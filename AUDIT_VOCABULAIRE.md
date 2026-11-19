# Español — correction globale de l’alignement du vocabulaire

Cette version reprend le projet PWA V3 et ajoute un correctif CSS global ciblant toutes les occurrences des classes `.es` et `.es-translation`, y compris les listes, paragraphes, tableaux et cartes de vocabulaire. Les paires dans les cartes `.vocab-pairs` sont explicitement disposées sur une même rangée et peuvent revenir à la ligne si l’écran est étroit.

## Contrôles statiques réalisés

- Fichier HTML analysé : `index.html`.
- Occurrences `.es` : 1241.
- Occurrences `.es-translation` : 1122.
- Listes contenant au moins une traduction : 222.
- Paragraphes contenant au moins une traduction : 101.
- Cellules de tableau contenant au moins une traduction : 32.
- Conteneurs `.vocab-pairs` : 23.

## Limite importante

Ce contrôle est statique : il vérifie la présence des éléments et applique des règles communes. Il ne remplace pas un test visuel sur plusieurs navigateurs et tailles d’écran Android. Les textes de lecture et explications ne sont pas restructurés ; seules les règles d’affichage des paires bilingues sont harmonisées.
