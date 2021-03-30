**Monday-29/3/2021**

**This is what I learned in class 401_03:**

![Image of data model](https://i2.wp.com/www.complexsql.com/wp-content/uploads/2018/05/Data-Modeling.png?fit=555%2C340&ssl=1)

![Image of REST](https://miro.medium.com/max/1032/1*sPLooWMag11pjZnzYXIQCA.png)

* I learned the following:

  1. We used middlewares for the following reasons:
      -  Having the ability to send a PUT request.
      -  Having the ability to send a DELETE request.
      -  Having the ability to send a PATCH request.
  2.  True or false: The route handler is middleware?
    False, [Route handlers VS middleware](https://stackoverflow.com/questions/58925276/what-is-the-difference-between-a-route-handler-and-middleware-function-in-expres).

  3. In what ways can a middleware function end the process and send data to the browser?

      It will receive the request and if there is a response it will send it other than that there should be next();
  4. At what point in the request lifecycle can you “inject” middleware?
   
        When receiving the requests

  5. What can cause express to error with “Request headers sent twice, cannot start a second response” 
        
        Means that you're already in the Body or Finished state, but some function tried to set a header or statusCode. When you see this error, look for callbacks that are accidentally called twice, or any error that happens after the body is sent.

  6. **Middleware** functions are functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle.
  7. **Request Object**, is the object that sent when the client is requesting.
  8. **Response Object**, is the object that response when the client is requesting.
  9. **Application Middleware**, it's an application that uses middleware.
  10. **Routing Middleware** refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routing.
  11. **Test Driven Development (TDD)** it's a way of programming that starts with testing then writing the code.
  12. **Behavioural Testing** is a testing of the external behavior of the program, also known as black box testing. It is usually a functional testing.
  13. **Classes**, are special functions (blueprint), we use to initialize instances (objects).
  14. **Routing**, refers to how an application’s endpoints (URIs) respond to client requests.
    
          // GET method route
          app.get('/', function (req, res) {
          res.send('GET request to the homepage')
          })

          // POST method route
          app.post('/', function (req, res) {
          res.send('POST request to the homepage')
          })

  15.  **Express Router**, It is a mini express application without all the bells and whistles of an express application, just the routing stuff.

            // server.js

            ...

            // we'll create our routes here

            // get an instance of router
            var router = express.Router();

            // home page route (http://localhost:8080)
            router.get('/', function(req, res) {
                res.send('im the home page!');  
            });

            // about page route (http://localhost:8080/about)
            router.get('/about', function(req, res) {
                res.send('im the about page!'); 
            });

            // apply the routes to our application
            app.use('/', router);

            ...
