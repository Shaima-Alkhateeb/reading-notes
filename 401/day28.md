# Redux

> ### What is Redux and why it is used?

Redux is a predictable state container designed to help you write JavaScript apps that behave consistently across client, server, and native environments, and are easy to test. While it's mostly used as a state management tool with React, you can use it with any other JavaScript framework or library.


#### Installation:
```
npm install @reduxjs/toolkit
```

> #### PROS:
1. Predictable state changes
2. Centralized state
3. Easy debugging
4. Preserve page state
5. Undo/redo
6. Ecosystem of add-ons

> #### CONS:
1. Complexity
2. Verbosity

> #### Should You Use Redux?

Redux is a valuable tool for organizing your state, but you should also consider whether it's appropriate for your situation. **Don't use Redux just because someone said you should - take some time to understand the potential benefits and tradeoffs of using it.**

Here are some suggestions on when it makes sense to use Redux:

- You have reasonable amounts of data changing over time

- You need a single source of truth for your state

- You find that keeping all your state in a top-level component is no longer sufficient
