# Redux

## Installing Redux

## npm

```
npm install @reduxjs/toolkit react-redux
```

#### just core

```
npm install redux
```

#### from app creation

```
npx create-react-app my-app --template redux
```

## yarn

```
yarn add redux
```

#### toolkit

```
yarn add @reduxjs/toolkit
```

## How does it work?

Redux uses a singular state storage process, that stores all cross-components or app wide state. This state storage allows data to be accessed from different components, via subscriptions. While components can subscribe to the state storage they cannot alter what is being stored directly. Stored data however can be manipulated using Reducers, **NOT useReducer**.

### Reducers

Reducers are functions that you create which take arguments of a current state and an action, and return a new state as its return object.

```javascript
function appReducer((state, action) => newState))
```

### Actions

These are basic JS functions that are forwarded to your Reducer that provide it with a typed object which is a description of the event that took place. For example clicking a button to remove an item from a list.

While named **Actions** they themselves do not perform the action and merely tell the Reducer what to do. The reducer then uses that action as the parameter in which the current state is updated to.

#### Payloads

```javascript
const action = {
    type: 'BET_ON_TEAM',
    payload: {
        amount: 10,
        team: 'Toronto Maple Leafs',
    },
};
```

While the action is used to describe what takes place, the payload are the key value pairs that can be used inside the store to make changes to the current state.

## Redux Methods

### createStore(reducer, initial state)

Creates the store that holds the state of your application.
It takes two arguments of your reducer, and an initial state.

### subscribe(listener)

Listens for a change in the store. Anytime there is an action dispatch to the store and some part of the tree may have been changed the listener will be called and invoked.

### dispatch(action)

Sends an action to the reducer which then triggers a change in the current state.

### replaceReducer(new reducer)

Replaces the current reducer with the provided one.

### getState()

Returns the current state store.

## Other Notables

[Three Principles](https://redux.js.org/understanding/thinking-in-redux/three-principles)

> -   Single source of truth
> -   State is read-only
> -   Changes are made with pure functions

-   When applications are intialized the reducer will be run so your initial state will be undefined. State should be intialized with a default value
-   **NEVER MUTATE STATE ONLY OVERWRITE IT**

```javascript
const appReducer = (state = { object: InitialValue }, action) => {};
```
### useSelector()
> Allows you to extract data from the Redux store state, using a selector function.

### useStore()
> This hook returns a reference to the same Redux store that was passed in to the <Provider> component.

### useDispatch
> This hook returns a reference to the dispatch function from the Redux store.
    
