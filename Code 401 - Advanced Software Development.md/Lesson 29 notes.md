# Reducers

### Extracting State Logic into a Reducer

1. What is the motivation for adding a reducer?

* As a component grows, so does the amount of state logic needed to maintain functionality. Reducers move this state logic into a single function outside of the component.

2. What are actions in the context of a reducer? How are they different than setting state directly?

* Actions in the context of a reducer are a way to manage the state of the app. Directly setting the state can make things unpredictable because if your app is handling data dynamically, you can maybe find yourself dealing with an unmanaged state.

3. What common list operation is useReduce named for, and why?

* The .reduce() operation. It is named after that operation because it is highlighting the action of "reducing" something to a single value or thing specifically.

4. When should you switch from useState to useReducer?

* It depends on how complex your components end up being. If you have a component with basic state management, maybe a couple of states, you don't "need" to use useReducer. A good example would be middleware handling, if that was implemented into a component along with a host of other functions, it might be worth implementing useReducer.
