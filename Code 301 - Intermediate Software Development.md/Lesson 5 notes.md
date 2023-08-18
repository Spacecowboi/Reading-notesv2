# Thinking in React + Higher-Order Functions

### Thinking in React

1. What is the single responsibility principle and how does it apply to components?
* "Ideally, a componenet should only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

2. What does it mean to build a 'static' version of your application?
* Static basically meas a non-dynamic version of your application. Something where there isn't a whole lot of complexity in component execution.

3. Once you have a static application, what do you need to add?
* State values. So initially you add just the data values, and once you are ready to implement responsiveness, then you implement state functionality.

4. What are three questions you can ask to determine if something is state?
* Does it remain unchanged over time?
* Is it passed in from a parent via props? NOT STATE
* Can you compute it based on existing state or props in your componenet? Yeah? THEN IT AIN'T STATE!

5. How can you identify where state needs to live?
* "After identifying your app's minimal state data, you need to identify which component is responsible for changing this state, or *owns* the state."

### Higher-order Functions

1. What is a higher-order function?
* Functions that operate on other functions, either by taking them as arguments or by returning them, are what are known as "higher-order" functions.

2. Explore the *greaterThan* function as defined in the reading. In your own words, what is line 2 of this function doing?
* The second line is returning a function m => m > n;

3. Explain how either *map* or *reduce* operates, with regards to higher-order functions.
* In regards to higher-order functions, map works similarly to a lower order function, except in this instance we are applying a newly declared function inside of the original to every element of the array, which is then transformed and pushed into the new array, which we then return.