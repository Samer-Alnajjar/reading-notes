**Sunday-3/1/2020**

**This is what I learned in class 201_06:**

* I learned the following:

    1. The browser convert a model of the page and that called DOM tree.
    2. There are many methods to select and create element node in DOM, such as: getElementByTagName(), createElement(), etc...
        - An example of creating a h1 tage:
        document.createElement("h1");

        - An example of selecting a h1 tage:
        document.getElementByTagName("h1");
    3. To repeat actions for the same   node we use for loop.
        - An example for that:
        
            for(let i=0; i<length; i++) {
                var li = document.createElement("li");
                ul.append(li);
            
            }

    4. Also I learned about a new type of data similar to array, it's objects they like a container that we can store anything inside them, and every array is an object but not evey object is an array.

        - example:
        var objectDemo = {
            propertyOne: valueOne,
            propertyTwo: valueTwo
        }