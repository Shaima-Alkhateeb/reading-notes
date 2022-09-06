# Class 03 : Passing Functions as Props

## (React Docs - lists and keys)

1. What does .map() return?
--> returns an entirely new array with transformed elements and the same amount of data.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?

```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((numbers) =>
 <li>{numbers}</li>
);
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<ul>{listItems}</ul>);
```

3. Each list item needs a unique key.
4. What is the purpose of a key?
--> to identify which items in the list are changed, updated, or deleted.

## (The Spread Operator)

1. What is the spread operator?
-->is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements.
2. List 4 things that the spread operator can do.
--> Copying an array, Using Math functions, Using an array as arguments, and Adding to state in React.
3. Give an example of using the spread operator to combine two arrays.

```
const numbers1 = [1, 2, 3, 4, 5];
const numbers2 = [6, 7, 8, 9, 10];
const numbers3 = [...numbers1, ...numbers2];
```

4. Give an example of using the spread operator to add a new item to an array.

```
const numbers = [1, 2, 3, 4, 5];
const add = [...numbers, 6];
```

5. Give an example of using the spread operator to combine two objects into one.

```
let person = {
  firstName: 'Shaima',
  lastName: 'Alkhateeb',
};
let job = {
  jobTitle: 'JavaScript Developer',
   location: 'Amman'
};
let employee  = {...person, ...job};
```

## (How to Pass Functions Between Components)

1. In the video, what is the first step that the developer does to pass functions between components?
--> create the function.
2. In your own words, what does the increment function do?
--> It increments the count of the name when we press the button
3. How can you pass a method from a parent component into a child component?
-In the parent component, create a callback function. This callback function will retrieve the data from the child component.
-Pass the callback function to the child as a props from the parent component.
-The child component calls the parent callback function using props and passes the data to the parent component.
4. How does the child component invoke a method that was passed to it from a parent component?
