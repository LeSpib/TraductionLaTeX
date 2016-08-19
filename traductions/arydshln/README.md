## Traduction de l'extension *arydshln*

L'objectif est de traduire la documentation de l'extension *arydshln* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex arydshln-fr.dtx
pdflatex arydshln-fr.dtx
makeindex -s gglo-fr.ist -o arydshln-fr.gls arydshln-fr.glo
makeindex -s gind-fr.ist -o arydshln-fr.ind arydshln-fr.idx
pdflatex arydshln-fr.dtx
pdflatex arydshln-fr.dtx
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
Entête du document tex        | :new_moon:             |                 |
Pages d'avant-propos          | :new_moon:             | 0 / 2           | 
1. Introduction               | :new_moon:             | 0 / 1           |
2. Utilisation                | :new_moon:             | 0 / 5           |
3. Problèmes connus           | :new_moon:             | 0 / 1           |
4. Implémentation             | :new_moon:             | 0 / 58          |
Remerciements                 | :new_moon:             | 0 / 1           |
Index                         | :new_moon:             | 0 / 5           |
Historique                    | :new_moon:             | 0 / 7           |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
