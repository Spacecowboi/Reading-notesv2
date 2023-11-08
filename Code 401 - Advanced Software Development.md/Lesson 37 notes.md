# Redux - combined reducers


### Multiple Reducers Example

1. Why create multiple reducers?

* Multiple reducers are created to manageg different states. It's important because every app has different components and managing them with one reducer is difficult.

2. How would you combine multiple reducers?

* using combineReducers. 

3. How will you manage state as immutable objects, why?

* You can manage it by using certain Javascript practices like combineReduce, or there is a whole library dedicated to it called Immutable.js

### Redux Docs: Using Combined Reducers

1. combineReducers is a utility function to simplify the most common use case when writing ___. 

* Redex reducers

2. Explain how combineReducers assembles the new state tree.

* "combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed."

3. How would you define initial state in an app using combineReducers? 

* you specify it as the default value in the reducer function

### Redux Docs: Combine Redducer Syntax

1. Why will you want to split your reducing functions as your app becomes more complex?

* keeping your code manageable and smaller throughout is incredibly beneficial as for modularity as opposed to having one massive function performing multiple tasks.

2. The ___ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to __.

* combineReducers
* createStore

3. What is a popular convention when naming reducers?

* Name reducers after the state slicesw they manage, so you can use ES6 property shorthand notation.