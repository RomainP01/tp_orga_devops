# TP ORGA SCRUM MASTER

## SPÉCIFICATIONS DU FRONT

### Utilisation de Storybook
A chaque nouveau composant, il faut lui associer une story grâce à storybook : https://storybook.js.org/
Utiliser le pattern Container/Presentational Component : https://medium.com/@sidibemouhamed/le-pattern-container-presentation-component-avec-react-ff7b6aa1c10d

### Les tests avec Cypress
Pour les tests d'acceptance, ils doivent être réalisé à l'aide de Cypress : https://storybook.js.org/

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

Le front de l'application sera disponible à l'adresse : http://localhost:3000

#### Démarrer storybook
```
yarn storybook
```
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



