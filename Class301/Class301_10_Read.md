**Thursday-25/2/2021**

**This is what I learned in class 301_10:**

![Functional Programming](https://res.cloudinary.com/practicaldev/image/fetch/s--YdnYpB3u--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://thepracticaldev.s3.amazonaws.com/i/nty82qv6m2sdjdwla7ue.png)


* I learned the following:

1. A **call stack** is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions.
2. We start with an empty Call Stack. Whenever we invoke a function, it is automatically added to the Call Stack. Once the function has executed all of its code, it is automatically removed from the Call Stack. Ultimately, the Stack is empty again.
3. A call stack is a data structure that uses the Last In, First Out (LIFO).
4. the most important information:
    - It is single-threaded. Meaning it can only do one thing at a time.
    - Code execution is synchronous.
    - A function invocation creates a stack frame that occupies a temporary memory.
    - It works as a LIFO — Last In, First Out data structure.


**Error**
  - **Reference errors**:This occurs to use a variable that is not yet declared you get this type os errors.
  - **Syntax errors**:This occurs when you mistypes a command syntax, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
  - **Range errors**:When you provide invalid length.
  - **Type errors**: Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.


**Debugging**
The way we use debugging is to console.log where I need to check the data coming from something.