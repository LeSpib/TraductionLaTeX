## Traduction de l'extension *glossaries*

L'objectif est de traduire le manuel utilisateur de l'extension *glossaries* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex glossaries-user-fr.tex
pdflatex glossaries-user-fr.tex
makeindex -s gglo-fr.ist -o glossaries-user-fr.gls glossaries-user-fr.glo
makeindex -s gind-fr.ist -o glossaries-user-fr.ind glossaries-user-fr.idx
makeglossaries glossaries-user-fr
pdflatex glossaries-user-fr.tex
pdflatex glossaries-user-fr.tex
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
Pages d'avant-propos          | :new_moon:             | 2 / 9           | 
Glossaire                     | :new_moon:             | 0 / 3           | 
1. Introduction               | :new_moon:             | 0 / 36          |
2. Options d'extension        | :new_moon:             | 0 / 23          |
3. Configuration              | :new_moon:             | 0 / 2           |
4. Définir des entrées de...  | :new_moon:             | 0 / 23          |
5. Listes de nombres          | :new_moon:             | 0 / 6           |
6. Liens vers les entrées...  | :new_moon:             | 0 / 23          |
7. Ajout d'une entrée...      | :new_moon:             | 0 / 2           |
8. Entrées à références...    | :new_moon:             | 0 / 4           |
9. Utilisation des termes...  | :new_moon:             | 0 / 8           |
10. Affichage d'un glossaire  | :new_moon:             | 0 / 5           |
11. Xindy (option 3)          | :new_moon:             | 0 / 8           |
12. Définition de nouveaux... | :new_moon:             | 0 / 3           |
13. Acronymes et autres...    | :new_moon:             | 0 / 26          |
14. Annulation et ...         | :new_moon:             | 0 / 8           |
15. Styles de glossaire       | :new_moon:             | 0 / 24          |
16. Utilitaires               | :new_moon:             | 0 / 8           |
17. Préfixes ou déterminants  | :new_moon:             | 0 / 5           |
18. Support d'accessibilité   | :new_moon:             | 0 / 2           |
19. Dépannage                 | :new_moon:             | 0 / 1           |
Index                         | :new_moon:             | 0 / 11          |


### Glossaire pour la traduction


Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
