## Traduction de l'extension *layouts*

L'objectif est de traduire la documentation de l'extension *layouts* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex layouts-doc-fr.tex
pdflatex layouts-doc-fr.tex
makeindex -s gind-fr.ist -o layouts-doc-fr.ind layouts-doc-fr.idx
pdflatex layouts-doc-fr.tex
pdflatex layouts-doc-fr.tex
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
Page d'avant-propos           | :new_moon:             | 0 / 4           | 
1. Introduction               | :new_moon:             | 0 / 3           |
2. Etendue du corps de page   | :new_moon:             | 0 / 2           |
3. Mise en page               | :new_moon:             | 0 / 7           |
4. Mise en page de la...      | :new_moon:             | 0 / 4           |
5. Mise en page d'un...       | :new_moon:             | 0 / 3           |
6. Mise en page des flottants | :new_moon:             | 0 / 8           | 
7. Mise en page des listes    | :new_moon:             | 0 / 6           |
8. Mise en page des titres... | :new_moon:             | 0 / 4           |
9. Mise en page des notes...  | :new_moon:             | 0 / 4           | 
10. Mise en page de la...     | :new_moon:             | 0 / 4           | 
11. Mise en boîte de polices  | :new_moon:             | 0 / 1           |
Références                    | :new_moon:             | 0 / 1           |
Index                         | :new_moon:             | 0 / 4           |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
