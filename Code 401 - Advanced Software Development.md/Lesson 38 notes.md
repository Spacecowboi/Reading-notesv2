# Redux - Asynchronous Actions

### async actions

1. Why use redux middlware?

* Redux middleware is very flexible in that it's able to handle authentication, authorization, and async actions especially.

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words. 

* So we got the UI where the user clicks on something or does *something* to initiate an action, which then goes to the **dispatch** , from dispatch, the action is sent over to the middleware where a request is sent to an API, which sends the requested object back to the middleware, using dispatch to then change the state of the store, returning the users request object as a payload from the store, changing the state depending on the action.

3. How are we accommodating async in our Redux app?

* By using middleware, in this case Redux-thunk

### thunk middleware

1. Why would you need redux-thunk middleware?

* "Middleware extends the store's abilities, and lets you write async logic that interacts with the store."

2. Redux middleware allows you to write action creators that return a __ instead of an action.

* "function"

3. Describe how any return value from the inner thunk function will be made available.

* It will be made available as the return value of dispatch

