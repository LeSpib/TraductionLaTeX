## Traduction de l'extension *boxedminipage2e*

L'objectif est de traduire la documentation de l'extension *boxedminipage2e* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex boxedminipage2e-fr.dtx
pdflatex boxedminipage2e-fr.dtx
makeindex -s gglo-fr.ist -o boxedminipage2e-fr.gls boxedminipage2e-fr.glo
makeindex -s gind-fr.ist -o boxedminipage2e-fr.ind boxedminipage2e-fr.idx
pdflatex boxedminipage2e-fr.dtx
pdflatex boxedminipage2e-fr.dtx
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
1. Introduction               | :new_moon:             | 0 / 1           |
2. Utilisation                | :new_moon:             | 0 / 0           |
3. Implémentation             | :new_moon:             | 0 / 2           |
Historique                    | :new_moon:             | 0 / 0           |
Index                         | :new_moon:             | 0 / 1           |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
