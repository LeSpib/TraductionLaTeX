## Traduction de l'extension *pgf (tikz)*

L'objectif est de traduire la documentation de l'extension *pgf (tikz)* utilisable avec LaTeX. 

La documentation, volumineuse, est associée ici à de nombreux fichiers et le document d'origine prévoit une organisation des fichiers par langue. Cette organisation est donc reprise à l'identique. Ainsi les fichiers à traduire sont (pour l'essentiel) dans `text-en' et les fichiers traduits dans `text-fr`.

La documentation prévoit aussi différents types de compilation. La traduction se base sur la version `luatex` car elle permet l'affichage de tout le document (certaines sections n'étant affichées qu'avec `luatex`).

Enfin, l'introduction de l'extension `babel` ne permet pas de générer pour le moment l'intégralité du document (la compilation mentionne des anomalies mais ne s'arrête pas). Ce problème sera traité en cours de traduction.


### Commandes pour obtenir le document

Pour obtenir le document, un fichier Makefile a déjà été constitué par l'auteur. Il est situé dans le dossier `version-for-luatex/fr`.

Sur la notion de fichier Makefile, voir par exemple [OpenClassrooms](https://openclassrooms.com/courses/compilez-sous-gnu-linux#/id/r-1130480) pour plus d'informations.


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
Pages d'avant-propos          | :new_moon:             | 0 / 24          | 
1. Introduction               | :new_moon:             | 0 / 3           | 
2. Tutoriel : une figure...   | :new_moon:             | 0 / 19          | 
3. Tutoriel : un réseau de... | :new_moon:             | 0 / 11          | 
4. Tutoriel : une version...  | :new_moon:             | 0 / 8           | 
5. Tutoriel : des...          | :new_moon:             | 0 / 9           | 
6. Tutoriel : un plan de...   | :new_moon:             | 0 / 15          | 
7. Lignes de conduite pour... | :new_moon:             | 0 / 7           | 
8. Installation               | :new_moon:             | 0 / 3           | 
9. Licences et copyright      | :new_moon:             | 0 / 13          | 
10. Formats supportés         | :new_moon:             | 0 / 5           | 
11. Principes de conception   | :new_moon:             | 0 / 5           | 
12. Structures...             | :new_moon:             | 0 / 7           | 
13. Spécification des...      | :new_moon:             | 0 / 16          | 
14. Syntaxe des chemins...    | :new_moon:             | 0 / 7           | 
15. Actions sur des chemins   | :new_moon:             | 0 / 17          | 
16. Flêches                   | :new_moon:             | 0 / 31          | 
17. Noeuds et arrêtes         | :new_moon:             | 0 / 36          | 
18. Pics : de petites...      | :new_moon:             | 0 / 6           | 
19. Spécification de graphes  | :new_moon:             | 0 / 47          | 
20. Matrices et alignement    | :new_moon:             | 0 / 11          | 
21. Faire croître les arbres  | :new_moon:             | 0 / 10          | 
22. Tracé de fonctions        | :new_moon:             | 0 / 11          |  
23. Transparence              | :new_moon:             | 0 / 11          | 
24. Chemins décorés           | :new_moon:             | 0 / 7           | 
25. Transformations           | :new_moon:             | 0 / 6           | 
(le reste)                    | :new_moon:             | 0 / 776         |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
