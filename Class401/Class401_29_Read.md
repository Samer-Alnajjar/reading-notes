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

----------------------


## ARIA HTML:

ARIA defines semantics that can be applied to elements, with these divided into roles (defining a type of user interface element) and states and properties that are supported by a role. ... Addition of ARIA semantics only exposes extra information to a browser's accessibility API, and does not affect a page's DOM.

## Queries:

Queries are the methods that Testing Library gives you to find elements on the page. There are several types of queries ("get", "find", "query"); the difference between them is whether the query will throw an error if no element is found or if it will return a Promise and retry. Depending on what page content you are selecting, different queries may be more or less appropriate.

## Types of Queries:

- Single Elements
        

    - getBy...: Returns the matching node for a query, and throw a descriptive error if no elements match or if more than one match is found (use getAllBy instead if more than one element is expected).


    - queryBy...: Returns the matching node for a query, and return null if no elements match. This is useful for asserting an element that is not present. Throws an error if more than one match is found (use queryAllBy instead if this is OK).


    - findBy...: Returns a Promise which resolves when an element is found which matches the given query. The promise is rejected if no element is found or if more than one element is found after a default timeout of 1000ms. If you need to find more than one element, use findAllBy.


- Multiple Elements


    - getAllBy...: Returns an array of all matching nodes for a query, and throws an error if no elements match.


    - queryAllBy...: Returns an array of all matching nodes for a query, and return an empty array ([]) if no elements match.


    - findAllBy...: Returns a promise which resolves to an array of elements when any elements are found which match the given query. The promise is rejected if no elements are found after a default timeout of 1000ms.

  

[simple react router](https://blog.pshrmn.com/simple-react-router-v4-tutorial/)

[react router](https://reactrouter.com/web/api)
