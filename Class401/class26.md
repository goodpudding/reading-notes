# Component Based UI

## React Quick Start

1. **What are the building blocks of a React app?**
   React applications are primarily built using components. Components are reusable, isolated pieces of code that return a React element to be rendered on the UI.

2. **What is the difference between an HTML element and a React component?**
   An HTML element is a building block of web pages defined by standard HTML tags, whereas a React component is a JavaScript function or class that optionally accepts inputs and returns a React element.

3. **What is JSX and why do we use it?**
   JSX is a syntax extension for JavaScript used in React to describe what the UI should look like. It is used because it allows writing HTML structures in the same file that contains JavaScript code.

4. **Describe the process of embedding JavaScript expressions in JSX.**
   JavaScript expressions can be embedded in JSX by wrapping them in curly braces `{}`.

5. **Does React or JSX have any special features for iteration or conditional logic?**
   Yes, JSX allows JavaScript expressions, so we can use JavaScript's built-in methods for iteration (like `map()`) and conditional logic (like `if` or ternary expressions).

6. **How does React know to respond to a user’s inputs?**
   React responds to user inputs through event handlers. These are special attributes (like `onClick`, `onChange`, etc.) that can be added to JSX elements and linked to JavaScript functions.

7. **What word indicates that a React component manages data with a Hook?**
   The word "use" in the function name (like `useState`, `useEffect`, etc.) indicates that a React component manages data with a Hook.

8. **How can two react components share data?**
   Two React components can share data by lifting the state up to their closest common ancestor, or by using context or Redux for more complex scenarios.

## Render and Commit

1. **What are the three steps of refreshing a React UI?**
   The three steps are: (1) The state of a component is updated. (2) React runs the render method again to find out what should be on the screen. (3) The React-DOM updates the DOM to match the React elements.

2. **How do you trigger updates to a component after the initial render?**
   You can trigger updates to a component by using state changing functions provided by `useState` hook or by calling `this.setState` in class components. Both cause the component to rerender.

3. **Does React recreate DOM nodes on every rerender?**
   No, React does not recreate DOM nodes on every rerender. It uses a diffing algorithm to determine what has changed and only updates those parts of the real DOM.

4. **After React has updated the DOM, what still needs to happen before the user sees the change?**
   After React has updated the DOM, the browser still needs to paint the updates. This involves calculating the layouts, styles, and finally drawing pixels to the screen.
