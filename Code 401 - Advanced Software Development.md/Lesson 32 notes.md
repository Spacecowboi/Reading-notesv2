# Scaling Up with Reducer and Context

1. How do useReducer and useContext work together to simplify state management in a React application?

* useReducer and useContext are two hooks that make state management in React much easier. useReducer helps out by making a "reducer" function, which does essentially what it sounds like, it "reduces" the processes that manage state. It's very useful for managing apps at scale that are managing multiple state transtions. 

* useContext on the other hand, let's components within React access values stored in a "context", which prevents the need for prop drilling. An example of prop drilling would be: "this prop is passed to this child and then this child from this child, etc". To use it effectively, you're essentially wrapping all of your React components in a hook that allows these values to be shared. When you mix both useReducer and useContext, you are able to keep your state management in one place and make it accessible by the components within the context of your React app.
