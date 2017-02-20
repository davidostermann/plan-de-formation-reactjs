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

### Les frameworks & libraires JS sur le marché actuellement :
- ReactJS, AngularJS, VueJS
- virtual dom VS dirty checking
- strict unidirectional data flow (one way binding) VS two way binding

### Development workflow :
- editor : (atom / sublimetext, webstorm) : jsx emmet, babel language syntax colorization, ternjs
- Best practices / conventions / linter (eslint) / editorconfig
- debugging / logging / chrome dev tools + react dev tools + redux dev tools

### React development stack
- webpack / webpack-dev-server : Mega-power bundler
- babel : es2015 / 2017 (future of web browser)
- react : the view part (virtualdom  / one way binding)
- redux / react-redux : the model part (functional reactive programming)

### React community :
- facebook, rbnb, ...
- Dan Abramov (@gaeron)
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
  ... (et bien plus : cf. webpack loader + webpack plugin)
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

- exercice : (reprise de l'exercice précédent) une liste de produit, un filtre par type, et un panier

- redux : Les trois principes (single source of truth, state is read-only, pure functions)

- redux : store, actions, reducers

- Dumb Components

- exercice : (reprise de l'exercice précédent) refacto des states en redux store

## Jour 5

- react-redux : container (High order component) / connect

- combine reducers (High order function)

- 

- exercice : (reprise de l'exercice précédent) Utilisation de redux à la place des states

## Jour 4

- React router V4 / React helmet / react-router-redux V4

- exercice : (reprise de l'exercice précédent) Ajout page detail produit + page recap panier

- evaluation : projet events / avec pagination / related events (à confirmer selon niveau général)

## Jour 6

- redux : thunk middleware to fetch remote data

- le contrat de données (json file)

- exercice : (reprise de l'exercice précédent) avec remote datas (cf. nodejs cours)

## Jour 7

- react form (controlled vs uncontrolled)

- validation de formulaire

- exercice : ajout/suppression/modification de produit (cf. nodejs cours)

## Jour 8

- reselect / memoize

- Material UI

- rxjs : redux observable

- Restitutions des projets evaluation (cf. nodejs cours : le projet sera en cours)

