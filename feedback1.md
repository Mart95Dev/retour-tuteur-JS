
# Feedback pour l'Apprenant 1

## Fichier `index.js`

- **Initialisation dotenv** : Placez `dotenv.config();` avant d'importer d'autres modules qui pourraient en dépendre.
- **Chemin pour les vues et ressources statiques** : Soyez cohérent dans la manière dont vous définissez les chemins. Les deux approches (`'./app/views'` vs `'app/views'`) fonctionnent, mais la cohérence est primordiale.
- **Configuration de session** : Revoyez les paramètres de session et assurez-vous de les comprendre : `resave: false` vs `resave: true`.

## Dossier `app`

### Fichier `dataMapper.js`

- **Définition de fonction** : Soyez cohérent dans la manière dont vous définissez les fonctions. Les deux syntaxes (arrow vs traditionnelle) sont acceptables, mais il est bon d'être regulier dans sa synthaxe à travers le projet.
- **Structure des requêtes SQL** : L' utilisation d'objets avec des propriétés `text` et `values` pour vos requêtes sont sécuritaires, comme dans la correction.

### Fichier `database.js`

- **Espacement** : Assurez-vous d'être cohérent dans la mise en forme, comme l'espacement autour des accolades.

### Fichier `mainController.js`

- **Gestion des erreurs** : Donnez des informations utiles lors de la gestion des erreurs. Par exemple, fournir des détails sur l'erreur de la base de données peut être utile pour le débogage.

### Fichier `searchController.js`

- **Recherche par élément** : Finalisez votre fonction `searchByElement`. Il semble que vous ayez commenté une grande partie du code. Est ce un oubli ? Utilisez la correction comme guide pour compléter cette fonction.

---

N'oubliez pas que le feedback est là pour vous aider à identifier les zones d'amélioration. Continuez à pratiquer et à poser des questions pour clarifier vos doutes. Bon travail !
