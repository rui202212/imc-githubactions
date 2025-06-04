## Pour la 1e fois

```sh
npm init
npm install express jest supertest nodemon
```

## Pour lancer localement

```sh
npm install
node src/server.js
```

## Requête URL

Quand le serveur est démarré, utiliser un url comme suit:
`http://localhost:3000/imc?weight=40&height=1.65`

## Pour lancer les tests

```sh
jest
```

## Pour construire l'image Docker et lancer le container

Sous Windows, il faut laisser tourner Docker Desktop.

```sh
docker build -t imc-calculator .
docker run -p 3000:3000 imc-calculator
```

## Pour tester le déploiement

`http://openlabtech.com:3031/imc?weight=80&height=1.70`
