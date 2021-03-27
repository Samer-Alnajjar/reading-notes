**Saturday-27/3/2021**

**This is what I learned in class 401_01:**

![Image of Async](https://bs-uploads.toptal.io/blackfish-uploads/uploaded_file/file/190741/image-1582215000590-ffa807c19d5f6959de485fc66664e123.png)

![Image of Async](https://www.30secondsofcode.org/assets/blog_images/js-array-methods.png)


* I learned the following:

  1. Array.map(),Creates a new array with the results of calling a callback function on every element in the array.
  2. Array.reduce(),Executes a reducer function on each element of the array, resulting in a single value.
  3. Difference between await / async and then using superagent:
       - async function getCity() {
        
          let data = await superagent.get("https://geocode.xyz/seattle?json=1");

          console.log(data.body);
        }

          getCity();
       - function getCity() {
        superagent("https://geocode.xyz/seattle?json=1")
        .then(data => {
          console.log(data.body);
        })
      }

  4. A promise, is like what it means, it's like I promise I do something, if I did it then the promise is "resolved", if I didn't do it then the promise is "rejected", so we use promises for requesting data from another server or when contacting with a database.
  5. Are all callback functions considered to be Asynchronous?
  No, not all of them.
  
      Why or Why Not?

      Because most of times we need a function to be sync which means we need to implement the callback function as soon as it's called, such as array methods, map, forEach, etc... and sometimes we need the callback to be async when communicating with another server.
