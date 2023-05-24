1. **Why use Redux middleware?**
Redux middleware provides a third-party extension point between dispatching an action, and the moment it reaches the reducer. It's commonly used for dealing with asynchronous actions in Redux. This is crucial for operations like logging, crash reporting, or making API calls.

2. **Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.**
The async data flow in Redux starts with a UI event like a button click, this triggers an action creator function. However, instead of returning a plain JavaScript object as in synchronous actions, it returns a function (using Redux Thunk middleware). This function can dispatch multiple actions over time, like one for request start and one for request completion. These actions go through the middleware, then reach the reducers which update the state, and finally the view gets updated based on the new state.

3. **How are we accommodating async in our Redux app?**
By using dispatches to call functions asynchronously 

4. **Why would you need redux-thunk middleware?**
Redux Thunk middleware allows you to write action creators that return a function instead of an action. This is particularly useful when you need to make an asynchronous operation, like an API call, where you need to dispatch an action once the request is completed.

5. **Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.**
*function*

6. **Describe how any return value from the inner thunk function will be made available.**
Any return value from the inner function of a Redux Thunk will be used as the return value of the dispatched action. This can be useful when you want to wait for some asynchronous operation to finish.
