## Traduction de l'extension *appendix*

L'objectif est de traduire la documentation de l'extension *appendix* utilisable avec LaTeX. 

Cette traduction a la particularité d'avoir déjà été traitée totalement sur la version v1.0 de l'extension par Jean-Pierre Drucbert (ci-dessous le fichier *f-appendix*), en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/contrib/supported/appendix).

Il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version v1.0 (datant de 1998) et la version v1.2b (datant de 2009).

### Commandes pour obtenir le document

    pdflatex appendix-fr.dtx
    makeindex -s gind-fr.ist appendix-fr.idx
    pdflatex appendix-fr.dtx
    pdflatex appendix-fr.dtx

Le fichier gind-fr.ist se base sur le fichier gind.ist classique. Il intègre uniquement deux lignes supplémentaires pour bien traduire l'index en français (sans cela, les termes "Symboles" et "Nombres" en titre dans les colonnes de l'index serait toujours en anglais) :

    symhead_positive  "Symboles"
    numhead_positive  "Nombres"

### Quelques termes récurrents dans la traduction de ce document
- *appendix* : annexe. 

### Avancement de la traduction, en vision table de matières
- [x] En-tête du document tex (définitions, métadonnées)
- [x] Introduction (1 page)
- [x] L'extension *appendix* (3 pages)
  - [x] Problèmes connus
- [x] Le code de l'extension (9 pages)
- [x] Références (1 page)
- [x] Index (1 page)
