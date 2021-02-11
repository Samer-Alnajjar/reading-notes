**Monday-11/1/2020**

**This is what I learned in class 201_12:**

* I learned the following:

    1. I learned how to create charts easily using **Chart.js**.
    2. We can draw diffrent types of charts, such as :
        - Line chart:
        
          in html:
          canvas id="buyers" width="600" height="400">canvas
        - Pie chart

            in html:
            canvas id="countries" width="600" height="400">canvas
        - Bar chart

            in html:
            canvas id="income" width="600" height="400">canvas

        and of course we need to add some code in the dcript tag, please follow this link to know which tag to use.
            [ link](https://www.chartjs.org/docs/latest/)
    3. Canvas element is used to draw in the browser.

    4. We also can use Canvas to draw diffrent shapes such as triangles and rectangles.

        example:

            function draw() {
            var canvas = document.getElementById('canvas');
            if (canvas.getContext) {
            var ctx = canvas.getContext('2d');

            ctx.fillRect(25, 25, 100, 100);
            ctx.clearRect(45, 45, 60, 60);
            ctx.strokeRect(50, 50, 50, 50);
            }
            }


    5. Also, we can use ti style the text

        example:

            ctx.font = '48px serif';
            ctx.textBaseline = 'hanging';
            ctx.strokeText('Hello world', 0, 100);


        