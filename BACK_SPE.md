# TP ORGA SCRUM MASTER

## SPÉCIFICATIONS DU FRONT

### Documentation de l'api
- Le swagger de l'api doit être couramment mis à jour. Le lien du swagger : https://github.com/RomainP01/tp_orga_devops/edit/main/BACK_SPE.md

### Les tests 
Tout les test doivent être référencés dans le dossier /tests/.

Les librairies de tests sont les suivantes :
- [sinon](https://www.npmjs.com/package/sinon)
- [chai](https://www.npmjs.com/package/chai)
- [sinon-test](https://www.npmjs.com/package/sinon-test)
- [mongodb-memory-server](https://www.npmjs.com/package/mongodb-memory-server)

Les test seront lancés automatiquement après le déploiement de l'application dans la CI pour vérifier le bon fonctionnement du code.

## RUN THE PROJECT
---
### Installation

### Utilisez Yarn
- WINDOWS : https://classic.yarnpkg.com/fr/docs/install/#windows-stable
- MACOS : https://classic.yarnpkg.com/fr/docs/install/#mac-stable

#### Première étape, clonez le projet
```
git clone https://github.com/RomainP01/tp_orga_devops.git
```

#### Lancer l'installation des librairies
```
yarn install
```

#### Démarrer le projet
```
yarn start
```

Le front de l'application sera disponible à l'adresse : http://localhost:3001

---

### Qualité de code

- Pour vérifier que la qualité de code est correct pour typescript et le css.
```
npm run lint
```

- Pour vérifier que la qualité de code est correct pour typescript.
```
npm run lint:js
```

- Pour vérifier que la qualité de code est correct pour le css.
```
npm run lint:css
```

- Lancer les tests.
```
npm test
```



