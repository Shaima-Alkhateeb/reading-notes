# Class 10: In memory storage

## (Understanding the JavaScript Call Stack)

1. What is a ‘call’?
--> is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function
2. How many ‘calls’ can happen at once?
--> One
3. What does LIFO mean?
--> "Last In, First Out", principle to temporarily store and manage function invocation (call)
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
![call stack](https://miro.medium.com/max/1838/1*NHvc4BArOnXfo7Afg6LFMg.png)
5. What causes a Stack Overflow?
--> occurs when there is a recursive function (a function that calls itself) without an exit point.

## (JavaScript error messages)

1. What is a ‘reference error’?
--> It happens when you try to use a variable that is not yet declared
2. What is a ‘syntax error’?
--> occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
3. What is a ‘range error’?
-->It happens when you are trying to manipulate an object with some kind of length and give it an invalid length
4. What is a ‘type error’?
--> It shows up when the types (number, string, and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
5. What is a breakpoint?
--> It's putting a debugger statement in your code in the line you want to break.
6. What does the word ‘debugger’ do in your code?
--> Once you run the code you can see the “history” before reaching that breakpoint.