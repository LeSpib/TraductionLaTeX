## Traduction de l'extension *appendix*

L'objectif est de traduire la documentation de l'extension *appendix* utilisable avec LaTeX. 

Cette traduction a la particularité d'avoir déjà été traitée totalement par Jean-Pierre Drucbert sur la version v1.0 de l'extension, en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/required/tools) sous les noms *f-appendix*.

Il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version v1.0 (datant de 1998) et la version v1.2b (datant de 2009). L'accord a été donné par Benjamin Bayart.

### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex appendix-fr.dtx
pdflatex appendix-fr.dtx
makeindex -s gind-fr.ist appendix-fr.idx
pdflatex appendix-fr.dtx
pdflatex appendix-fr.dtx
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
En-tête du document tex       | :full_moon:            |                 |
Page d'avant-propos           | :full_moon:            | 1               | 
1. Introduction               | :full_moon:            | 1               |
2. L'extension *appendix*     | :full_moon:            | 3               | 
3. Le code de l'extension     | :full_moon:            | 9               |
Références                    | :full_moon:            | 1               |
Index                         | :full_moon:            | 1               |


### Glossaire pour la traduction

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------
appendix                  | annexe                                            | 

