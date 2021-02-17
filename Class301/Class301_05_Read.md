**Thursday-17/2/2021**

**This is what I learned in class 301_05:**

* I learned the following:

1. **Node.js** is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications
2. We need to follow the following steps to run the server:
   - First of all, we need to create a JavaScript file. Let's name it server.js:

      var http = require("http");

          http.createServer(function(request, response) {
          response.writeHead(200, {"Content-Type": "text/plain"});
          response.write("It's alive!");
            response.end();
          }).listen(3000);

    - The we run the server
            
            node server.js

3. Please follow the link for the rest of the steps, 
[Link](https://howtonode.org/deploy-blog-to-heroku) 

4. Heruko it's online service (cloud) with limited features to upload our project on it.




