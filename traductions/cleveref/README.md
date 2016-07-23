## Traduction de l'extension *cleveref*

L'objectif est de traduire la documentation de l'extension *cleveref* utilisable avec LaTeX.

### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées (elles évitent d'imprimer la partie Implémentation présentant le code) :

```bash
xelatex "\AtBeginDocument{\OnlyDescription} \input cleveref-fr.dtx"
xelatex "\AtBeginDocument{\OnlyDescription} \input cleveref-fr.dtx"
makeindex -s gind-fr.ist -o cleveref-fr.ind cleveref-fr.idx
makeindex -s gglo-fr.ist -o cleveref-fr.gls cleveref-fr.glo
xelatex "\AtBeginDocument{\OnlyDescription} \input cleveref-fr.dtx"
xelatex "\AtBeginDocument{\OnlyDescription} \input cleveref-fr.dtx"
```

Sur ce point, un fichier Makefile est mis à disposition (voir par exemple [OpenClassrooms](https://openclassrooms.com/courses/compilez-sous-gnu-linux#/id/r-1130480) pour plus d'informations)


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
1. Introduction               | :new_moon:             | 0 / 1           |
2. Utilisation                | :new_moon:             | 0 / 1           | 
3. Comparaison avec ...       | :new_moon:             | 0 / 1           |   
4. Composition de ...         | :new_moon:             | 0 / 2           |  
5. Tri et compression         | :new_moon:             | 0 / 1           |  
6. Contournement des ...      | :new_moon:             | 0 / 1           |
7. Options modifiant ...      | :new_moon:             | 0 / 1           |  
8. Personnalisation des ...   | :new_moon:             | 0 / 8           |  
9. Mise en forme avancées ... | :new_moon:             | 0 / 1           |  
10. Langues et support de ... | :new_moon:             | 0 / 2           |  
11. Le fichier cleveref.cfg   | :new_moon:             | 0 / 0           |
12. Cleveref pour les démunis | :new_moon:             | 0 / 1           |
13. Interaction avec les ...  | :new_moon:             | 0 / 1           |
14. Erreurs connues...        | :new_moon:             | 0 / 3           |
15. Remerciements             | :new_moon:             | 0 / 1           |
Historique                    | :new_moon:             | 0 / 4           |

### Glossaire pour la traduction

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------

