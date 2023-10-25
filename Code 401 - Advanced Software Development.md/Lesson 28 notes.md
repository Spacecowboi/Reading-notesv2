# Component Lifecycle/Hook

### useEffect

1. What is the main intended use case for the useEffect hook?

* It allows you to synchronize a component with an external system.

2. How does the effect's logic interact with the component?

* It works with the component via the useEffect function. After the component has rendered, it is then able to interact with things like props and state.

3. What is the importance of the return value from the effect's logic function?

* It's like the preventDefault() method. It essentially for "cleaning up". Removing old values and replacing them with new ones, and facilitating the new render. 