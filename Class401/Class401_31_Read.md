**Friday-7/5/2021**

**This is what I learned in class 401_30:**

# Routing

![image](https://miro.medium.com/max/3000/1*-Ijet6kVJqGgul6adezDLQ.png)


1. Why do we not need more .html pages in a multi-page React app?

Because of react-route-dom library, which will allow us to have multiple routes and on each route we can render component.

2. If we wanted a component to show up on every page, where would we put it and why?

Inside the ```<BrowserRouter />```, outside a ```<Route />```.

3. What does props.children contain?

used to display whatever you include between the opening and closing tags when invoking a component.

---------------------------------------------

## Vocabulary Terms

1. **Composition**: React Composition is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop.
2. **Child Components**: The children, in React, refer to the generic box whose contents are unknown until they're passed from the parent component. What does this mean? It simply means that the component will display whatever is included in between the opening and closing tags while invoking the component.
3. **Hash Routing**: Hash value will be handled by react router. It is used to support legacy browsers which usually doesn't support HTML pushState API, It doesn't need any configuration in server to handle routes, This route isn't recommended by the team who created react router package.
4. **Link Rounting**: It is a dynamic routing algorithm in which each router shares knowledge of its neighbors with every other router in the network.

------------------------------------------------

## Preparation Materials

- **Hooks:** Hooks are the new feature introduced in the React 16.8 version. It allows you to use state and other React features without writing a class. Hooks are the functions which "hook into" React state and lifecycle features from function components. It does not work inside classes.

- Hooks are backward-compatible, which means it does not contain any breaking changes. Also, it does not replace your knowledge of React concepts.

- If you write a function component, and then you want to add some state to it, previously you do this by converting it to a class. But, now you can do it by using a Hook inside the existing function component.

- Rules of Hooks:
  - Only call Hooks at the top level.
  - Only call Hooks from React functions.

- Pre-requisites for React Hooks
  - Node version 6 or above
  - NPM version 5.2 or above

- We need hooks when we can't break a complex UI to the first level.
- Hooks apply the React philosophy (explicit data flow and composition) inside a component, rather than just between the components.
-  useState is a Hook (we’ll talk about what this means in a moment)
-  The only argument to useState is the initial state.The initial state argument is only used during the first render.
- useState return a pair of values: the current state and a function that updates it.
- useEffect do tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API.
- We use useEffect after every render.
