# React Lifecycle 
Lifecycle of Components
Each component in React has a lifecycle which you can monitor and manipulate during its three main phases.

* The three phases are: Mounting, Updating, and Unmounting.

Mounting: that is when in instance of a component is being created and inserted into the DOM.

Updating: it's when a component is updated or stat changes.

Unmounting: it's when a component is being removed from the DOM.

## What is the very first thing to happen in the lifecycle of React? ##
The very first thing is the mounting, and that is when in instance of a component is being created and inserted into the DOM.

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates .

1. constructor 
2. render
3. React Updates
4. componentDidMount
5. componentWillUnmount

## What does componentDidMount do? ##
 it happend right after a component is loaded. when we want to load something through initializing our DOM, it will go to it.

##  What types of things can you pass in the props? ##
static information

## What is the big difference between props and state? ##
is that we can pass props into a component it is handled out side the component but state is handled inside that comopnent.

## When do we re-render our application? ##
When we change the state inside our application, it is going to re-render that section of our application.

## What are some examples of things that we could store in state? ##
user inputs inside a form