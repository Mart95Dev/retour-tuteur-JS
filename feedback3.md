
# Feedback pour l'Apprenant 3

## Fichier `index.js`
- La correction utilise une variable dédiée `PORT` pour le port d'écoute. Cette varaible est absente de votre code.
- La correction utilise `process.env.SESSION_SECRET` pour le secret de session, offrant ainsi une meilleure sécurité.

## Fichier `dataMapper.js`
- L'utilisation de chaînes de caractères simples pour les requêtes SQL est dangereux. La correction montre la meilleure façon avec l'utilisation de l'objet.Cela apporte une protection contre les injections SQL.

## Conclusion
Vous avez une bonne compréhension de la structure et des concepts, mais pourrait bénéficier d'améliorations en matière de sécurité et d'efficacité, en particulier dans la gestion des requêtes SQL. De plus, l'adoption d'une meilleure mise en forme et d'une syntaxe cohérente pourrait aider à améliorer la lisibilité et la maintenance du code.
