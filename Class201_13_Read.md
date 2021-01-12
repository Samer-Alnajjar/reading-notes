**Tuesday-12/1/2020**

**This is what I learned in class 201_13:**

* I learned the following:

    1. In the early days web application was using cookies to store smal data, but there was some disadvantages of this:

        - Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
        - Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
        - Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

    2. Since HTML5 we were able to store data locally, HTML5 storage (web storage) it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies

    3. Before start storing data, you should check if your browser support it, by writing the following:

        - if (Modernizr.localstorage) {
        // window.localStorage is available!
        } else {
        // no native support for HTML5 storage :(
        // maybe try dojox.storage or a third-party solution
        }

    4. HTML5 Storage is based on      named key/value pairs.

    5. localStorage is an object like any other object in JS, it has two methods **.setItem()**, used to add data to the localStorage, **.getItem()** used to retreieve data from the local storage, **.clear()** used to clear the data from the local storage.