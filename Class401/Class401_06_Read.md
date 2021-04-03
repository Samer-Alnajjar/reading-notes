**Saturday-3/4/2021**

**This is what I learned in class 401_06:**

![Image of singleton](https://girlsincode.com/wp-content/uploads/2020/03/javascript-design-patterns-singleton-and-modules-500x534.jpeg)

![Image of dynamic modeling](https://miro.medium.com/max/760/1*BP6_vVHwGC6Q403DdIn2UQ.png)

![Image of dynamic modeling](https://www.ilantus.com/wp-content/uploads/2019/07/authentication-vs-authorization1-thegem-blog-default.png)

* I learned the following:

  1.  the **singleton** pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system.
  2.  We use singleton to make sure there is only one object instantiated.We can achieve this by refactoring our class to have:
      - hidden (private)constructor
      - public getInstance method that returns instance of the class 

  3. Singleton pattern with Node modules,
   
        - Create Singleton.js

         class PrivateSingleton {
          constructor() {
          this.message = 'I am an instance';
              }
          }
          class Singleton {
          constructor() {
          throw new Error('Use Singleton.getInstance()');
            }
            static getInstance() {
            if (!Singleton.instance) {
                Singleton.instance = new PrivateSingleton();
            }
            return Singleton.instance;
                }
              }
              module.exports = Singleton;

    - Create test.js


            const Singleton = require('./Singleton');
            const object = Singleton.getInstance(); 
            console.log(object.message);   // Prints out: 'I am an instance'
            object.message = 'Foo Bar';    // Overwrite message property
            const instance = Singleton.getInstance();
            console.log(instance.message); // Prints out: 'Foo Bar'

  4. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

      - Create a function that takes three arguments :
          - req
          - res
          - next
      - The req will indicate the data comming
      - The res will indicate the data responding.
      - and next will go to the next middleware.

-------------------------------
Vocabulary:

  - **Middleware** literally means anything you put in the middle of one layer of the software and another. Express middleware are functions that execute during the lifecycle of a request to the Express server. Each middleware has access to the HTTP request and response for each route (or path) it's attached to.
  - **Dynamic loading** is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.
  - **singleton pattern** is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.
  - **CRUD** It is an acronym for C - create, R - read/retrieve, U -update, D - delete- the four basic functions that are implemented in any relational DB applications. Each of it can map to a standard SQL statement, HTTP protocol method or Data Distribution Service (DDS).
  - **Mock testing** is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.

--------------------------
## preview

  1. Which 3 things had you heard about previously and now have better clarity on?

      - binary search
      - Next()
      - MVC

  2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

      - Middleware
      - Linked list
      - Mongo DB

----------------------
## Preparation Materials

1. Passwords are the first line of defense against cyber criminals.
- Cryptographic hash algorithms MD5, SHA1, SHA256, SHA512, SHA-3 are general purpose hash functions, designed to calculate a digest of huge amounts of data in as short a time as possible.
- Hashing is the greatest way for protecting passwords and considered to be pretty safe for ensuring the integrity of data or password.

- PROBLEMS WITH CRYPTOGRAPHIC HASH ALGORITHM
  
    - Brute Force attack: Hashes can't be reversed, so instead of reversing the hash of the password.

    - Hash Collision attack: Hash functions have infinite input length and a predefined output length, so there is inevitably going to be the possibility of two different inputs that produce the same output hash.

2.  **basic access authentication** is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.
3.  **Authentication** is the process of verifying that an individual, entity or website is whom it claims to be.
4.  **bcrypt.js**, is js library to help you hash the passwords.
