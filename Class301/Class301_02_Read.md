**Monday-15/2/2021**

**This is what I learned in class 203_02:**

* I learned the following:

1. jQuery is a JS library, and it's used because it let you do what you can do using DOM but with less code.
2. jQuery works, it creates a jQuery object and refer the object to the selected elements. ex: **$("p")**.
3. You can use different methods on jQuery objects, such as **$("li").addClass("test")**.
4. You can use jQuery by download the file locally or link it to your project using CDN.
5. There are two type of file for jQuery, the first with the extension **.min** which is abbreviation for minification(remove white spaces which will reduce the file size), and the normal one.

We can select element using jQuery by:
  - element name. **$("p")**
  - id. **$("#id")**
  - class. **$(".class")**

6. Also one the reasons why jQuery is easier, is that we don't have to loop for multiple elements, jQuery will do te job for us.
7. We can get the content using jQuery using two methods:
  - .html() - **Will return what inside the element inclusing the tags**
  - .text() - **Will return only the text inside the element**

8. We can insert elements using jQuery by using the following methods:
   - .before()
   - .after()
   - .prepend()
   - .append()

9. We can het and set attribute values using jQuery:
    - .attr()
    - .removeAttr()
    - .addClass()
    - .removeClass()

10. Also we can add events using jQuery
    - $("p").on("click",callback)

11. The benefits of pair programming is as following:
    - Greater efficiency
    - Engaged collaboration
    - Learning from fellow students
    - Social skills
    - Job interview readiness
    - Work environment readiness