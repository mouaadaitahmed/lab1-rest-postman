# Lab 1 - API REST avec Postman

Tests de l'API [DummyJSON](https://dummyjson.com) avec Postman : GET, POST, PUT, PATCH, DELETE, variables d'environnement et scripts de test.

## Contenu

- `postman/` : collection et environnement exportés
- `rapport/rapport-lab1.pdf` : rapport du TP
- `screenshots/` : captures Postman

## Utilisation

1. Ouvrir Postman et cliquer sur **Import** (en haut à gauche).
2. Glisser les 2 fichiers du dossier `postman/` :
   - `LAB1 - Gestion Produits REST.postman_collection.json`
   - `Demo API Env.postman_environment.json`
3. En haut à droite, choisir l'environnement `Demo API Env` ,sinon `{{baseUrl}}` reste vide et les requêtes échouent.
4. Ouvrir une requête dans la collection et cliquer sur **Send**.
5. Pour tout lancer d'un coup : clic droit sur la collection,puis **Run**, puis **Run LAB1 - Gestion Produits REST**. Les résultats des tests s'affichent à la fin.
