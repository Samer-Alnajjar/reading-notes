**Tuesday-4/5/2021**

**This is what I learned in class 401_29:**

# Routing

![image](https://repository-images.githubusercontent.com/19872456/05dca500-f010-11e9-9588-a96554294e4e)


1. Do child components have direct access to props/state from the parent?

    Not direct access, but it can access it using props.

2. When a component “wraps” another component, how does the child component’s output get rendered?

    when adding the component as children. 

3. Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?

    Yes

4. What trick can a parent use to share all props with it’s children

    We can use spread operator

------------------------------------------------

## Vocabulary Terms

- **props.children**:used to display whatever you include between the opening and closing tags when invoking a component.
- **composition**: a development pattern based on React’s original component model where we build components from other components using explicit defined props or the implicit children prop.

-----------------------------------------------

## Preparation Materials

- React routing


- To build routing you need to install react-router, react-router-dom, and react-router-native.
- Determine which type of router to use, ig. <BrowserRouter> and <HashRouter>.
- Render router component in the App render function.
- React Router Component: - <Route path=''/>
<Switch>


[simple react router](https://blog.pshrmn.com/simple-react-router-v4-tutorial/)

[react router](https://reactrouter.com/web/api)
