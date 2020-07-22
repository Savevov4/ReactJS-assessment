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
    } // &#10004;

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
