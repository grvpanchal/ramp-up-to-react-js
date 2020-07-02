# Overview
This is a quick guide to ramp up to React JS by beginning with essential HTMl CSS and JavaScript knowledge to code in React. Initially when I started React without knowing ES6, It was a lot to grasp and difficult wrap thing around in head. The Pathway below is design to be efficient in HTML, CSS and JS first. This is important as Learning react may look easy but while coding if the core of JavaScript is not clear, you will have huge trouble in debugging the code.

As you move along the parts, you dont directly start ReactJS coding, instead you first have to get accustomed to syntax like JSX, CSS as Objects and way to think before writing in ReactJS. Understand first what React does with light DOM using virtual DOM. Once, your mind is prepared, learning React becomes a hell lot easier. As you know React is just a library and final product (i.e. websites) is amalgamation of architecture and various technologies which are addons to React Library. Improper knowledge of this amalgamation results in destructive self growth in frontend technology.

## Part 1: Understanding HTML and CSS relation to Browser
This is first and foremost part every developer working with website should know. Forget JavaScript right now. JavaScript only won't make content appear on to browser but HTML and CSS will. 

Young developer are directly moved to React and Angular is a big red indicator for their personal development. Its not young developers are bad at HTMl/CSS. The major problem is not HTML/CSS but the exposure they are given to it. While taking interview many candidates directly jump on to technologies like Angular and ReactJS (JavaScript Framework) without understanding the internal workings of HTML and CSS.

Everything you see on the web is built on HTML and CSS. JavaScript only gives the interactiveness to a site. Now in the modern age, the site needs to work as an App. So JavaScript Frameworks are made to make the site work as an app. There is a major practice problem such that developers get too much involved in framework JS. I have heard developers losing grip on HTML and CSS as tickets have major work on App improvements bit and not UI changes. I recommend developer to practicing on developing an app from scratch, once a month, so they get full insight of how web architecture of SPA and PWA work around to generate HTML DOM and CSS.

### Content
- Clear Introduction
- HTML
- CSS
- Developer's insight into UI and UX
- Essential HTML and CSS for SPA

## Part 2: Core of JavaScript
Once your core of javascript is strong, you can work in any front end Framework with ease. Using this knowledge you could earn the most merit in Web development on Apps like SPA and PWA. Many developers in interview study a lot on React and redux but fails to answer the core mechanisms on how object works. 70% developers in interview who know redux, fail to answer below example
```js
const a = { name: 'abc' };
const b = a;
b.name = 'xyz';
console.log(a.name); // Output is 'xyz'. I dont want object 'a' to change. How do I do that?
```
If you are unable to answer this you need to make you core knowledge of JavaScript stronger as knowing Redux means nothing if you can't solve this.

### Content
- Declaration, Datatypes and Type conversions
- Comparisions
- Operators (Majorly Logical)
- Loops and Conditions
- Iterators and Generators
- Objects
- Arrays
- Destructuring assignment
- Arrow Function and binding
- Decorators and Forwarding
- ProtoType and Prototypal Inheritance
- Scope
- Closure
- Error Handling
- Asynchronous (Kronos - Titan of Time) JavaScript
    - setTimeout
    - setInterval
    - Callbacks
    - Promises
    - Async await
    - AJAX
- ES6 Modules
- Classes
- Understanding Event Loop
- DOM Tree
- Storage
- Native Event Binding with attributes
- Airbnb Coding Style
- Tests

<span style="font-size: 56px; color: red"> Do not Start the Below section unless you have completed the Core of JavaScript<span>

## Part 3: Adjusting to React
Starting coding in react project directy
- Introduction
- Imperative and Declarative
- Understanding vDOM
- Adopting JSX writing style
- Bending CSS to Objects
- Thinking in React
- Hello World with CDNs

## Part 4: Prerequisites of React
- npm
    - Saving and executing
    - package.json options
    - environment variables
    - Linting Config
    - Ejecting Configuration
- Webpack
    - Dev Server
    - Babel
    - Resource Import with Loaders

## Part 5: Hierarchy of React
- Router
    - Lazy Loading and Code Splitting
- Containers (also known a modules, views in other framework)
- Components
    - Rendering the JSX
    - Loop and Conditional Rendering
    - Working with Props
    - Composition vs Inheritance
    - Passing the Data to Component: State and Lifecycle
    - Interactions to Component: Events and State
        - Handling Events
        - Forms
        - Lifting State Up
        - Hooks
    - Refering to DOM via React Refs
- Tutorial
- Create React App
- Summary of fundamentals
        
## Part 6: Diffusing State Management onto React Architecture
- The State of Immutability
- Redux
    - thunk
    - SAGA
## Part 7: Debugging, Testing and Resources
- Debugging Tools
- Unit Testing Tools
- Resources
    
