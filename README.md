# Reading Notes 📚

This web site is a document and highlight my new knowledge.

## 1. **Code 102** - Intro to Software Development

## 2. **Code 201** - Foundations of Software Development

## 3. **Code 301** - Intermediate Software Development

### Class 01 :

(Component-Based Architecture)

1. What is a “component”?
--> The component allows us to break the code into smaller codes, so if we have some bugs, or when we modify something we can easily access it. In general, we have 5 components (App, Header, SidebNav, Main, and  Footer).
2. What are the characteristics of a component?
--> (Reusability, Replaceable, Not context-specific, Extensible,Encapsulated , Independent )
3. What are the advantages of using component-based architecture?
--> To help us avoid the introduction of errors.

(What is Props and How to Use it in React)

1. What is “props” short for?
--> properties
2. How are props used in React?
1-Defining Attribute & its Data
2-Then pass it to child component(s) by using Props
3-Finally, render the Props Data
3. What is the flow of props?
--> A uni-directional flow (one way from parent to child)

---

### Class 02 :

(React lifecycle)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
--> render
2. What is the very first thing to happen in the lifecycle of React?
--> constructor
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
--> (constructor -> render -> componentDidMount -> React Updates -> componentWillUnmount)
4. What does componentDidMount do?
---> allows us to execute the React code when the component is already placed in the DOM (Document Object Model).

(React State Vs Props)

1. What types of things can you pass in the props?
--> pass values from one component to another component down the component tree.
2. What is the big difference between props and state?
--> state is handled in the component and you can update it inside the component. But props handel outside the component and must be updated outside of the component.
3. When do we re-render our application?
--> whenever there is a change in their state or props.
4. What are some examples of things that we could store in state?
--> counter

---

### Class 03 : Passing Functions as Props

(React Docs - lists and keys)

1. What does .map() return?
--> returns an entirely new array with transformed elements and the same amount of data.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?

`const numbers = [1, 2, 3, 4, 5];`
`const listItems = numbers.map((numbers) =>`
 `<li>{numbers}</li>`
`);`
`const root = ReactDOM.createRoot(document.getElementById('root'));`
`root.render(<ul>{listItems}</ul>);`

3. Each list item needs a unique key.
4. What is the purpose of a key?
--> to identify which items in the list are changed, updated, or deleted.

(The Spread Operator)

1. What is the spread operator?
-->is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements.
2. List 4 things that the spread operator can do.
--> Copying an array, Using Math functions, Using an array as arguments, and Adding to state in React.
3. Give an example of using the spread operator to combine two arrays.

`const numbers1 = [1, 2, 3, 4, 5];
const numbers2 = [6, 7, 8, 9, 10];
const numbers3 = [...numbers1, ...numbers2];`

4. Give an example of using the spread operator to add a new item to an array.

`const numbers = [1, 2, 3, 4, 5];
const add = [...numbers, 6];`

5. Give an example of using the spread operator to combine two objects into one.

`let person = {
  firstName: 'Shaima',
  lastName: 'Alkhateeb',
};
let job = {
  jobTitle: 'JavaScript Developer',
   location: 'Amman'
};
let employee  = {...person, ...job};`

(How to Pass Functions Between Components)

1. In the video, what is the first step that the developer does to pass functions between components?
--> create the function.
2. In your own words, what does the increment function do?
--> It increments the count of the name when we press the button
3. How can you pass a method from a parent component into a child component?
-In the parent component, create a callback function. This callback function will retrieve the data from the child component.
-Pass the callback function to the child as a props from the parent component.
-The child component calls the parent callback function using props and passes the data to the parent component.
4. How does the child component invoke a method that was passed to it from a parent component?

---

### Class 04 :

(React and Forms)

1. What is a ‘Controlled Component’?
--> is a component that renders form elements and controls them by keeping the form data in the component's state, and its can only updated with setState().
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
--> update the state with their responses as soon as they enter, I dont know.
3. How do we target what the user is entering if we have an event handler on an input field?
-->Because the handler runs on every keystroke to update the React state.

(The Conditional "Ternary" Operator Explained)

1. Why would we use a ternary operator?
--> Because it's short and simple compared with if else block.
2. Rewrite the following statement using a ternary statement:

`x===y ? console.log(true) : console.log(false);`

---

### Class 05 :

(React Docs - Thinking in React)

1. What is the single responsibility principle and how does it apply to components?
--> It means that any object in OOP should do one thing(one specific function).
2. What does it mean to build a ‘static’ version of your application?
--> That means you don't need the user to interact with your app.
3. Once you have a static application, what do you need to add?
--> Need to use props not state.
4. What are the three questions you can ask to determine if something is state?
--> Is the value need/going to change or not, If yes so Its state.
5. How can you identify where state needs to live?
--> After you drow, the UI and decide the name and number of components you need, then decide which one is props or state, so now you have a clear vision of your app, you can now diside where your state should live.  

(Higher-Order Functions)

1. What is a “higher-order function”?
--> Its 1)takes a function as a parameter or 2)returns a function
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

`function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true`

--> It's going to return true If the 11 > 10
3. Explain how either map or to reduce operates, with regards to higher-order functions.
--> Because it applies a given function to each element of a collection.

---

### Class 06 : NODE.JS

(An Introduction to Node.js on sitepoint.com)

1. What is node.js?
--> A runtime environment for executing JavaScript code outside the browser.
2. In your own words, what is Chrome’s V8 JavaScript Engine?
--> Its something that takes the JavaScript code that you write and executes it when you browse with Chrome, and the V8 is the JavaScript engine.
3. What does it mean that node is a JavaScript runtime?
--> It refers to where your javascript code is executed when you run it, and it means that Node. js wastes no time or resources on waiting for I/O requests to return.
4. What is npm?
-->is a package manager for Node. js packages, or modules.
5. What version of the node are you running on your machine?(node -v)
--> v16.15.1
6. What version of npm are you running on your machine?(npm -v)
--> 8.11.0
7. What command would you type to install a library/package called ‘jshint’?
npm install -g jshint
8. What is node used for?
--> It is used for developing applications that make heavy use of the ability to run JavaScript both on the client, as well as on the server side, and therefore benefit from the re-usability of code and the lack of context switching.

(6 Reasons for Pair Programming)

1. What are the 6 reasons for pair programming?
-Greater efficiency
-Engaged collaboration
-Learning from fellow students
-Social skills
-Job interview readiness
-Work environment readiness
2. In your experience, which of these reasons have you found most beneficial?
--> Greater efficiency
3. How does pair programming work?
--> One of them is Driver and the other one is Navigator.
The Driver is the only one typing on the keyboard, and the Navigator uses their words to guide the Driver, they think about the big picture like what comes next, and how an algorithm might be converted into code.

## Things I want to know more about

## 4. **Code 401** - Advanced Software Development
