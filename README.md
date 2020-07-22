# ReactJS-assessment
React.JS Assessment from Linkedin

#### 1. When using webpack, why would you need to use a loader ?
- to put together physical file folders
- to load external data &#10004;
- to load the website into everyone's phone
- to process files

#### 2. How do you fix the syntax error that results from running this code ?
```js
const person = (firstName, lastName) => 
        {
            first: firstName,
            last: lastName
        }
console.log(person("Jill", "Wilson"));
```
- Wrap the object in parentheses. &#10004;
- Call the function from another file.
- Replace the object with an array.
- Add a return statement before the first curly brace.

#### 2. Which of these terms commonly describes React applications ?
- declarative &#10004;
- integrated
- closed
- imperative

#### 4. Which attribute do you use to replace innerHTML in the browser DOM ?
- injectHTML
- dangerouslySetInnerHTML &#10004;
- weirdSetInnerHTML
- strangeHTML

#### 5. What can you use to handle code splitting ?
- React.split
- React.memo
- React.fallback
- React.lazy &#10004;

#### 6. To create a constant in Javascript, which keyword do you use ?
- const &#10004;
- var
- constant
- var

#### 7. How do you destructure the properties that are sent to the Dish component ?
```js
-    function Dish(props) {
        return <h1>{props.name} {props.cookingTime}</h1>
    }

-    function Dish({name, cookingTime}) { 
        return <h1>{name} {cookingTime}</h1>
    } // <<< CORRECT

-    function Dish(...props) {
        return <h1>{props.name} {props.cookingTime}</h1>
    }

-    function Dish([name, cookingTime]) {
        return <h1>{name} {cookingTime}</h1>
    }

-    function Dish(props) {
        return <h1>{name} {cookingTime}</h1>
    }
```

#### 8. What do you call a React component that catches Javascript errors anywhere in the child component tree ?
- error bases
- error catches
- error helpers
- error boundaries  &#10004;

#### 9. In which lifecycle method do you make requests for data in a class component ?
- constructor
- componentDidMount  &#10004;
- componentWillReceiveProps
- componentWillMount

#### 10. React components are composed to create a user interface. How are components composed ?
- by putting them in the same file
- by nesting components &#10004;
- with webpack
- with code splitting

#### 11. All React components must act like ____ with respect to their props.
- monads
- pure functions
- recursive functions
- higher-order functions &#10004;

#### 12. If you created a component called Dish and rendered it to the DOM, what type of element would be rendered ?
```js
function Dish() {
    return <h1>Mac and Cheese</h1>
}

ReactDOM.render(
    <Dish />,
    document.getElementById('root')
);
```
- h1 &#10004;
- section
- component
- div

#### 13. What should the console read when the following code is run ?
```js
const [, , animal] = ["Horse", "Mouse", "Cat"];
console.log(animal);
```
- Mouse
- undefined
- Cat &#10004;
- Horse

#### 14. Why might you use a ref ?
- to directly access to DOM node &#10004;
- to refer to another JS file
- to call a function
- to bind the function

#### 15. Why might you use useReducer over useState in a React component.
- when you need to manage more complex state in an app &#10004;
- when you want to replace Redux
- when you want to improve performance
- when you want to break your production app

#### 16. If you want to import just the Component from the React library, what syntax do you use?
- import React.Component from 'react'
- import [ Component ] from 'react'
- import Component from 'react'
- import { Component } from 'react' &#10004;

#### 17. If a function component should always render the same way given the same props, what is a simple performance optimization available for it?
- Wrap it in the React.memo higher-order component. &#10004;
- Implement the useReducer Hook.
- Implement the useMemo Hook.
- Implement the shouldComponentUpdate lifecycle method.

#### 18. If you see the following import in a file, what is being used for state management in the component?
```js
import React, {useState} from 'react';
```
- React Hooks &#10004;
- stateful components
- math
- class components

#### 19. Using object literal enhancement, you can put values back into and object. When you log person to the console, what is the output?
```js
const name = "Rachel";
const age = 31;
const person = { name, age }
console.log(person)
```
- {{name: "Rachel", age: 31}}
- {name: "Rachel", age: 31} <<<<<--CORRECT
- {person: "Rachel", person: 31}}
- {person: {name: "Rachel", age: 31}}
