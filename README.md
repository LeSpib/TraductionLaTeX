## Traduction d'extensions courantes de LaTeX

L'objectif de ce projet est de traduire en français la documentation de différentes extensions de LaTeX.

*The goal of this project is to translate in french some LaTeX packages documentations.* 

### Aspects juridiques

Nous reprenons ici le principe retenu par un projet de traduction datant de 2000 : [French translations](https://www.ctan.org/pkg/french-translations).

Toutes ces traductions sont régies par la License Publique du Projet LaTeX (LPPL). Elles sont donc librement distribuables, du moment que le code des extensions inclus dans les documentations l'est (il n'est pas de notre ressort). Si vous êtes autorisés à utiliser une extension d'une certaine façon, alors vous êtes autorisé à faire la même chose avec la version française de sa documentation. Les seules restrictions
(imposées par la LPPL) sont sur la traduction elle-même.

En quelques mots: ne modifiez pas un document si vous trouvez une faute, indiquez-la plutôt à la bonne personne (l'auteur de l'extension, le traducteur, l'équipe de traduction, etc).

*All those translations are under the LaTeX Project Public License. Thus they are freely distributable, as long as the code of the packages that is in the document (which does not belong to us) is itself freely distributable. If you're allowed to use a package in a given way, then you are allowed to use the french translation of its documentation in exactly the sane way. The only restrictions (imposed by the LPPL) are on the translation itself.*

*In short words: do not modify a document if you find a mistake, just contact the right person (the author of the package, the person who translated it, the translation team, etc).*

### Liste des extensions traduites 

Ces extensions sont considérées comme traduites. Elles peuvent encore contenir des coquilles. Les retours sur ces traductions sont les bienvenus !

- [ ] *geometry* ;
- [ ] *titlesec*.

### Liste des extensions en cours de traitement
- [ ] *fontspec* ;
- [ ] *xcolor*.

### Liste des extensions envisagées par la suite
- [ ] *adjustbox* ;
- [ ] *booktabs* ;
- [ ] *cleveref* ;
- [ ] *datatool* (énorme) ;
- [ ] *datetime2* (gros) ;
- [ ] *etoc* ;
- [ ] *glossaries* (énorme) ;
- [ ] *hyperref* ;
- [ ] *pgfplots* (énorme) ;
- [ ] *siunitx* (gros) ;
- [ ] *tikz* (gigantesque) ;
- [ ] *varioref*.

### Formalisation de l'avancée de la traduction

Le résultat courant de chaque traduction est fourni en PDF avec des passages mis en orange pour indiquer les passages ou éléments restant à traduire. Ces marques sont parfois un peu approximatives pour certains éléments ajoutés au texte comme les tables et index.

Ces marques sont gérées par quelques commandes placées en préambule de document : `\trad{}`, `\tradini` et `\tradfin`. Les commandes et leur définition seront retirées une fois la traduction achevée.

### Terminologie

De nombreux termes se retrouvent dans les différentes documents traduits. Cette section sert de pense-bête sur ce sujet en regroupant certains de ces termes. Chaque traduction d'extension reprend dans son ReadMe dédié ce principe, de façon plus ciblée.

- *control sequence* : commande ;
- *cropmarks* : traits de coupe (source Wiktionnaire) ;
- *driver* : pilote (informatique, graphique...) ;
- *error report* : rapports d'erreur ;
- *filler* : motif (de remplissage) ;
- *header* : en-tête ;
- *leaders* : points de conduite ;
- *leading* : interlignage ;
- *package* : extension.
