## Traduction de l'extension *booktabs*

L'objectif de ce dépôt GIT est de traduire la documentation de l'extension *booktabs* utilisable avec LaTeX.

Cette traduction a la particularité d'avoir déjà été traitée totalement par Jean-Pierre Drucbert et Mathieu Goutelle sur la version v1.00 de l'extension, en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/required/tools) sous les noms `f-booktabs`.

Mathieu Goutelle ayant donné son accord, il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version v1.00 (datant de 1995) et la version v1.618033 (datant de 2016).


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex booktabs-fr.dtx
pdflatex booktabs-fr.dtx
makeindex -s gglo-fr.ist -o booktabs-fr.gls booktabs-fr.glo
makeindex -s gind-fr.ist -o booktabs-fr.ind booktabs-fr.idx
pdflatex booktabs-fr.dtx
pdflatex booktabs-fr.dtx
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
Page d'avant-propos           | :first_quarter_moon:   | 1               | 
1. Introduction               | :first_quarter_moon:   | 1               |
2. Mise en page de...         | :first_quarter_moon:   | 1               | 
3. Utilisation de nouvelles...| :first_quarter_moon:   | 2               |
4. Abus des nouvelles...      | :first_quarter_moon:   | 1               |
5. Booktabs et l'extension... | :first_quarter_moon:   | 1               |
6. Booktabs et l'extension... | :first_quarter_moon:   | 0               |
7. Profil technique des...    | :new_moon:             | 0 / 2           | En cours.
8. Remerciements              | :new_moon:             | 0 / 0           |
9. Le code                    | :new_moon:             | 0 / 7           |
Historique                    | :first_quarter_moon:   | 1               |
Index                         | :full_moon:            | 1               |


### Glossaire pour la traduction

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------
