# Class 09: Functional Programming

## (Functional Programming Concepts)

1. What is functional programming?
--> Is a programming paradigm - a style of building the structure and elements of computer programs - that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
2. What is a pure function and how do we know if something is a pure function?
--> It returns the same result if given the same arguments (it is also referred to as deterministic), also it does not cause any observable side effects
3. What are the benefits of a pure function?
--> They’re easier to reason about, easier to combine, easier to test, easier to debug, and easier to parallelize
4. What is immutability?
--> Data state cannot change after it’s created
5. What is Referential transparency?
-->means that given a function and an input value, you will always receive the same output, with another word you can take an expression in your program, and replace it with the result of that expression

## (Node JS Tutorial for Beginners #6 - Modules and require())

1. What is a module?
--> A module is a software component or part of a program that contains one or more routines. One or more independently developed modules make up a program.
2. What does the word ‘require’ do?
--> refers to a function that is used to import all the constructs exported using the module.
3. How do we bring another module into the file we are working in?
--> We need to require('./NAME OF MODULE FILE') in the global object, then export the part of the module we went it available for all the file
4. What do we have to do to make a module available?
1) `require('./NAME OF MODULE FILE')`
2) `module.exports = ......`
