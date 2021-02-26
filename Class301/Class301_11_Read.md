**Thursday-26/2/2021**

**This is what I learned in class 301_11:**

![EJS](https://images.g2crowd.com/uploads/product/image/social_landscape/social_landscape_f9dd821cb48125c63c64b6f5c7552372/ejs.png)


* I learned the following:

1. **EJS**, Embedded JavaScript, it's a framework (templating language)that let you generate HTML markup using JS syntax.
2. The syntax to inject js into html **<%= %>**.
3. To install ejs:
     - npm install ejs
     - app.set('view engine', 'ejs')
     - then create the routes for your website.

4. EJS is mostly useful whenever you have to output HTML with a lot of javascript.
5. Google Books APIs,  is a way to search and access that content.
6. https://www.googleapis.com/auth/books
7. A sample of the response object:
   
   {
 "kind": "books#volume",
 "id": "zyTCAlFPjgYC",
 "etag": "f0zKg75Mx/I",
 "selfLink": "https://www.googleapis.com/books/v1/volumes/zyTCAlFPjgYC",
 "volumeInfo": {
  "title": "The Google story",
  "authors": [
   "David A. Vise",
   "Mark Malseed"
  ]

