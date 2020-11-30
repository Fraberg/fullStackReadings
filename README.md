# nice_readings

## javascript
<details><summary>(click to toggle)</summary>

- in overall
  - lit javascript https://developer.mozilla.org/fr/docs/Web/JavaScript/Une_r%C3%A9introduction_%C3%A0_JavaScript
  
- on functions
  - in overall https://developer.mozilla.org/fr/docs/Web/JavaScript/Une_r%C3%A9introduction_%C3%A0_JavaScript#Les_fonctions
  - Immediately Invoked Function Expression https://developer.mozilla.org/fr/docs/Glossaire/IIFE
  
</details>


## react
<details><summary>(click to toggle)</summary>

- in overall
  - getting started https://fr.reactjs.org/docs/getting-started.html
  - courses https://fr.reactjs.org/community/courses.html
  
 - on components
  - state and props
    - ***"The main responsibility of a Component is to translate raw data into rich HTML. With that in mind, the props and the state together constitute the raw data that the HTML output derives from."***
    - commonalities: objects, render update, deterministic
    - [see differences](https://fr.reactjs.org/docs/faq-state.html#what-is-the-difference-between-state-and-props)
    - state: initial value defined inside the comp. Optional, preferable without (+complexity and -predictability). Modified with setState()
    - props - properties: value received from parent component, immutable for "pure" component. Like function argument
    - async updates imply https://fr.reactjs.org/docs/state-and-lifecycle.html#state-updates-may-be-asynchronous
  - lifecycle methods https://fr.reactjs.org/docs/state-and-lifecycle.html#adding-lifecycle-methods-to-a-class
    - 1) componentDidMount() "exécutée après que la sortie du composant a été injectée dans le DOM."
    - 2) componentWillUnmount() destruct the component
  - pass args to onEvent() attr https://fr.reactjs.org/docs/handling-events.html#passing-arguments-to-event-handlers
  
- web page design with components tree
  - components tree design and hierarchy https://fr.reactjs.org/docs/thinking-in-react.html

- on conventions
  - DOM tag if downcase \<div \/> but \<Component \/> if uppercase
  - Tout composant React doit agir comme une fonction pure vis-à-vis de ses props.

- cheap metaphore
  - "Si vous imaginez un arbre de composants comme une cascade de props, chaque état de composant est une source d’eau supplémentaire qui rejoint la cascade à un point quelconque, mais qui coule également vers le bas." https://fr.reactjs.org/docs/state-and-lifecycle.html#the-data-flows-down
  
</details>
