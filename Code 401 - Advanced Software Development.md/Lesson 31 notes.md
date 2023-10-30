# Context API

### Choosing the State Structure

1. Summarize the five principles for structuring state.

* Group Related State - If you need to update more than a couple of state variables, merge them into one state variable.

* Avoid contradicitons in state - Don't use state in ways that they will overlap each other and cause problems later.

* Avoid redundant state - Don't repeat yourself. Don't make multiple copies of the same data.

* Avoid duplication in state - Try to just have one single soursce of truth in your data

* Avoid deeply nested state - Keep it simple, don't make things a temple of doom.

### Passing State Deeply with Context

1. What problem do Contexts aim to solve?

* It gives devs the ability to pass props without having to continually pass them through a nested architechture of components and parent/sibling relations.

2. What is one technique to try before useContext?

* "Prop Drilling" - essentially the process I described above

3. What hook complements useContext for complex applications?

* useReducer