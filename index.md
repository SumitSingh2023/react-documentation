1.  What is React ?
    React is a javascript library for building users interfaces.
    React is used to build single-page applications.
    React allows us to create reusable UI components.

2.  Who made React ?
==>    Jordan Walke

3. What is Babel ?
=> Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backward compatible version of javascript in current and older browser or environments. 

4.How does Babel convert html code in React into valid code?
=> Babel doesn't directly convert HTML code into React. Instead, it primarily transpiles JavaScript syntax, including JSX, a JavaScript extension used by React to write component-based UI.

5. What is ReactDOM used for? Write an example?
=> ReactDom is a package in React that provide Dom-specific methods used for interacting with the DOM.It's primarly responsible for rendering React components into the HTML Dom and managing their lifecycle

example=>// Import necessary libraries
        import React from 'react';
        import ReactDOM from 'react-dom';
        
        // Define a simple React component
        const App = () => {
          return <h1>Hello, React!</h1>;
        };
        
        // Render the React component into the DOM
        ReactDOM.render(<App />, document.getElementById('root'));


6.What are the packages that you need to import for react to work with?

=> react
   react-dom
   babel
   webpack

7.How do you add react to a web application?
=> You can add React to an existing HTML page including some script tags that load React and React DOM from CDN .You can then write your React components in a separate Js file and use JSX syntax with the help of Babel.

8.What is React.createElement?
=>React.createElement is a function that creates and returns a React element based on the given arguments.A React elements is a virtual representation of a UI components or an HTML element ,ready to be rendered by React.
React.createElement is often used when JSX is not available or as a lower-level API for element creation

Syntaxof React.createElement is:
React.createElement(type,properties,...children)

9.What are the three properties that createElement accept?

=> Type
   Properties
   children 


10.What is the meaning of render and root?

=> Render is the process of creating and updating the React elements based on the props and state of the components1. Render can also refer to the function that returns the React elements to be displayed, such as the render() method in class components or the function body in function components2.


Root is the browser DOM element that React uses as the container for the React elements1. Root can also refer to the object returned by ReactDOM.createRoot(), which provides methods to display and unmount the React elements inside the root element34.
