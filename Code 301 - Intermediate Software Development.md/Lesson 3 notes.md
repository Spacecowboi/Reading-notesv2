# Passing Functions as Props

### Lists and Keys

1. What does .map() return?
* A new array of objects where every item in the array is altered.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
* The .map method

3. Each list item needs a unique _
* Key

4. What is the purpose of a key?
* It helps react update the component when the array is changed. 

### The Spread Operator

1. What is the spread operator?
* "A useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function's arguments.

2. List 4 things the spread operator can do
* Array Expansion
* Function Arguments
* Object Propagation
* Destructuring Arrays and Objects

3. Give an example using the spread operator to combine two arrays.

* let array1 = [1, 2, 3]
  let array2 = [4, 5, 6]

  let combinedArray = [...array1, ...array2]

4. Give an example of using the spread operator to add a new item to an array.
* let ogArray = [1, 2, 3];
  let newNumber = 4;

  let newArray = [...ogArray, newNumber]
  

5. Give an example of using the spread operator to combine two objects into one.

let object1 = {key1: 'value1', key2: 'value2'}
let object1 = {key3: 'value3', key4: 'value4'}

let fusedObject = {...object1, ...object2}
return fusedObject

### How to pass functions between components
1. In the video, what is the first step that the devloper does to pass functions between componenets?
* They defined the function in the first component (parent), and then passed it to the child component as a prop.
2. In your own words what does the increment function do?
* It makes a function more valuable, so to speak. Like literally increasing a value by 1 for example.
3. How can you pass a method from a parent component into a child component?
* You do so by passing the method as a prop. 
4. How does the child component invoke a method that was passed to it from a parent component?
* By invoking the function (calling it)