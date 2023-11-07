# Redux

### Redux Tutorials

1. What is the first principle of Redux?

* State(App) === {store} - a single JS object.

2. What is a store and what do we use our reducers for within that store?

* A "store is what holds that entire state of an application. It makes managin state much easier. Reducers, in this context, take the current state + an action, and return a new state.

3. Name three Redux store methods given to us by createStore and describe their use.

* getState - retrieves the current state of the store
* dispatch - "dispatches" actions to the Redux store, triggering state change.
* subscribe - adds a listener function that is invoked whenever an action is "dispatched" and the store gets updated.

4. Explain to a non-technical recruiter what combineReducers() does and why is it useful.

* combineReducers() is a tool that makes managing this big, complex puzzle box a lot easier by divyying it up into smaller pieces. Then it puts those small pieces together when needed to make the whole application.