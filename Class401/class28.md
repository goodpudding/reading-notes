# Component Lifecycle / useEffect Hook

## useEffect hook

* *What is the main intended use case for the useEffect hook?*

  * The useEffect hook is a function provided by React that allows you to perform side effects in function components. Side effects could be data fetching, subscribing to some event, manual DOM manipulation, or setting up a timer, among other things. It essentially serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount combined in class components.

* *How does the effect’s logic interact with the component?*

  * The useEffect hook runs after every completed render (i.e., after the first render and after every update). The logic inside useEffect will execute in response to changes in the component lifecycle or in response to changes in data that the component depends on. The data dependencies of useEffect are managed through its second parameter, the dependency array. If any value in this array changes between renders, the effect function will be called.

* *What is the importance of the return value from the effect’s logic function?*

  * If the effect’s logic function returns a function, React will run that returned function when it is time to clean up. This is most commonly used to clean up side effects. For example, if your effect subscribes to some service or sets up a timer, it should also clean up after itself by unsubscribing or clearing the timer when the component unmounts or before re-running the effect due to a change in dependencies. This is analogous to how you would use componentWillUnmount in a class component to clean up ongoing side effects to prevent memory leaks.