## Traduction de l'extension *varioref*

L'objectif de ce dépôt GIT est de traduire la documentation de l'extension *varioref* utilisable avec LaTeX.

Cette traduction a la particularité d'avoir déjà été traitée partiellement sur la version v1.2c de l'extension par Jean-Pierre Drucbert (ci-dessous le fichier *f-varioref*), en lien avec le projet [French translations](https://www.ctan.org/pkg/french-translations). Les fichiers d'origine de la traduction se retrouvent sur le site du [CTAN](https://www.ctan.org/tex-archive/macros/latex/required/tools).

Benjamin Bayart ayant donné son accord, il s'agit ici donc de revoir cette traduction et de la compléter des évolutions apportées à l'extension entre la version v1.2c (datant de 1999) et la version v1.5c (datant de 2016).

### Commandes pour obtenir le document

```bash
pdflatex varioref-fr.dtx
pdflatex varioref-fr.dtx
makeindex -s gglo-fr.ist -o varioref-fr.gls varioref-fr.glo
pdflatex varioref-fr.dtx
pdflatex varioref-fr.dtx
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
Page d'avant-propos           | :new_moon:             | 0 / 1           | 
1. Introduction               | :new_moon:             | 0 / 0           |
2. L'interface utilisateur    | :new_moon:             | 0 / 3           | 
3. Multilinguisme             | :new_moon:             | 0 / 1           |
4. Personnalisation           | :new_moon:             | 0 / 1           |
5. Options                    | :new_moon:             | 0 / 0           |
6. Quelques avertissements    | :new_moon:             | 0 / 1           |
7. Fichier de génération...   | :new_moon:             | 0 / 0           |
8. L'implémentation           | :new_moon:             | 0 / 24          |
Historique                    | :new_moon:             | 0 / 4           |

### Glossaire pour la traduction

Anglais                   | Français                                          | Commentaires 
------------------------- | ------------------------------------------------- | -------------------------------
