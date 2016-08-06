## Traduction de l'extension *datetime2*

L'objectif est de traduire la documentation de l'extension *datetime2* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex datetime2-fr.dtx
pdflatex datetime2-fr.dtx
makeindex -s gglo-fr.ist -o datetime2-fr.gls datetime2-fr.glo
makeindex -s gind-fr.ist -o datetime2-fr.ind datetime2-fr.idx
pdflatex datetime2-fr.dtx
pdflatex datetime2-fr.dtx
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
Pages d'avant-propos          | :waxing_crescent_moon: | 2 / 4           | 
1. Introduction               | :new_moon:             | 0 / 1           |
2. Affichage de la date et... | :new_moon:             | 0 / 5           |
4. Stockage et affichage...   | :new_moon:             | 0 / 7           |
5. Styles                     | :new_moon:             | 0 / 5           |
6. Support multilingue        | :new_moon:             | 0 / 13          |
7. Noms de jour et de...      | :new_moon:             | 0 / 8           |
8. Options de l'extension     | :new_moon:             | 0 / 3           |
9. L'extension datetime2-calc | :new_moon:             | 0 / 6           |
10. Migrer depuis datetime    | :new_moon:             | 0 / 50          |
11. Le code                   | :new_moon:             | 0 / 64          |
Index                         | :new_moon:             | 0 / 5           |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
