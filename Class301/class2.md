## *Readings: State and Props*

### React Lifecycle
* Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? 

Render occurs first

* What is the very first thing to happen in the lifecycle of React? 

Mounting is the first thing that occurs.

* Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, render, React Updates, componentDidMount, componentWillUnMount

* What does componentDidMount do?

It is used to initialize the DOM or if you need to load anything using a network request.

### React Stat VS Props
* What types of things can you pass in the props?

I'm pretty sure props can be anything like a variable, function, string, array, etc...

* What is the big difference between props and state? 

State is used when we are dealing with user interaction, because it needs to be used locally and rerendered. Props is stuff you pass in to dynamically change elements. 

* When do we re-render our application?

When the user does something that changes the applicationm.

* What are some examples of things that we could store in state?

Things that we might need to keep track of that would increment.


## Notes from Class

3 things we need when using react:
Import React, declare the class(probably need to have a render), export the class

<> </> marginal or fractional element

files that need to be used on your website from react, need to be in your public file.
you can access them just by referncing the folder the images are you
if you need to use the src folder you have to use ./ to go to it.

