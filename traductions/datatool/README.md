## Traduction de l'extension *datatool*

L'objectif est de traduire la documentation de l'extension *datatool* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex datatool-user-fr.dtx
pdflatex datatool-user-fr.dtx
makeindex -s gglo-fr.ist -o datatool-user-fr.gls datatool-user-fr.glo
makeindex -s gind-fr.ist -o datatool-user-fr.ind datatool-user-fr.idx
pdflatex datatool-user-fr.dtx
pdflatex datatool-user-fr.dtx
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
Pages d'avant-propos          | :new_moon:             | 1 / 10          | 
1. Introduction               | :new_moon:             | 0 / 2           |
2. Types de données           | :new_moon:             | 0 / 18          |
3. Arithmérique en virgule... | :new_moon:             | 0 / 11          |
4. Chaînes de caractères      | :new_moon:             | 0 / 3           |  
5. Listes séparées par...     | :new_moon:             | 0 / 3           |
6. Bases de données           | :new_moon:             | 0 / 73          |
7. Créer un index, un...      | :new_moon:             | 0 / 30          |  
8. Diagramme en...            | :new_moon:             | 0 / 12          |
9. Diagramme de dispersion... | :new_moon:             | 0 / 16          |  
10. Histogrammes...           | :new_moon:             | 0 / 13          |  
11. Conversion d'une base...  | :new_moon:             | 0 / 20          |
12. Référencement de...       | :new_moon:             | 0 / 11          |
Bibliographie                 | :new_moon:             | 0 / 1           | 
Remerciements                 | :new_moon:             | 0 / 1           |
Index                         | :new_moon:             | 0 / 9           |

### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
