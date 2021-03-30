**Sunday-28/3/2021**

**This is what I learned in class 401_02:**

![Image of webserver](https://i0.wp.com/www.informationq.com/wp-content/uploads/2017/12/What-is-a-Web-Server.jpg?resize=2196%2C1476&ssl=1)

![Image of WRRC](https://image.slidesharecdn.com/inft132-09303webconcepts-090920164402-phpapp02/95/inft132-093-03-web-concepts-5-728.jpg?cb=1253465082)


* I learned the following:

  1. HTTP PUT, is used when we need to change a resource entirely.
  2. HTTP PATCH, is used we need change a resource partially.
  3. Three tools to mock API for development:
      - https://mockoon.com/
      - https://stoplight.io/mocking/
      - https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/

  4. Response from swagger:         
              
            '200':
            description: OK

            '400':
            description: Bad request. User ID must be an integer and larger than 0.

  5. Response from APIDoc.js 1:
             
            '200':
            Success 200
            
            HTTP/1.1 400 Bad Request
              {
                "error": "UserNameTooShort"
              }
  6. **SOAP** stands for Simple Object Access Protocol, it's a protocol, it uses service interfaces to expose its functionality to client applications, only works with XML formats, and SOAP cannot make use of REST.
  7. **REST** stands for Representational State Transfer, REST is an architectural pattern, REST uses Uniform Service locators to access to the components on the hardware device, it work with plain text, XML, HTML and JSON, REST can make use of SOAP.
  8. A **web server** is a computer that runs websites. It's a computer program that distributes web pages.
  9. **Express** is a JS framework, that provide features for web application.
  10. **Routing** is the process of selecting a path for traffic in a network or between or across multiple networks.
  11. **WRRC**, Web Request Response Cycle, it's the whole process, when a client request certain data from the server, and the response that responded from the server to the client.
  12. **Nodejs** is a JavaScript runtime built on Chrome's V8 JavaScript engine. which allow us to run JS code outside the browser.
  13. **TDD**, Test-driven development, it's a style of programming where we write the tests before the features themselves.
  14. **CI**, Continues Integration is a workflow to ensure everyone changes integrate to reduce bugs and conflicts.
  15. **CD**, Continues Delivery is the process of developing to release at any time.
  16. Continues Deployment, is the process of deploying new features immediately.  
  17. **Data Model**, is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities.
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