# Redux Advance

### What is Redux Toolkit?
Redux Toolkit is our official, opinionated, batteries-included toolset for efficient Redux development. It is intended to be the standard way to write Redux logic, and we strongly recommend that you use it.


### What is the purpose of Redux Toolkit ?
 to be the standard way to write redux logic.
 
 
 ### What Toolkit includes ?
 It includes several utility functions that simplify the most common Redux use cases, including store setup, defining reducers, immutable update logic, and even creating entire "slices" of state at once without writing any action creators or action types by hand. It also includes the most widely used Redux addons, like Redux Thunk for async logic and Reselect for writing selector functions, so that you can use them right away.
 
 ### What is createSlice ?
 A function that accepts an initial state, an object of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state.
 
 ### What is createSlice in Redux Toolkit?
 createSlice is a higher order function that accepts an initial state, an object full of reducer functions and a slice name. It automatically generates action creators and action types that correspond to the reducers and state.
 
 In **Redux-Toolkit**, the **createSlice method** helps us create a slice of the redux-store. This function aims to reduce the boilerplate required to add data to redux in the canonical way. Internally, it uses **createAction** and **createReducer**.
 
 ### 
 
