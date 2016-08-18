## Traduction de l'extension *array*

L'objectif de ce dépôt GIT est de traduire la documentation de l'extension *array* utilisable avec LaTeX.

Cette traduction a la particularité d'avoir déjà été traitée partiellement par Jean-Pierre Drucbert sur la version v2.3m de l'extension, en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/required/tools) sous les noms `f-array`.

Il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version v2.3m (datant de 1998) et la version v2.4c (datant de 2014). L'accord a été donné par Benjamin Bayart.


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées.

```bash
pdflatex array-fr.dtx
pdflatex array-fr.dtx
makeindex -s gind-fr.ist -o array-fr.ind array-fr.idx
makeindex -s gglo-fr.ist -o array-fr.gls array-fr.glo
pdflatex array-fr.dtx
pdflatex array-fr.dtx
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
Pages d'avant-propos          | :first_quarter_moon:   | 1               | 
1. Introduction               | :new_moon:             | 1 / 3           |
2. Derniers commentaires      | :new_moon:             | 0 / 2           | 
3. Le pilote de documentation | :new_moon:             | 0 / 1           | 
4. La construction du...      | :new_moon:             | 0 / 3           | 
5. L'insertion de déclarations| :new_moon:             | 0 / 4           | 
6. Les commandes...           | :new_moon:             | 0 / 5           | 
7. Construction et appel de...| :new_moon:             | 0 / 1           | 
8. Le séparateur de rangées   | :new_moon:             | 0 / 1           | 
9. Extension de cellules...   | :new_moon:             | 0 / 1           | 
10. Définitions de...         | :new_moon:             | 0 / 1           | 
11. Définitions de...         | :new_moon:             | 0 / 1           | 
12. Définitions de ses...     | :new_moon:             | 0 / 6           |
Index                         | :new_moon:             | 0 / 2           |
Historique                    | :new_moon:             | 0 / 3           |
Références                    | :new_moon:             | 0 / 0           | 

### Quelques termes récurrents dans la traduction de ce document

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------
