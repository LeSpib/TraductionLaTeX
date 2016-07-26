## Traduction de l'extension *calc*

L'objectif est de traduire la documentation de l'extension *calc* utilisable avec LaTeX. 

Cette traduction a la particularité d'avoir déjà été traitée partiellement par Jean-Pierre Drucbert sur la version v4.1a de l'extension, en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/required/tools) sous les noms `f-calc`.

Benjamin Bayart ayant donné son accord, il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version v4.1b (datant de 1998) et la version v4.3 (datant de 2014).

### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex calc-fr.dtx
pdflatex calc-fr.dtx
makeindex -s gglo-fr.ist -o calc-fr.gls calc-fr.glo
pdflatex calc-fr.dtx
pdflatex calc-fr.dtx
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
Page d'avant-propos           | :new_moon:             | 0 / 0           | 
1. Introduction               | :new_moon:             | 0 / 1           |
2. Description informelle     | :new_moon:             | 0 / 3           |
3. Syntaxe formelle           | :new_moon:             | 0 / 1           |
4. La mécanique d'évaluation  | :new_moon:             | 0 / 2           |
5. Implémentation             | :new_moon:             | 0 / 10          |
6. Rapport d'erreurs          | :new_moon:             | 0 / 0           |
7. Autres additions           | :new_moon:             | 0 / 1           |
Références                    | :new_moon:             | 0 / 0           |
Historique                    | :new_moon:             | 0 / 1           |

### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
