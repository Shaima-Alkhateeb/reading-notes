# Class 02 :State and Props

## (React lifecycle)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
--> render
2. What is the very first thing to happen in the lifecycle of React?
--> constructor
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
--> (constructor -> render -> componentDidMount -> React Updates -> componentWillUnmount)
4. What does componentDidMount do?
---> allows us to execute the React code when the component is already placed in the DOM (Document Object Model).

## (React State Vs Props)

1. What types of things can you pass in the props?
--> pass values from one component to another component down the component tree.
2. What is the big difference between props and state?
--> state is handled in the component and you can update it inside the component. But props handel outside the component and must be updated outside of the component.
3. When do we re-render our application?
--> whenever there is a change in their state or props.
4. What are some examples of things that we could store in state?
--> counter
