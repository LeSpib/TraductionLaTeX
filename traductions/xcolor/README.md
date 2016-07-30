## Traduction de l'extension *xcolor*

L'objectif de ce dépôt GIT est de traduire la documentation de l'extension *xcolor* utilisable avec LaTeX.

### Commandes pour obtenir le document

Les commandes suivantes doivent être exécutées.

```bash
pdflatex xcolor-fr.dtx
pdflatex xcolor-fr.dtx
makeindex -s gind-fr.ist xcolor-fr.idx
pdflatex xcolor-fr.dtx
pdflatex xcolor-fr.dtx
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
En-tête du document tex       | :waxing_crescent_moon: |                 |
Pages d'avant-propos          | :waxing_crescent_moon: | 3 / 4           | 
1. Introduction               | :waxing_gibbous_moon:  | 4               |
2. L'interface utilisateur    | :first_quarter_moon:   | 28              | 
3. Exemples                   | :first_quarter_moon:   | 7               | 
4. Couleurs nommées           | :first_quarter_moon:   | 3               | 
5. Compléments techniques     | :first_quarter_moon:   | 3               | 
6. Les formules               | :new_moon:             | 5 / 13          | Section 6.3 en cours
Références                    | :first_quarter_moon:   | 1               | 
Annexes                       | :new_moon:             | 2 / 6           |
Index                         | :new_moon:             | 0 / 4           |

### Quelques termes récurrents dans la traduction de ce document

La terminologie des couleurs est, comme le dit d'ailleurs l'auteur dans le document, assez peu précise et les différents termes en viennent à même se recouper. Un effort a été fait afin de conserver uniquement les termes les moins biaisés possibles, quitte à utiliser des expressions parfois un peu plus rares. Les termes ci-dessous donnent la traduction usuelle qui n'est pas forcément celle suivie dans le document à certains endroits (typiquement en section 1.2 du document).

Les terminologies plus rares mais plus explicites ont été tirées du site [Sit & Kiss Leaf](http://sitekissleaf.blogspot.fr/2012/05/utiliser-les-couleurs.html).

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------
*brightness*              | luminosité                                        |   
*color harmony*           | accord de couleurs                                | 
*color masking*           | masque de couleur                                 |
*color model*             | modèle colorimétrique                             | 
*color wheel*             | cercle chromatique                                | 
*complement*              | complémentaire, couleur complémentaire            | 
*hue*                     | teinte                                            | 
*name clash*              | conflit de nom                                    | 
*shade*                   | nuance (usuel), couleur assombrie (ici)           |
*spot color*              | ton direct                                        | Source : Wikipédia
*tetrad*                  | tétrade                                           | 
*tint*                    | teinte (usuel), couleur éclaircie (ici)           | 
*tone*                    | ton (usuel), couleur assourdie (ici)              |
*triad*                   | triade                                            | 
