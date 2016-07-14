## TransLaTeX - Traduction en français d'extensions courantes de LaTeX

L'objectif de ce projet est de traduire en français la documentation de différentes extensions de LaTeX. En espérant que cela aide le plus grand monde ! :smile:

> *The goal of this project is to translate into French the documentation of several LaTeX packages. Hope this helps !* :smile:


### Aspects juridiques

Nous reprenons ici le principe retenu par un projet de traduction datant de 2000 : [French translations], ci-après noté FT.

Toutes ces traductions sont régies par la License Publique du Projet LaTeX (LPPL). Elles sont donc librement distribuables, du moment que le code des extensions inclus dans les documentations l'est (il n'est pas de notre ressort). Si vous êtes autorisés à utiliser une extension d'une certaine façon, alors vous êtes autorisé à faire la même chose avec la version française de sa documentation. Les seules restrictions (imposées par la LPPL) sont sur la traduction elle-même.

:heavy_exclamation_mark: En quelques mots: ne modifiez pas un document si vous trouvez une faute, indiquez-la plutôt à la bonne personne (l'auteur de l'extension, le traducteur, l'équipe de traduction, etc).

> *All those translations are under the LaTeX Project Public License. Thus they are freely distributable, as long as the code of the packages that is in the document (which does not belong to us) is itself freely distributable. If you're allowed to use a package in a given way, then you are allowed to use the French translation of its documentation in exactly the same way. The only restrictions (imposed by the LPPL) are on the translation itself.*

> :heavy_exclamation_mark: *In short: do not modify a document if you find a mistake, just contact the right person (the author of the package, the person who translated it, the translation team, etc).*


### Liste des extensions traitées et avancement des traductions

Ce tableau indique les différentes extensions envisagées dans le projet ainsi que l'avancement de ces traductions. Le code visuel pour l'avancée de la traduction reprend les phases de la lune, soit dans l'ordre : :new_moon: :waxing_crescent_moon: :first_quarter_moon: :waxing_gibbous_moon: :full_moon: (plus c'est jaune, mieux c'est).

> *This table shows the different extensions foreseen for this project and the progress of these translations. The visual code for the translation progress uses the phases of the moon and their order :* :new_moon: :waxing_crescent_moon: :first_quarter_moon: :waxing_gibbous_moon: :full_moon: *(the brighter, the better).*

Traduction      | Source              | Avancée                | Pages traduites | Commentaires 
--------------- | ------------------- | :--------------------: | :-------------: | ------------------------------------
[adjustbox-fr]  | [adjustbox] v1.0    | :new_moon:             | 0 / 29          |
[appendix-fr]   | [appendix] v1.2b    | :full_moon:            | 16              | Traduction préexistante ([FT-tools]).
[booktabs-fr]   | [booktabs] 1.618033 | :new_moon:             | 7 / 17          | Traduction préexistante ([FT-tools]).
                | [cleveref]          |                        | *. / 31*        |
                | [datatool]          |                        | *. / 220*       |
                | [datetime2]         |                        | *. / 169*       |
                | [etoc]              |                        | *. / 114*       |
[fontspec-fr]   | [fontspec] v2.4e    | :new_moon:             | 7 / 123         | Auteur contacté et intéressé.
[geometry-fr]   | [geometry] v5.6     | :full_moon:            | 42              | Auteur contacté et intéressé.
                | [glossaries]        |                        | *. / 248*       |
                | [hyperref]          |                        | *. / 31*        | Licence GNU FDL à analyser.
[indentfirst-fr]| [indentfirst] v1.03 | :new_moon:             | 0 / 1          | Traduction préexistante ([FT-tools]).

[lipsum-fr]     | [lipsum] v1.3       | :full_moon:            | 41              |
                | [pgfplots]          |                        | *. / 544*       |
                | [siunitx]           |                        | *. / 102*       |
                | [tikz] (pgf)        |                        | *. / 1161*      |
[titlesec-fr]   | [titlesec] 2.10.2   | :full_moon:            | 25              | 
[tocbibind-fr]  | [tocbibind] v1.5k   | :waxing_crescent_moon: | 9 / 18          | 
[varioref-fr]   | [varioref] v1.5c    | :new_moon:             | 0 / 35          | Traduction préexistante ([FT-tools]).
[xcolor-fr]     | [xcolor] v2.12      | :new_moon:             | 29 / 73         | 
[xkeyval-fr]    | [xkeyval] v2.7      | :new_moon:             | 1 / 73          |
[xspace-fr]     | [xspace] v1.13      | :waxing_crescent_moon: | 5 / 7           | Traduction préexistante ([FT-tools]).

### Traduction des documents 

##### Fichiers associés à la traduction

Les fichiers employés par LaTeX utilisent par défaut des termes anglais, tout particulièrement l'index composé dans la plupart des extensions avec le fichier de style `gind.ist`. Quelques commandes placées dans le préambule du document principal permettent de traduire (par redéfinition) la plupart de ces termes mais certains cas demandent un fichier extérieur. Ces fichiers spécifiques sont placés dans le dossier [TransLaTeX] avec l'explicitation des commandes placées en préambule.

> *LaTeX files display English terms by default, especially when typesetting the index with the style file `gind.ist`. Some macros placed in the preamble of the main document are used to translate (by redefinition) most of these terms, but some cases require an external file. These specific files are placed in the [TransLaTeX] directory with some explanations, along with other macros used for translation.*


##### Formalisation de l'avancée de la traduction

Le résultat courant de chaque traduction est fourni en PDF avec des passages mis en orange pour indiquer les passages ou éléments restant à traduire. Ces marques sont parfois un peu approximatives pour certains éléments ajoutés au texte comme les tables et index.

Ces marques sont gérées par trois commandes placées en préambule de document : `\trad{}`, `\tradini` et `\tradfin`. Les commandes et leur définition seront retirées une fois la traduction achevée.

> *The current result of each translation is provided in PDF with passages set in orange to indicate the remaining elements or passages to translate. These indications are sometimes a little rough for some elements added to the text, such as tables and indexes.*

> *These indications are managed by three macros placed in the document preamble: `\trad{}`, `\tradini` and `\tradfin`. These macros and their definitions are removed when the translation is finished.*


##### Glossaire pour la traduction

De nombreux termes spécifiques se retrouvent dans les différents documents traduits. Cette section sert de glossaire en regroupant certains de ces termes. Chaque traduction d'extension reprend ce principe dans son ReadMe de façon plus ciblée.

> *Many specific terms are found in the various documents translated. This section functions as a glossary by grouping some of these terms. Each translation has its own glossary in its ReadMe file.*

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
*control sequence*     | commande                                       |   
*cropmarks*            | traits de coupe                                | source Wiktionnaire
*device*               | périphérique, input/output d'entrée de sortie  |
*driver*               | pilote (informatique, graphique...)            |
*em dash*              | tiret quadratin                                |
*en dash*              | tiret demi-quadratin                           |
*error report*         | rapports d'erreur                              |
*filler*               | motif (de remplissage)                         |
*header*               | en-tête                                        |
*heading(s)*           | titre                                          |
*leaders*              | points de conduite                             |
*leading*              | interlignage                                   |
*package*              | extension                                      |
*style guide*          | code typographique                             | source Wikipédia
*token*                | unité lexicale                                 | source Traduction française du TeXbook


[//]: # (Sur le Markdown : https://guides.github.com/features/mastering-markdown/)


[French translations]: <https://www.ctan.org/pkg/french-translations>
[FT-tools]:      <https://www.ctan.org/tex-archive/info/french-translations/macros/latex/required/tools>
[adjustbox]:     <https://www.ctan.org/pkg/adjustbox>
[adjustbox-fr]:  <https://github.com/LeSpib/TransLaTeX/tree/master/adjustbox>
[appendix]:      <https://www.ctan.org/pkg/appendix>
[appendix-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/appendix>
[booktabs]:      <https://www.ctan.org/pkg/booktabs>
[booktabs-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/booktabs>
[cleveref]:      <https://www.ctan.org/pkg/cleveref>
[cleveref-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/cleveref>
[datatool]:      <https://www.ctan.org/pkg/datatool>
[datatool-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/datatool>
[datetime2]:     <https://www.ctan.org/pkg/datetime2>
[datetime2-fr]:  <https://github.com/LeSpib/TransLaTeX/tree/master/datetime2>
[etoc]:          <https://www.ctan.org/pkg/etoc>
[etoc-fr]:       <https://github.com/LeSpib/TransLaTeX/tree/master/etoc>
[fontspec]:      <https://www.ctan.org/pkg/fontspec>
[fontspec-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/fontspec>
[geometry]:      <https://www.ctan.org/pkg/geometry>
[geometry-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/geometry>
[glossaries]:    <https://www.ctan.org/pkg/glossaries>
[glossaries-fr]: <https://github.com/LeSpib/TransLaTeX/tree/master/glossaries>
[hyperref]:      <https://www.ctan.org/pkg/hyperref>
[hyperref-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/hyperref>
[lipsum]:        <https://www.ctan.org/pkg/lipsum>
[lipsum-fr]:     <https://github.com/LeSpib/TransLaTeX/tree/master/lipsum>
[listings]:      <https://www.ctan.org/pkg/listings>
[listings-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/listings>
[pgfplots]:      <https://www.ctan.org/pkg/pgfplots>
[pgfplots-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/pgfplots>
[siunitx]:       <https://www.ctan.org/pkg/siunitx>
[siunitx-fr]:    <https://github.com/LeSpib/TransLaTeX/tree/master/siunitx>
[titlesec]:      <https://www.ctan.org/pkg/titlesec>
[titlesec-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/titlesec>
[tocbibind]:     <https://www.ctan.org/pkg/tocbibind>
[tocbibind-fr]:  <https://github.com/LeSpib/TransLaTeX/tree/master/tocbibind>
[tikz]:          <https://www.ctan.org/pkg/pgf>
[tikz-fr]:       <https://github.com/LeSpib/TransLaTeX/tree/master/tikz>
[varioref]:      <https://www.ctan.org/pkg/varioref>
[varioref-fr]:   <https://github.com/LeSpib/TransLaTeX/tree/master/varioref>
[xcolor]:        <https://www.ctan.org/pkg/xcolor>
[xcolor-fr]:     <https://github.com/LeSpib/TransLaTeX/tree/master/xcolor>
[xkeyval]:       <https://www.ctan.org/pkg/xkeyval>
[xkeyval-fr]:    <https://github.com/LeSpib/TransLaTeX/tree/master/xkeyval>
[xspace]:        <https://www.ctan.org/pkg/xspace>
[xspace-fr]:     <https://github.com/LeSpib/TransLaTeX/tree/master/xspace>
[TransLaTeX]:    <https://github.com/LeSpib/TransLaTeX/tree/master/TransLaTeX>
