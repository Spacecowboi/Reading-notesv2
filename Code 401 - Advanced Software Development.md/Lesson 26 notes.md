# Component Based UI

### React Quick Start

1. What are the building blocks of a React App?

* React apps are built out of components

2. What is the difference between an HTML element and a React Component?

* An html element is the building block of a webpage and a React component is the building block of a React Application

3. What is JSX and why do we use it?

* JSX is a type of syntax that is stricter than HTML and is primarily used for React. It lets you write HTML-ish JS code, so it's easier to define JS-React things.

4. Describe the process of embedding JavaScript expressions in JSX.

* Wrap it up...in curly brackets.

5. Does React or JSX have any special features for iteration or conditional logic?

* No they do not. 

6. How does React know to respond to a user's inputs?

* Event listeners/handlers like a button or logging a click event

7. What word indicates that a React component manages data with a Hook?

* "use". So "useThis". "useThat". "useState".

8. How can two react components share data?

* props, inheritance, or hooks.


### Render and Commit

1. What are the three steps of refreshing a React UI?

* Triggering a render
* Rendering the component
* Committing to the DOM

2. How do you trigger updates to a component afte the initial render?

* "You can trigger further renders by updating its state with the (set) function. Updating your component's state automatically queues a render."

3. Does React recreate DOM nodes on every render?

* "React *only* changes the DOM nodes if there's a difference between redners."

4. After React has updated the DOM, what still needs to happen before the user sees the change?

* The application needs to still re-render