## Traduction de l'extension *multicol*

L'objectif est de traduire la documentation de l'extension *multicol* utilisable avec LaTeX. 

Cette traduction a la particularité d'avoir déjà été traitée totalement par Jean-Pierre Drucbert et Françoise Marre-Fournier sur la version v1.5w de l'extension, en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/info/french-translations/macros/latex/required/tools) sous les noms `f-multicol`.

Benjamin Bayart ayant donné son accord, il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version v1.5w (datant de 1999) et la version v1.8p (datant de 2016).


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex multicol-fr.dtx
pdflatex multicol-fr.dtx
makeindex -s gglo-fr.ist -o multicol-fr.gls multicol-fr.glo
makeindex -s gind-fr.ist -o multicol-fr.ind multicol-fr.idx
pdflatex multicol-fr.dtx
pdflatex multicol-fr.dtx
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
Pages d'avant-propos          | :new_moon:             | 0 / 2           | 
1. Introduction               | :new_moon:             | 0 / 0           | 
2. Interface utilisateur      | :new_moon:             | 0 / 3           | 
3. Préfaces des anciennes...  | :new_moon:             | 0 / 2           | 
4. Implémentation             | :new_moon:             | 0 / 18          | 
5. Nouvelles commandes et...  | :new_moon:             | 0 / 3           | 
6. Réglage de \columnwidth    | :new_moon:             | 0 / 0           | 
7. Compléments à l'extension  | :new_moon:             | 0 / 4           | 
Index                         | :new_moon:             | 0 / 1           | 
Historique                    | :new_moon:             | 0 / 3           | 



### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
