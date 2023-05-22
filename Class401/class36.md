The first principle of Redux is that the entire application state is stored in a single immutable object called the "store." The store represents the current state of the application and is responsible for managing and updating the state.

A store in Redux is a JavaScript object that holds the application state. Reducers are functions used within the store to specify how the state should change in response to different actions dispatched to the store. Reducers take the current state and an action as input and return a new state based on that action.

Three Redux store methods provided by createStore are:

getState(): This method returns the current state of the store. It allows you to access the current data stored in the Redux store.

dispatch(action): This method is used to dispatch an action to the store. It triggers the state update process by calling the appropriate reducer function and updating the state accordingly.

subscribe(listener): This method allows you to register a listener function that will be called whenever the state in the store changes. It enables components to react to state changes and update accordingly.

combineReducers() is a Redux utility function used to combine multiple reducers into a single reducer function. It takes an object as input, where each property represents a specific slice of the overall application state managed by a separate reducer. The combineReducers() function automatically combines these individual reducers into a single reducer that can be used with the Redux store. It is useful because it simplifies the process of managing complex application states by breaking them down into smaller, independent reducers, and combining them into one coherent state object.



