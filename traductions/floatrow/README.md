## Traduction de l'extension *floatrow*

L'objectif est de traduire la documentation de l'extension *floatrow* utilisable avec LaTeX. 

Pour traiter un problème de compilation, la ligne 50 du fichier `TheCat.picture` a été commentée.

### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex floatrow-fr.dtx
pdflatex floatrow-fr.dtx
makeindex -s gglo-fr.ist -o floatrow-fr.gls floatrow-fr.glo
pdflatex floatrow-fr.dtx
pdflatex floatrow-fr.dtx
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
Pages d'avant-propos          | :new_moon:             | 0 / 8           | 
1. Introduction               | :new_moon:             | 0 / 6           | 
2. Commandes pour...          | :new_moon:             | 0 / 13          | 
3. Paramétrage de la mise...  | :new_moon:             | 0 / 34          | 
4. Création de nouveaux...    | :new_moon:             | 0 / 1           | 
5. Code emprunté              | :new_moon:             | 0 / 4           | 
6. L'extension floatrow...    | :new_moon:             | 0 / 7           | 
7. Duos d'extension           | :new_moon:             | 0 / 15          | 
8. Les incompatibilités       | :new_moon:             | 0 / 0           | 
9. Limites                    | :new_moon:             | 0 / 1           | 
10. Remerciements             | :new_moon:             | 0 / 2           | 
11. Annexes                   | :new_moon:             | 0 / 15          | 


### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
