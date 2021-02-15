**Tuesday-16/2/2021**

**This is what I learned in class 203_03:**

* I learned the following:

1. Flexbox css, is new feature added to css, to make it easier to make the website responsive.
2. Why "flex"? Flexbox allows us to distribute space dynamically across elements of an unknown size, hence the term "flex".
3. We need to add the property "display:flex".
4. Flex works in two axis main axis and cross axis.
5. "justify-content", which we can control how the content is distributed across the main axis (The default is "flex-start").
6. "flex-wrap", Which determines whether the element are going to wrap along the main axis onto a new line (The default is "nowrap").
7. "align-items", which we can control how the content is distributed across the cross axis (The default is "flex-start").
8. "align-content". Which we use to control or distribute space along the cross axis, but only when we have multiple rows or columns (It's only useful when we have flex-wrap).
9. "align-self", Which is the same as align-items except we use it for a single element
10. There are flex sizing properties:
  - "flex-basis", Which defines the initial size of an element before additional space is distributed
  - "flex-grow", Which controls the amount of available space an element should take up. (accepts a unit-less number value(proportional))
  - "flex-shrink", if items are larger than the container, they shrink according to flex-shrink. (accepts a unit-less number value(proportional))
  - since we use the flex sizing properties all the time there is a flex shorthand, flex: flex-grow | flex-shrink | flex-basis