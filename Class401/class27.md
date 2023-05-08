# useState() Hook

## Thinking in React

1. **Summarize the five steps of thinking in react.**
   The five steps are: (1) Break the UI into a component hierarchy. (2) Build a static version in React. (3) Identify the minimal (but complete) representation of UI state. (4) Identify where your state should live. (5) Add inverse data flow.

## State: A Component’s Memory

1. **What is one reason a local variable isn’t sufficient for managing a React component?**
   A local variable isn't sufficient for managing a React component because its value does not persist across re-renders. When a component re-renders, all local variables are reset.

2. **What is the argument to the useState hook, and what are the two parts of its return array?**
   The argument to the `useState` hook is the initial state. The return array consists of two parts: the current state and a function to update that state.

3. **How can Component A access state from Component B?**
   Component A can access state from Component B either by lifting the state up to their closest common ancestor, or by using context or Redux for more complex scenarios.

