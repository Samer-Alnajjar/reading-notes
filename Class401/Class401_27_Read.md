**Monday-3/5/2021**

**This is what I learned in class 401_27:**

# Props and State

![image](https://miro.medium.com/max/3840/1*yjH3SiDaVWtpBX0g_2q68g.png)

![image](https://scriptverse.academy/img/tutorials/reactjs-components-props.png)


1. Does a deployed React application require a server?

You don't necessarily need a static server in order to run a Create React App project in production. It also works well when integrated into an existing server side app.

2. Why do we prefer to test a React application at the behavior rather than the unit level?

When it comes to React components you want to check how your component is rendered and if all props you pass to the component influence the behavior of your component as expected.

3. What does npm run build do?

npm run build creates a build directory with a production build of your app.

4. Describe the actual composition / architecture of a React application

Unlike other UI libraries and frameworks, Reactjs doesn’t enforce an architecture pattern. It is just a view that caters to the user interface. Just beneath the user interface lies a tree of several React components.

-----------------------------------

## Vocabulary Terms



**BDD**:	behavior driven development: Agile software development process that encourages collaboration among developers, QA and non-technical or business participants in a software project.

**Acceptance Tests**:	conducted to determine if the requirements of a specification or contract are met
mounting.	

**Mounting**: is the process of outputting the virtual representation of a component into the final UI representation (e.g. DOM or Native Components). In a browser that would mean outputting a React Element into an actual DOM element (e.g. an HTML div or li element) in the DOM tree. In a native application that would mean outputting a React element into a native component.

**build**:	the process of converting source code into an “executable” bundle by the browser.


-------------------------------

## State

The state is an updatable structure that is used to contain data or information about the component and can change over time. The change in state can happen as a response to user action or system event. It is the heart of the react component which determines the behavior of the component and how it will render. A state must be kept as simple as possible. It represents the component's local state or information. It can only be accessed or modified inside the component or by the component directly.

## Props

Props are read-only components. It is an object which stores the value of attributes of a tag and work similar to the HTML attributes. It allows passing data from one component to other components. It is similar to function arguments and can be passed to the component the same way as arguments passed in a function. Props are immutable so we cannot modify the props from inside the component.

## SetState

- Update to a component state should be done using setState().

- You can pass an object or a function to setState().
  
- Pass a function when you can to update state multiple times.
  
- Do not depend on this.state immediately after calling setState() and make use of the updater function instead.

## Handling Events

Handling events with React elements is  similar to handling events on DOM elements. There are some syntax differences:

- React events are named using camelCase, rather than lowercase.

- With JSX you pass a function as the event handler, rather than a string.

## Form

HTML form elements work a little bit differently from other DOM elements in React, because form elements naturally keep some internal state.

## React Testing Library

React Testing Library builds on top of DOM Testing Library by adding APIs for working with React components.

