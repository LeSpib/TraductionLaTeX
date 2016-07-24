## Traduction de l'extension *fncychap*

L'objectif est de traduire la documentation de l'extension *fncychap* utilisable avec LaTeX. 

Le document demande ici quelques modifications : l'extension *ydrop* n'existe plus (du moins, une [version](http://www.math.vanderbilt.edu/~schectex/wincd_files/tex/docs/Tricks%20for%20TeX%20and%20LaTeX.htm) existe et n'aboutit pas au résultat souhaité). Elle est ici remplacée par *lettrine* et les commandes associées tout au long du document sont adaptées en conséquence.

Par ailleurs, le document a fait l'objet de l'**ajout d'une annexe** pour traiter d'un point permettant de mieux gérer le cas de documents francophones.


### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées :

```bash
pdflatex fncychap-fr.tex
pdflatex fncychap-fr.tex
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
Pages d'avant-propos          | :first_quarter_moon:   | 2               | 
1. Description de l'extension | :first_quarter_moon:   | 1               |
2. Nouvelles commandes        | :first_quarter_moon:   | 1               |
3. Aperçu des styles de...    | :first_quarter_moon:   | 4               |
4. Exemple simple             | :first_quarter_moon:   | 2               |
5. Historique                 | :first_quarter_moon:   | 1               |

### Glossaire pour la traduction

Anglais                | Français                                       | Commentaires 
---------------------- | ---------------------------------------------- | -------------------------------
