## Commandes et fichiers associés à la traduction en français

Une extension `translatex-fr` a été constituée pour simplifier la gestion du préambule des documents à traduire. Elle présente deux options : `ltxdoc` qui charge les différentes fonctions présentées ci-après et `babel` qui charge l'extension babel (avec son option `french`). Cette extension est développée au fur et à mesure des traductions rencontrées pour essayer de la rendre la plus générale possible. Sa documentation reste à faire mais les éléments ci-dessous décrivent la plupart des éléments.

### Commandes pour marquer la traduction

Les trois commandes pour marquer les endroits encore non traduits utilisent un symbole issu de l'extension `pifont` ainsi que les commandes de couleur tirées de `xcolor`.

```tex
% Bloc temporaire pour la traduction (retranché une fois le doc traduit)
\usepackage{xcolor}
\usepackage{pifont}
\definecolor{orange5}{RGB}{255,153,0} 
\newcommand{\trad}[1]{\textbf{\textcolor{orange5}{\noindent\ding{54} #1 \ding{54}}}}
\newcommand{\tradini}{\color{orange5}\ding{54}}
\newcommand{\tradfin}{\ding{54}\color{black}}
% Fin du bloc temporaire
```
### Commande pour les en-tête du *LaTeX Project*

La classe `ltxdoc` contient une commande permettant de générer un cadre en début de document donnant des informations en lien avec l'équipe du *LaTeX Project*. La définition suivante en traduit les termes.

```tex
\makeatletter
\def\MaintainedByLaTeXTeam#1{%
{\gdef\@maintainedby{%
Ce fichier est maintenu par l'équipe du \og \LaTeX{} Project \fg{}.\\%
Les rapports d'anomalie peuvent être envoyés en anglais à \\%
\url{http://latex-project.org/bugs.html} (catégorie \texttt{#1}).}}}
\makeatother
```

### Commandes pour le traitement de l'index

Le texte figurant en prologue de l'index est traduit avec la commande `\IndexPrologue` pensée pour remplacer le texte proposé par défaut. 

```tex
\IndexPrologue{\section*{Index}\markboth{Index}{Index} Les numéros en italique 
renvoient à la page où se trouve l'entrée correspondante; les numéros soulignés
renvoient à la ligne de code de la définition; les numéros en romain renvoient
aux lignes de code où l'entrée est utilisée.}
```

Dans les classes `doc` et `ltxdoc`, les entrées d'index associées à des environnements appliquent des définitions intégrant le terme *environment*. Les définitions sont ici écrasées par des définitions où seuls les termes anglais ont été modifiés.

```tex
\makeatletter
\def\SpecialMainEnvIndex#1{\@bsphack\special@index{%
                                      #1\actualchar
                                      {\string\ttfamily\space#1}
                                         (environnement)%
                                      \encapchar main}%
    \special@index{environnements:\levelchar#1\actualchar{%
                   \string\ttfamily\space#1}\encapchar
           main}\@esphack}
\def\SpecialEnvIndex#1{\@bsphack
    \index{#1\actualchar{\protect\ttfamily#1}
           (environnement)\encapchar usage}%
    \index{environnements:\levelchar#1\actualchar
          {\protect\ttfamily#1}\encapchar usage}\@esphack}
\makeatother
```

### Fichier pour le traitement de l'index

Le fichier `gind-fr.ist` se base sur le fichier `gind.ist` classique. Il intègre uniquement deux lignes supplémentaires pour bien traduire l'index en français. Sans cela, les termes *Symboles* et *Nombres* en titre dans les colonnes de l'index seraient toujours en anglais. Ces lignes sont :

```tex
symhead_positive  "Symboles"
numhead_positive  "Nombres"
```
La constitution de l'index fait donc appel à ce nouveau fichier de style. En supposant un fichier nommé `extension-fr`, la commande à utiliser est alors :

```bash
makeindex -s gind-fr.ist -o extension-fr.ind extension-fr.idx
```

### Commandes pour le traitement du glossaire

Dans les classes `doc` et `ltxdoc`, le glossaire est utilisé pour traiter l'historique des versions d'un document. Le titre du glossaire est ici remplacé par sa traduction. De plus, le titre associé aux entrées non rattachées à une commande en particulier est également traduit.

```tex
\makeatletter
\def\glossary@prologue{\section*{{Historique}}%
               \markboth{{Historique}}{{Historique}}%
               }
\def\generalname{Général}
\makeatother
```

### Fichier pour le traitement du glossaire

Le fichier `gglo-fr.ist` se base sur le fichier `gglo.ist` classique. L'idée est ici la même que pour le fichier `gind-fr.ist` avec l'ajout de deux lignes :

```tex
symhead_positive  "Symboles"
numhead_positive  "Nombres"
```
La constitution de l'index fait donc appel à ce nouveau fichier de style. En supposant un fichier nommé `extension-fr`, la commande à utiliser est alors :

```bash
makeindex -s gglo-fr.ist -o extension-fr.gls extension-fr.glo
```

### Date de fichier en français

La date d'un fichier, telle que restituée par LaTeX avec la fonction \filedate après utilisation de \GetFileInfo, est au format "AAAA/MM/JJ". Le code ci-dessous la remet dans l'ordre français "JJ/MM/AAAA". Ce retraitement est une reprise d'une réponse de [Leo Liu](http://tex.stackexchange.com/questions/54594/tex-capacity-exceeded-while-parsing-a-date-string). La fonction \filedatefr restitue le résultat souhaité.

```tex
\def\parsedate#1{\edef\temp{#1}%
  \expandafter\parsedateX\temp\relax}
\def\parsedateX #1/#2/#3\relax{\def\filedatefr{#3/#2/#1}}
```
