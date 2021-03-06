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
- {name: "Rachel", age: 31} &#10004;
- {person: "Rachel", person: 31}}
- {person: {name: "Rachel", age: 31}}

#### 20. What is the testing library most often associated with React?
- Mocha
- Chai
- Sinon
- Jest &#10004;

#### 21. To get the first item from the array ("cooking") using array destructuring, how do you adjust this line?
```js
const topics = ["cooking", "art", "history"]
```
- const first = ["cooking", "art", "history"]
- const [] = ["cooking", "art", "history"]
- const [, first]["cooking", "art", "history"]
- const [first] = ["cooking", "art", "history"] &#10004;

#### 22. How do you handle passing through the component tree without having to pass props down manually at every level?
- React Send
- React Pinpoint
- React Router
- React Context &#10004;

#### 23. What is the name of the tool used to take JSX and turn it into createElement calls?
- JSX Editor
- ReactDOM
- Browser Buddy
- Babel &#10004;

#### 24. Which props from the props object is available to the component with the following syntax?
```js
<Message {...props}/>
```
- any that have not changed
- all of them &#10004;
- child props
- any that have changed

#### 25. Consider the following code from React Router. What do you call :id in the path prop?
```js
<Route path="/:id" />
```
- This is a route modal
- This is a route parameter &#10004;
- This is a route splitter
- This is a route link

#### 26. What does this React element look like given the following function?
```js
React.createElement( 
    "h1",
    null,
    "What's happening?"
);
```
- ``` <h1 props={null}>What's happenning?</h1>```
- ``` <h1 id="component">What's happening?</h1>```
- ``` <h1>What's happening?</h1>``` &#10004;
- ``` <h1 id="element">What's happening?</h1>```

#### 27. What property do you need to add to the Suspense component in order to display a spinner or loading state?
```js
function MyComponent() {
    return (
        <Suspense>
            <div>
                <Message />
            </div>
        </Suspense>
    );   
}
```
- lazy
- loading
- fallback &#10004;
- spinner

#### 28. What do you call the message wrapped in curly braces below?
```js
let message = "Hi there";
const element = <p>{message}</p>
```
- a JS function
- a JS element
- a JS expression &#10004;
- a JSX wrapper

#### 29. When do you use useLayoutEffect?
- to optimize for all devices
- to complete the update
- to change the layout of the screen
- when you need the browser to paint before the effect runs &#10004;

#### 30. What is the difference between the click behaviors of these two buttons (assuming that this.handleClick is binded correctly)?
```js
A. <button onClick="{this.handleClick}>Click Me</button>"
B. <button onClick="{event => this.handleClick()event}}>Click Me</button>"
```
- Button A will not have access to the event object on click of the button.
- Button B will not fire the handler this.handleClick successfully. &#10004;
- Button A will not fire the handler this.handleClick successfully.
- There is no difference

#### 30. When might you use React.PureComponent?
- when you do not want your component to have props
- when you have sibling components that need to be compared
- when you want to implement shouldComponentUpdate() by default to not update unnecessarily &#10004;
- when you do not want your component to have state

#### 30. Why is it important to avoid copying the values of props into a component's state where possible?
- because you should never mutate state
- because getDerivedStateFromProps() is an unsafe method to use
- because you want to allow a component to update in response to changes in the props &#10004;
- because you want to allow data to flow back up to the parent

#### 30. What is the children prop?
- a property that adds child components to state
- a property that lets you pass components as data to other components &#10004;
- a property that lets you set an array as a property
- a property that lets you pass data to child elements

#### 31. A representation of a user interface that is kept in memory and is synced with the "real" DOM is called what?
- virtual DOM &#10004;
- DOM
- virtual elements
- shadow DOM

#### 32. You have written the following code but nothing is rendering. How do you fix this problem?
```js
const Heading = () => {
    <h1>Hello!</h1>
};
```
- Add a render function
- Change the curly braces to parentheses or add a return statement before the h1 tag. &#10004;
- Move the h1 to another component.
- Surround the h1 in a div.
