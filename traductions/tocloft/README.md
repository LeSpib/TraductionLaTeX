## Traduction de l'extension *tocloft*

L'objectif est de traduire la documentation de l'extension *tocloft* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex tocloft-fr.dtx
pdflatex tocloft-fr.dtx
makeindex -s gind-fr.ist -o tocloft-fr.ind tocloft-fr.idx
pdflatex tocloft-fr.dtx
pdflatex tocloft-fr.dtx
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
Entête du document tex        | :new_moon:             |                 |
Page d'avant-propos           | :new_moon:             | 0 / 1           | 
1. Introduction               | :new_moon:             | 0 / 4           |
2. L'extension tocloft        | :new_moon:             | 0 / 12          |
3. Le code de l'extension     | :new_moon:             | 0 / 31          |
Références                    | :new_moon:             | 0 / 1           |
Index                         | :new_moon:             | 0 / 5           |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
