## Traduction de l'extension *booktabs*

L'objectif de ce dépôt GIT est de traduire la documentation de l'extension *booktabs* utilisable avec LaTeX.

Cette traduction a la particularité d'avoir déjà été traitée totalement sur la version v1.00 de l'extension par Jean-Pierre Drucbert et Mathieu Goutelle (ci-dessous le fichier *f-booktabs*), en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/contrib/supported/booktabs).

Il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version v1.00 (datant de 1995) et la version v1.618033 (datant de 2016).

### Commandes pour obtenir le document

```bash
pdflatex booktabs-fr.dtx
pdflatex booktabs-fr.dtx
makeindex -s gglo-fr.ist -o booktabs-fr.gls booktabs-fr.glo
makeindex -s gind-fr.ist -o booktabs-fr.ind booktabs-fr.idx
pdflatex booktabs-fr.dtx
pdflatex booktabs-fr.dtx
```

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
Page d'avant-propos           | :first_quarter_moon:   | 1 / 1           | 
1. Introduction               | :new_moon:             | 0 / 1           |
2. La mise en page de...      | :new_moon:             | 0 / 1           | 
3. Utilisation de nouvelles...| :new_moon:             | 0 / 1           |
4. Abus des nouvelles...      | :new_moon:             | 0 / 1           |
5. Booktabs et longtable      | :new_moon:             | 0 / 1           |
6. Booktabs et colortbl       | :new_moon:             | 0 / 1           |
7. Résumé technique des...    | :new_moon:             | 0 / 1           |
8. Remerciements              | :new_moon:             | 0 / 1           |
9. Le code                    | :new_moon:             | 0 / 6           |
Historique des versions       | :new_moon:             | 0 / 1           |
Index                         | :new_moon:             | 0 / 1           |

### Glossaire pour la traduction

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------
