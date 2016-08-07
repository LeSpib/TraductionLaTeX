## Traduction de l'extension *tocbibind*

L'objectif de ce dépôt GIT est de traduire la documentation de l'extension *tocbibind* utilisable avec LaTeX.


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex tocbibind-fr.dtx
pdflatex tocbibind-fr.dtx
makeindex -s gind-fr.ist -o tocbibind-fr.ind tocbibind-fr.idx
pdflatex tocbibind-fr.dtx
pdflatex tocbibind-fr.dtx
```

Sur ce point, un fichier Makefile est mis à disposition (voir par exemple [OpenClassrooms](https://openclassrooms.com/courses/compilez-sous-gnu-linux#/id/r-1130480) pour plus d'informations).


### Avancement de la traduction, en vision table de matières

L'évolution est précisée par un code visuel identique à celui de la page principale mais avec une définition affinée :

- :new_moon: : traduction non entamée ;
- :waxing_crescent_moon: : traduction en cours ;
- :first_quarter_moon: : traduction achevée ;
- :waxing_gibbous_moon: : première relecture achevée (comparant original et traduction) ; 
- :full_moon: : seconde relecture achevée (vérifiant la cohérence de la traduction seule).

Section                       | Avancée                | Pages traduites |   Commentaires 
----------------------------- | :--------------------: | :-------------: | -------------------------
En-tête du document tex       | :new_moon:             |                 |
Page d'avant-propos           | :first_quarter_moon:   | 1               | 
1. Introduction               | :first_quarter_moon:   | 1               | 
2. L'extension tocbibind      | :first_quarter_moon:   | 4               | 
3. Le code de l'extension     | :first_quarter_moon:   | 9               | 
Références                    | :first_quarter_moon:   | 1               |
Index                         | :first_quarter_moon:   | 2               |   


### Glossaire pour la traduction

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------
