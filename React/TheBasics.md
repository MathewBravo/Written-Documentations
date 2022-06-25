# Reacts Basics

## What is a React App?

One of the most widely used front-end JavaScript libraries. Its main purpose (outside of React.native mobile applications) is to facilitate efficient UI creation that is then rendered to a Virtual DOM.

### The Virtual Document Object Model (VDOM or Virtual DOM)

This is a concept in React in which a UI is kept in memory and then passed to the real DOM via the React library.

Unlike in Angular react renders the DOM anytime a change in [State](statelink) is made. If we were to re-render the REAL DOM completely each time that would be very intensive and very slow. The virtual DOM is like a carbon copy that sits atop the actual DOM. Then any changes you make re-render the lightweight virtual DOM and only the differences between your real and virtual DOM are applied.

## Creating a React App

### npx

`npx create-react-app [app_name]`

### npm

`npm init react-app [app_name]`

### yarn

`yarn create react-app [app_name]`

### Then you can move into your react app via:

`cd [app_name]`

### Finally you can run the react app via:

npm & npx

`npm start`

yarn

`yarn start`

## The Structure of a React app

React is made up of [Components](componentlink). Up until recently components have been written as classes, however it has become more widely accepted to write your components as functions. This is done either in the form of an arrow function or a regular named function. Below is an example of all three, which ultimately out put the exact same thing.

### Class (Old Way)

```javascript
import React from 'react';

class App extends React.Component {
    render() {
        return (
            <>
                <h1>App</h1>
                <p>Hello World</p>
            </>
        );
    }
}

export default App;
```

### Arrow (Most Common)

```javascript
const App = () => {
    return (
        <>
            <h1>App</h1>
            <p>Hello World</p>
        </>
    );
};

export default App;
```

### Normal Functions

```javascript
function App() {
    return (
        <>
            <h1>App</h1>
            <p>Hello World</p>
        </>
    );
}

export default App;
```

### Output 

> # App 
> ### Hello World

All three of the above are components and are just evolutions of the progression of react as a library. 

To progress further into react it's best to talk about each aspect of the Library separately. In order to facilitate this process I've broken up this documentation into respective parts.

- [Components](components)
- [State](state)
- [Hooks](hooks)
- [Events](events)
- [Props](props)
- [Conditional Rendering](rendering)
- [API Calls with Axios and Fetch](apis)
- [Custom hooks](customhooks)
