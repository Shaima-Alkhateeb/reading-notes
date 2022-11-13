# Chakra UI

### What is a Chakra UI?

 its a component-based library. It's made up of basic building blocks that can help you build the front-end of your web application. It is customizable and reusable, and most importantly it supports ReactJs, along with some other libraries too.

### Is Chakra UI better than material UI?

Material UI is much better when it comes to performance and reliability. Chakra UI is not bad in terms of performance, but it can lag a bit on data-heavy, large-enterprise websites.


### How to use Chakra UI?

1. Wrap your application with the ChakraProvider provided by @chakra-ui/react.
```
import { ChakraProvider } from "@chakra-ui/react"

// Do this at the root of your application
function App({ children }) {
  return <ChakraProvider>{children}</ChakraProvider>
}
```
Optionally, you can wrap your application with the ColorModeProvider so you can toggle between light and dark mode within your app.

2. Now you can start using components like so!:
```
import { Button } from "@chakra-ui/react"

function Example() {
  return <Button>I just consumed some ⚡️Chakra!</Button>
}
```
