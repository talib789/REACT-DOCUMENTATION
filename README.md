# What is React?
##  ReactJS is a declarative, efficient, and flexible JavaScript library for building reusable UI components.<br> It is an open-source, component-based front end library responsible only for the view layer of the application.
# Who made React?
## It was created by Jordan Walke.
# What is Babel?
## Babel is a JavaScript compiler that can translate markup or programming languages into JavaScript.<br> With Babel, you can use the newest features of JavaScript (ES6 - ECMAScript 2015).<br>Babel is available for different conversions.<br> React uses Babel to convert JSX into JavaScript.Please note that <script type="text/babel">is needed for using Babel.
# How does Babel convert html code in React into valid code?
## Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.<br>Here are the main things Babel can do for you:<br>Transform syntax<br>Polyfill features that are missing in your target environment (through a third-party polyfill such as core-js)<br>Source code transformations (codemods)
# What is ReactDOM used for? Write an example?
## ReactDOM is the middleman that renders the React element in the browser. ReactDOM comes with some useful methods but the method in which we are interested is render. It takes 2 parameters describe as what(element you want to render) and where(the location where you want to render).
 Example: To render the above list element(listElement) in DOM.
  const listElement = React.createElement( 'li', {
    className: 'list'
}, 'React.js' );
ReactDOM.render( listElement, document.querySelector( '#root' ) );
# What are the packages that you need to import for react to work with?
## These packages are big time-savers — use them when you can, and often! 1. React Testing Library The React Testing Library is a lightweight solution for testing React components. The library provides light utility functions on top of react-dom and react-dom/test-utils.
# How do you add react to a web application?
## React has been designed from the start for gradual adoption, and you can use as little or as much React as you need. Perhaps you only want to add some “sprinkles of interactivity” to an existing page. React components are a great way to do that.
The majority of websites aren’t, and don’t need to be, single-page apps. With a few lines of code and no build tooling, try React in a small part of your website. You can then either gradually expand its presence, or keep it contained to a few dynamic widgets.
# What is React.createElement?
## React.createElement () Method: The React.createElement () method is used to create elements. Whenever we write code in JSX, JSX converts it to React.createElement (). The createElement method is not recommended to use as it is very hard to maintain or debug.
# What are the three properties that createElement accept?
## const element = React.createElement('div', {id: 'login-btn'}, 'Login') createElement takes in three arguments. The first is a tag name string (div, span, etc), the second is any attributes you want the element to have, the third is the contents or the children of the element, in this case, the text "Login".
# What is the meaning of render and root?
## React renders HTML to the web page by using a function called render().
 The purpose of the function is to display the specified HTML code inside the specified HTML element.
In the render() method, we can read props and state and return our JSX code to the root component of our app.
In the render() method, we cannot change the state, and we cannot cause side effects( such as making an HTTP request to the webserver).
Root The root element is the passed to the ReactDom. "... The React tree is: a tree composed of React elements that implements a virtual DOM system where only the updates are applied to the real DOM (browser DOM) Structure React element
  
