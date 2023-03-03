## *Putting it all together*

### React Docs - Thinking in React

* What is the single responsibility principle and how does it apply to components?

Ideally, your component should do only one thing at a time. If it needs to do multiple, you should break it down into subcomponents. 

* What does it mean to build a ‘static’ version of your application?

Basically it means to make your app dumb but pretty. It has all the places for the info to go later. 

* Once you have a static application, what do you need to add?

Interactivity. 

* What are the three questions you can ask to determine if something is state?

Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

* How can you identify where state needs to live?

Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

### Higher-Order Functions

* What is a “higher-order function”?
 
 Functions that use other other functions, either as arguments or returning them. 

* Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
 
 It takes in an argument of n, which ends up being 10. Then on the second line, its returning m and its making m > n which since n is set to 10, it makes m 11. I think

* Explain how either map or reduce operates, with regards to higher-order functions.

Because instead of having to create modify then return, you can just return in the same line as you map an array from an old array.

