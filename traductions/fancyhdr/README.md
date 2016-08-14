## Traduction de l'extension *fancyhdr*

L'objectif est de traduire la documentation de l'extension *fancyhdr* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex fancyhdr-fr.dtx
pdflatex fancyhdr-fr.dtx
makeindex -o fancyhdr-fr.ind fancyhdr-fr.idx
pdflatex fancyhdr-fr.dtx
pdflatex fancyhdr-fr.dtx
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
Page d'avant-propos           | :waxing_crescent_moon: | 0 / 1           | 
1. Introduction               | :first_quarter_moon:   | 2               |
2. Entêtes et pieds de page   | :first_quarter_moon:   | 1               |
3. Qu'est donc fancyhdr ?     | :first_quarter_moon:   | 0               |
4. Utilisation simple de...   | :first_quarter_moon:   | 1               |
5. Exemple simple             | :first_quarter_moon:   | 1               |
6. Exemple d'impression...    | :new_moon:             | 0 / 1           |
7. Redéfinition du style...   | :new_moon:             | 0 / 0           |
8. Mise en page par défaut    | :new_moon:             | 0 / 1           |
9. Marques de LaTeX           | :new_moon:             | 0 / 2           |
10. Entêtes à la manière...   | :new_moon:             | 0 / 1           |
11. Mises en page...          | :new_moon:             | 0 / 1           |
12. La largeur des entêtes... | :new_moon:             | 0 / 1           |
13. Deux exemples de livre    | :new_moon:             | 0 / 1           |
14. Mise en page spécifique...| :new_moon:             | 0 / 0           |
15. Pages vides               | :new_moon:             | 0 / 1           |
16. Style de numérotation...  | :new_moon:             | 0 / 0           |
17. Numéros de page liés...   | :new_moon:             | 0 / 1           |
18. Quand changer les...      | :new_moon:             | 0 / 1           |
19. Entêtes et pieds de...    | :new_moon:             | 0 / 2           |
20. Un film                   | :new_moon:             | 0 / 0           |
21. Onglets                   | :new_moon:             | 0 / 1           |
22. Placement de flottant     | :new_moon:             | 0 / 3           |
23. Flottants sur plusieurs...| :new_moon:             | 0 / 2           |
24. Contact                   | :new_moon:             | 0 / 0           |
Index                         | :new_moon:             | 0 / 1           |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
