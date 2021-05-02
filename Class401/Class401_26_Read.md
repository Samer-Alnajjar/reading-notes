**Sunday-2/5/2021**

**This is what I learned in class 401_26:**

# Component Based UI

![image](https://miro.medium.com/max/3840/1*yjH3SiDaVWtpBX0g_2q68g.png)



1. Name 5 Javascript UI Frameworks (other than React)

  - Angular
  - Vue.js
  - jQuery
  - Express
  - Bootstrap

2. What’s the difference between a framework and a library?

The technical difference between a framework and library lies in a term called inversion of control. When you use a library, you are in charge of the flow of the application. You are choosing when and where to call the library. When you use a framework, the framework is in charge of the flow.

----------------------------------------------

# Vocabulary Terms

- **Rendering**: Rendering refers to showing the output in the browser. The DOM establishes parent-child relationships, and adjacent sibling relationships, among the various elements in the HTML file.
- **Templates**: The template is HTML markup, peppered with tags that will either insert variables or run programming logic.
- **State**: State is a JavaScript object that stores component's dynamic data and it enables a component to keep track of changes between renders. Because state is dynamic, it is reserved only for interactivity so you don't use it for static React projects. Components defined as classes have some additional features.

-------------------------------------------------

- An example of React:
    ```
      ReactDOM.render(
      <h1>Hello, world!</h1>,
      document.getElementById('root')
      );
    ```

- JSX syntax
    ```
    const element = <h1>Hello, world!</h1>;
    ```

- React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

- Embedding Expressions in JSX:

    ```
    const name = 'Josh Perez';
    const element = <h1>Hello, {name}</h1>;

    ReactDOM.render(
    element,
    document.getElementById('root')
    );
    ```
- **Sass** is the most mature, stable, and powerful professional grade CSS extension language in the world.
    