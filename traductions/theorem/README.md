## Traduction de l'extension *theorem*

L'objectif est de traduire la documentation de l'extension *theorem* utilisable avec LaTeX. 

Cette traduction a la particularité d'avoir déjà été traitée partiellement par Jean-Pierre Drucbert sur la version v2.2c de l'extension, en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/required/tools) sous les noms `f-theorem`.

Benjamin Bayart ayant donné son accord, il s'agit ici donc de compléter et revoir cette traduction, l'extension n'ayant pas évoluée depuis la dernière traduction. Ceci permet aussi de mettre le document au format du *LaTeX Project*.


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex theorem-fr.dtx
pdflatex theorem-fr.dtx
makeindex -s gglo-fr.ist -o theorem-fr.gls theorem-fr.glo
pdflatex theorem-fr.dtx
pdflatex theorem-fr.dtx
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
Page d'avant-propos           | :new_moon:             | 0 / 1           | 
1. Introduction               | :new_moon:             | 0 / 0           |
2. L'interface utilisateur    | :new_moon:             | 0 / 3           |
3. Considérations...          | :new_moon:             | 0 / 0           |
4. Remerciements              | :new_moon:             | 0 / 0           |
5. Le pilote de documentation | :new_moon:             | 0 / 1           |
6. Définition des commandes   | :new_moon:             | 0 / 10          |
Références                    | :new_moon:             | 0 / 0           |
Historique                    | :new_moon:             | 0 / 1           |

### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
