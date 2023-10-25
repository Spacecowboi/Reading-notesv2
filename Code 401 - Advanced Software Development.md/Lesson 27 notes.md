# Hooks

### Thinking in React

1. Summarize the five steps of thinking in react.

* Structure each part of the UI into different components, little boxes that outline how the page is going to look after being broken down.

* Build a static version of the app in React. This means build the app how you want it to be without adding the parts that make it interactive

* Then you need to let users change the underlying data model. This is where you implement *state* into the equation

* Identify where state is going to live. Every piece of the react puzzle that renders is going to need to have it's *state* altered.

* Add inverse data flow. This means "You want to make it so whenever the user changes the form inputs, the *state* updates to reflect those changes."

### State: A Component's Memory

1. What is one reason a local variable isn't sufficient for managing a React component?

* Local variables don't persist between renders.

2. What is the argument to the useState hook, and what are the two parts of its return array?

* The argument is it's initial value, and the two parts of the return array are the *getter* and *setter*

3. How can Component A access state from component B?

* By passing the state as a prop