# Reading Notes 📚

This web site is a document and highlight my new knowledge.

## 1. **Code 102** - Intro to Software Development

## 2. **Code 201** - Foundations of Software Development

## 3. **Code 301** - Intermediate Software Development

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
x===y ? console.log(true) : console.log(false);

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
function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true
--> It's going to return true If the 11 > 10
3. Explain how either map or to reduce operates, with regards to higher-order functions.
--> Because it applies a given function to each element of a collection.

## Things I want to know more about

## 4. **Code 401** - Advanced Software Development
