## Traduction de l'extension *xkeyval*

L'objectif de ce dépôt GIT est de traduire la documentation de l'extension *xkeyval* utilisable avec LaTeX.

### Commandes pour obtenir le document

```bash
pdflatex xkeyval-fr.dtx
pdflatex xkeyval-fr.dtx
bibtex xkeyval-fr.aux
makeindex -s gglo-fr.ist -o xkeyval-fr.gls xkeyval-fr.glo
makeindex -s gind-fr.ist -o xkeyval-fr.ind xkeyval-fr.idx
pdflatex xkeyval-fr.dtx
pdflatex xkeyval-fr.dtx
```

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
Page d'avant-propos           | :first_quarter_moon:   | 1               | 
1. Introduction               | :new_moon:             | 0 / 1           |
2. Chargement de xkeyval      | :new_moon:             | 0 / 1           | 
3. Définir et gérer les clés  | :new_moon:             | 0 / 5           |
4. Paramétrer les clés        | :new_moon:             | 0 / 2           |
5. Pointeurs                  | :new_moon:             | 0 / 4           |
6. Préparamétrer les clés     | :new_moon:             | 0 / 2           |
7. Traitement des options...  | :new_moon:             | 0 / 2           |
8. Liste des structures...    | :new_moon:             | 0 / 2           |
9. Alertes et erreurs         | :new_moon:             | 0 / 1           |
10. Codes de catégorie        | :new_moon:             | 0 / 1           |
11. Problèmes connus          | :new_moon:             | 0 / 1           |
12. Extensions additionnelles | :new_moon:             | 0 / 3           |
13. Exemples et documentation | :new_moon:             | 0 / 1           |
14. Implémentation            | :new_moon:             | 0 / 40          |
Références                    | :new_moon:             | 0 / 1           | 
Remerciements                 | :new_moon:             | 0 / 1           | 
Historique des versions       | :new_moon:             | 0 / 1           |
Index                         | :new_moon:             | 0 / 3           |

### Glossaire pour la traduction

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------
