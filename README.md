# plan-de-formation-reactjs

Plan de formation ReactJS

---

## Pré-requis :

- javascript / D.O.M
- git / github
- node / npm
- es6
- html / css / pré-processeurs css / framework css
- anglais

---

## Jour 1

### Le fonctionnement des navigateurs :
- markup / dom / rendering / paint / layout
- javascript engines (https://en.wikipedia.org/wiki/List_of_ECMAScript_engines)
- javascript versions (es5, es6, ...)

### Les navigateurs et les servers :
- server / browser / domains (cors)
- templating (browser responsability / server responsability)
- API vs Server rendering

### Les web applications :
- single page application 
- MVC, MVVM...

### Development workflow :
- Best practices / conventions
- reserved words (javascript / es2015)
- debugging / logging / chrome dev tools
- linter
- bundler / task runner

### React development stack
- webpack / webpack-dev-server
- babel
- react
- redux
- react-redux

### Les frameworks & libraires JS sur le marché actuellement :
- ReactJS
- AngularJS
- VueJS

### React community :
- facebook, rbnb, ...
- Dan Abramov
- https://react.rocks/
- https://github.com/enaqx/awesome-react
- https://github.com/brillout/awesome-react-components
- https://github.com/xgrommx/awesome-redux

### Let's step into :
- npm install create-react-app -g
- Your first web app / Your first component

## Jour 2

- Webpack what ?
  - require data json
  - require css
  - require image
  ...
  - comprendre webpack en dev / comprendre le build de production

- React, the component way
  - JSX
  - map / key
  - ref
  - props
  - state
  
- exercice : une liste de produit

## Jour 3

- React : state shared between components

- exercice : une liste de produit, un filtre par type, et un panier

## Jour 5

- redux : Les trois principes (single source of truth, state is read-only, pure functions)

- redux : store, actions, reducers

- combine reducers (High order function)

- react-redux : container (High order component) 

- exercice : (reprise de l'exercice précédent) Utilisation de redux à la place des states

## Jour 4

- React router V4 / React helmet / react-router-redux V4

- exercice : (reprise de l'exercice précédent) Ajout page detail produit + page recap panier

- evaluation : projet events / avec pagination / related events (à confirmer selon niveau général)

## Jour 6

- react form (controlled vs uncontrolled)

- validation de formulaire

- exercice : ajout/suppression/modification de produit

## Jour 7

- redux : thunk middleware to fetch remote data

- le contrat de données (json file)

- exercice : (reprise de l'exercice précédent) avec remote datas

## Jour 8

- rxjs : redux observable

- Material UI

- autres libs et components

- Restitutions des projets evaluation.

