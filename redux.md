
# Is Redux Toolkit a React Library ?

##Introduction
A lot of React developers are big fans of using Redux in their projects in order to make the development of their App much more easier and constructive, but many people who are new to React believe that it is an official React library which is not the case. In this article, I will show you what exactly Redux is and the steps you will make to start using it in your projects. With that being said, let's dive in 😎

Guidelines:

Step 1: What Exactly is Redux Toolkit </br>
Step 2: Benefits of using Redux in your React Application </br>
Step 3: How to use Redux Toolkit </br>

<h2>What Exactly is Redux Toolkit ?</h2>

In simple definition, Redux is an open-source javascript library for managing and centralising application state. it was created by Dan Abramov and Andrew Clark. read the full story here

Redux is quite similar to React context API / useContext Hook, which means that it is not always necessary for you to use Redux everytime in your Application. if you are very familiar with React Context API, you are already in good shape, but when you are working on a bigger Application, you can use Redux in order to structurize your Application in simple and effective manner.

There are some importance of using Redux in your application which are listed below

It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test.

Centralizing your application's state and logic enables powerful capabilities like undo/redo, state persistence, and much more.

The Redux DevTools make it easy to trace when, where, why, and how your application's state changed. Redux's architecture lets you log changes, use "time-travel debugging", and even send complete error reports to a server.

Redux works with any UI layer, and has a large ecosystem of addons to fit your needs.

##Benefits of using Redux in your React Application
It's a no brainer that Redux has some cool and amazing benefits when you incorperate it in your projects, some of the benefits of using Redux are:

Simplicity : It includes utilities to simplify common use cases like store setup update logic and more...</br>

Opinionated : It provides good default store setup out of the box and includes the most commonly used redux addons built-in</br>

Powerful : It takes inspiration from libraries like immer and autoduo to let you write mature immutable update logic and even create entire slices of state automatically</br>

Effectiveness : It enables you to focus on the entire core logic your app needs so you that can do more work with less code.</br>
##How to use Redux Toolkit in your React App
First thing's firts. In React land or just like any other Javascript libary or frameworks, whenever we want to use an external package, then we will have to install it and that is first step towards using Redux toolkit in our React Application

To install Redux toolkit in our react app, then we will have to type the code below, it is also available as a package on NPM for use with a module bundler or in a Node application:
# NPM
npm install @reduxjs/toolkit

# Yarn
yarn add @reduxjs/toolkit

<h>Basic Example</h2>
import { createStore } from 'redux'

/**
 * This is a reducer - a function that takes a current state value and an
 * action object describing "what happened", and returns a new state value.
 * A reducer's function signature is: (state, action) => newState
 *
 * The Redux state should contain only plain JS objects, arrays, and primitives.
 * The root state value is usually an object. It's important that you should
 * not mutate the state object, but return a new object if the state changes.
 *
 * You can use any conditional logic you want in a reducer. In this example,
 * we use a switch statement, but it's not required.
 */
 /*
function counterReducer(state = { value: 0 }, action) {
  switch (action.type) {
    case 'counter/incremented':
      return { value: state.value + 1 }
    case 'counter/decremented':
      return { value: state.value - 1 }
    default:
      return state
  }
}
*/

// Create a Redux store holding the state of your app.
// Its API is { subscribe, dispatch, getState }.
let store = createStore(counterReducer)

// You can use subscribe() to update the UI in response to state changes.
// Normally you'd use a view binding library (e.g. React Redux) rather than subscribe() directly.
// There may be additional use cases where it's helpful to subscribe as well.

store.subscribe(() => console.log(store.getState()))

// The only way to mutate the internal state is to dispatch an action.
// The actions can be serialized, logged or stored and later replayed.
store.dispatch({ type: 'counter/incremented' })
// {value: 1}
store.dispatch({ type: 'counter/incremented' })
// {value: 2}
store.dispatch({ type: 'counter/decremented' })
// {value: 1}

In order to dive deeper on how to use Redux in your React Application, visit the official website here to learn more about it. There is absolutely no doubt that these are the basic things you have to know before getting started with Redux.

In cnclusion, Redux is very very useful when working on a large Application. You can always use React context API to achieve similar task which means you don't always have to use Redux, but in many cases, you can. 💪

So with that being said, Have fun while learning 😎 stay motivated Keep coding see you soon !!!
