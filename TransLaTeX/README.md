## Commandes et fichiers associés à la traduction en français

### Commandes pour marquer la traduction

Les trois commandes pour marquer les endroits encore non traduits utilisent un symbole issu de l'extension `pifont` ainsi que les commandes de couleur tirées de `xcolor`.

```tex
\usepackage{xcolor}
\usepackage{pifont}
\definecolor{orange5}{RGB}{255,153,0} 
\newcommand{\trad}[1]{\textbf{\textcolor{orange5}{\noindent\ding{54} #1 \ding{54}}}}
\newcommand{\tradini}{\color{orange5}\ding{54}}
\newcommand{\tradfin}{\ding{54}\color{black}}
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
makeindex -s gind-fr.ist extension-fr.idx
```
