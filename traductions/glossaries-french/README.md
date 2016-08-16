## Traduction de l'extension *glossaries-french*

L'objectif est de traduire la documentation de l'extension *glossaries-french* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex glossaries-french-fr.dtx
pdflatex glossaries-french-fr.dtx
makeindex -s gglo-fr.ist -o glossaries-french-fr.gls glossaries-french-fr.glo
makeindex -s gind-fr.ist -o glossaries-french-fr.ind glossaries-french-fr.idx
pdflatex glossaries-french-fr.dtx
pdflatex glossaries-french-fr.dtx
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
Entête du document tex        | :full_moon:            |                 | Entête peu important.
Page d'avant-propos           | :full_moon:            | 0               | 
1. Implémentation             | :full_moon:            | 2               |


### Glossaire pour la traduction

Il n'y a pas eu besoin d'un glossaire pour cette traduction.
