
# Feedback pour l'Apprenant 2

## Fichier `index.js`
- Vous n'avez pas paramétre de variable "PORT" dans votre code. Referrez-vous à la correction pour mieux comprendre.
- La correction utilise `process.env.SESSION_SECRET` pour le secret de session, offrant une meilleure sécurité.

## Fichier `dataMapper.js`
- Le module `database.js` est importé inutilement deux fois.
- L'utilisation de chaînes de caractères simples pour les requêtes SQL est dangereux. La correction montre la meilleure façon avec l'utilisation de l'objet.Cela apporte une protection contre les injections SQL.

## Dossier `controllers`
- Dans `searchController.js`, la correction semble récupérer les cartes correspondant à l'élément recherché directement à partir de la base de données, ce qui est plus efficace.

## Conclusion
Vous avez une bonne compréhension de la structure et des concepts, mais pourrait bénéficier d'améliorations en matière de sécurité et d'efficacité, en particulier dans la gestion des requêtes SQL. De plus, l'élimination du code redondant et des importations inutiles pourrait rendre le code plus propre et plus lisible.
