## Traduction de l'extension *lettrine*

L'objectif est de traduire la documentation de l'extension *lettrine* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex lettrine-fr.dtx
pdflatex lettrine-fr.dtx
makeindex -s gglo-fr.ist -o lettrine-fr.gls lettrine-fr.glo
pdflatex lettrine-fr.dtx
pdflatex lettrine-fr.dtx
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
Page d'avant-propos           | :first_quarter_moon:   | 0               | 
1. Introduction               | :new_moon:             | 0 / 4           |
2. Détails TeXniques          | :new_moon:             | 0 / 8           |
Historique                    | :new_moon:             | 0 / 1           |


### Glossaire pour la traduction

[********]Il n'y a pas eu besoin d'un glossaire pour cette traduction.

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
