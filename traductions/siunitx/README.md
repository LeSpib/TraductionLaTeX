## Traduction de l'extension *siunitx*

L'objectif est de traduire la documentation de l'extension *siunitx* utilisable avec LaTeX. 


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex siunitx-fr.dtx
pdflatex siunitx-fr.dtx
makeindex -s gglo-fr.ist -o siunitx-fr.gls siunitx-fr.glo
makeindex -s gind-fr.ist -o siunitx-fr.ind siunitx-fr.idx
pdflatex siunitx-fr.dtx
pdflatex siunitx-fr.dtx
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
2. Installation               | :new_moon:             | 0 / 1           |
3. sinuitx pour l'impatient   | :new_moon:             | 0 / 2           | 
4. Utilisation de...          | :new_moon:             | 0 / 10          | 
5. Détail exhaustif des...    | :new_moon:             | 0 / 45          |
6. Localisation               | :new_moon:             | 0 / 1           |
7. Astuces pour utiliser...   | :new_moon:             | 0 / 9           | 
8. Information pour ceux...   | :new_moon:             | 0 / 6           |
9. Application correcte de... | :new_moon:             | 0 / 5           |
10. Faire des suggestions...  | :new_moon:             | 0 / 1           | 
11. Remerciements             | :new_moon:             | 0 / 0           |
Références                    | :new_moon:             | 0 / 0           |
Historique                    | :new_moon:             | 0 / 7           |
Index                         | :new_moon:             | 0 / 9           |


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
