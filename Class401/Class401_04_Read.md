**Tuesday-30/3/2021**

**This is what I learned in class 401_04:**

![Image of middleware](https://i2.wp.com/www.complexsql.com/wp-content/uploads/2018/05/Data-Modeling.png?fit=555%2C340&ssl=1)

![Image of Black Box](https://miro.medium.com/max/1032/1*sPLooWMag11pjZnzYXIQCA.png)

* I learned the following:

  1. 3 advantages to Test Driven Development:
      -  Better program design and higher code quality.
      -  Detailed project documentation.
      -  TDD reduces the time required for project development.
  2. **beforeEach** test is for each individual tests, and before the test is run.
  3. **afterEach** test is for each individual tests, and before the test is run.
  4. one downside of Test Driven Development is the slow process.
  5. What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
      
      in ES6 classes you don't have to call the parent class inside each child class like the using the prototype.

  6. It works because you're not tying your API to your client-side technology. You could imagine that this API is accessible from a client-side Web project, an iOS app, an IoT device and even a Windows Phone. This allows you to build the infrastructure for your organization with fewer worries about the longer-term marrying to a particular client-side stack. The server lives longer than the client. It always does.

  7. Why use REST?
  
      Because of **Caching**. Caching is important, as if multiple requests for the same resource are requested, caching of the result of the request means that the scalability of the server should increase.

  8. **functional programming**,  is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects
  9. **object-oriented programming (OOP)**, writing procedures or functions that perform operations on the data.
  10. **Class** is like a blueprint of objects that you want to create.
  11. **super** keyword is used to access and call functions on an object's parent.
  12. **this**, the value of this is determined by how a function is called (runtime binding)
  13. **Test Driven Development (TDD)** it's a way of programming that starts with testing then writing the code.
  14. **Jest**, is JS testing framework.
  15. **CI**, Continues Integration is a workflow to ensure everyone changes integrate to reduce bugs and conflicts.
  16. **REST** stands for Representational State Transfer, REST is an architectural pattern, REST uses Uniform Service locators to access to the components on the hardware device, it work with plain text, XML, HTML and JSON, REST can make use of SOAP.
  17.  **Data Model**, is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities.
  18. **SQL vs NoSQL:**

        1. SQL databases are relational, NoSQL are non-relational.
        2. SQL databases use structured query language and have a predefined schema. NoSQL databases have dynamic schemas for unstructured data.
        3. SQL databases are vertically scalable, NoSQL databases are horizontally scalable.
        4. SQL databases are table based, while NoSQL databases are document, key-value, graph or wide-column stores.
        5. SQL databases are better for multi-row transactions, NoSQL are better for unstructured data like documents or JSON.

  19. **NOSQL DATA MODELING TECHNIQUES:**

      - **Denormalization**:
            Denormalization can be defined as the copying of the same data into multiple documents or tables in order to simplify/optimize query processing or to fit the user’s data into a particular data model.
      - **Aggregates** :
      - **Application Side Joins**: Joins are rarely supported in NoSQL solutions. As a consequence of the “question-oriented” NoSQL nature, joins are often handled at design time as opposed to relational models where joins are handled at query execution time.
      - [Other resources](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/)
 