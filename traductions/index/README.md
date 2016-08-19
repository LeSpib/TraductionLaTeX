## Traduction de l'extension *index*

L'objectif est de traduire la documentation de l'extension *index* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex index-fr.dtx
pdflatex index-fr.dtx
makeindex -s gind-fr.ist -o index-fr.ind index-fr.idx
pdflatex index-fr.dtx
pdflatex index-fr.dtx
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
Page d'avant-propos           | :first_quarter_moon:   | 0               | 
1. Introduction               | :new_moon:             | 0 / 1           |
2. Création d'un index...     | :new_moon:             | 0 / 0           |
3. Interface utilisateur      | :new_moon:             | 0 / 3           |
4. Avertissements             | :new_moon:             | 0 / 0           |
5. À faire                    | :new_moon:             | 0 / 0           |
6. Le code                    | :new_moon:             | 0 / 12          |
7. Historique                 | :new_moon:             | 0 / 2           |
8. Fichier d'exemple          | :new_moon:             | 0 / 1           |
Index                         | :new_moon:             | 0 / 1           |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
