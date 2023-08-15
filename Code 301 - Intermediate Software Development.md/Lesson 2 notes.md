# State and Props

### The React Lifecycle

1. Based off the diagram, what happens first, the 'render' or the 'componentDidMount'?

* The render is what happens first.

2. What is the very first thing to happen in the lifecycle of React?

* "Mounting", or the instance in which a component is created and inserted into the DOM.

3. Put the following things in the order that they happen: 

* Constructor > render > React updates > componenetDidMount > componentWillMount

4. What does componentDidMount do?

* "If you need to load anything using a network request or initialize the DOM, use this." 

### Videos

1. What types of things can you pass in the props?

2. What is the big difference between props and state?

* State is handled in the component and you can update it inside the componenet, whereas props are handled outside the component and therefore must be updated outside of the component.

3. When do we re-render our application?

* When the user changes something within the application.

4. What are some examples of things that we could store in state?

* User data that was taken from a form, a counter, or a toggle option.