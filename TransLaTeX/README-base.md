## Traduction de l'extension *[********]*

L'objectif est de traduire la documentation de l'extension *[********]* utilisable avec LaTeX. 

[********] Cette traduction a la particularité d'avoir déjà été traitée [********] par Jean-Pierre Drucbert sur la version [********] de l'extension, en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/required/tools) sous les noms `f-[********]`.

[********] Il s'agit ici donc de revoir cette traduction, l'extension n'ayant pas évoluée depuis la dernière traduction. Ceci permet aussi de mettre le document au format du *LaTeX Project*.

[********] Benjamin Bayart ayant donné son accord, il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version [********] (datant de [********]) et la version [********] (datant de [********]).

### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex [********]-fr.dtx
pdflatex [********]-fr.dtx
bibtex [********]-fr.aux
makeindex -s gglo-fr.ist -o [********]-fr.gls [********]-fr.glo
makeindex -s gind-fr.ist -o [********]-fr.ind [********]-fr.idx
pdflatex [********]-fr.dtx
pdflatex [********]-fr.dtx
```

Sur ce point, un fichier Makefile est mis à disposition (voir par exemple [OpenClassrooms](https://openclassrooms.com/courses/compilez-sous-gnu-linux#/id/r-1130480) pour plus d'informations).


### Avancement de la traduction, en vision table de matières

L'évolution est précisée par un code visuel identique à celui de la page principale mais avec une définition affinée :

- :new_moon: : traduction non entamée ;
- :waxing_crescent_moon: : traduction en cours ;
- :first_quarter_moon: : traduction achevée ;
- :waxing_gibbous_moon: : première relecture achevée (comparant original et traduction) ; 
- :full_moon: : seconde relecture achevée (vérifiant la cohérence de la traduction seule).

Section                       | Avancée                | Pages traduites | Commentaires 
----------------------------- | :--------------------: | :-------------: | -------------------------
En-tête du document tex       | :new_moon:             |                 |
Page[********] d'avant-propos | :new_moon:             | 0 / [********]  | 
1. [********]                 | :new_moon:             | 0 / [********]  |


### Glossaire pour la traduction

[********]Il n'y a pas eu besoin d'un glossaire pour cette traduction.

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
