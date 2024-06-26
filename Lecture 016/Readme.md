Lecture 16: Introduction to CSS Flexbox

1. Introduction to Flexbox:
Definition: Flexbox, or the Flexible Box Layout, is a layout model designed to provide a more efficient way to lay out, align, and distribute space among items in a container.

Importance: Flexbox simplifies complex layouts and is especially useful for responsive design. It offers powerful alignment capabilities and can adapt to various screen sizes and orientations.

2. Flex Container and Flex Items:
Flex Container:

Definition: The parent element where the display: flex; or display: inline-flex; property is applied.
Example:
 
.container {
  display: flex;
}

Flex Items:

Definition: The child elements within a flex container.
Example:
 
<div class="container">
  <div class="item">Item 1</div>
  <div class="item">Item 2</div>
  <div class="item">Item 3</div>
</div>

3. Flex Container Properties:

flex-direction:

Definition: Defines the direction of the flex items within the container.
Values: row, row-reverse, column, column-reverse
Example:
 
.container {
  flex-direction: row;
}

justify-content:

Definition: Aligns flex items along the main axis.
Values: flex-start, flex-end, center, space-between, space-around, space-evenly
Example:
 
.container {
  justify-content: space-between;
}
align-items:

Definition: Aligns flex items along the cross axis.
Values: flex-start, flex-end, center, baseline, stretch
Example:
 
.container {
  align-items: center;
}

flex-wrap:

Definition: Specifies whether flex items should wrap or not.
Values: nowrap, wrap, wrap-reverse
Example:
 
.container {
  flex-wrap: wrap;
}

align-content:

Definition: Aligns a flex container’s lines within the container when there is extra space in the cross-axis.
Values: flex-start, flex-end, center, space-between, space-around, stretch
Example:
 
.container {
  align-content: space-around;
}

4. Flex Item Properties:
order:

Definition: Specifies the order of a flex item relative to the other flex items.
Example:
 
.item {
  order: 2;
}
flex-grow:

Definition: Defines the ability for a flex item to grow if necessary.
Example:
 
.item {
  flex-grow: 1;
}

flex-basis:

Definition: Defines the default size of an element before the remaining space is distributed.
Example:
 
.item {
  flex-basis: 100px;
}
align-self:

Definition: Allows the default alignment (or the one specified by align-items) to be overridden for individual flex items.
Values: auto, flex-start, flex-end, center, baseline, stretch
Example:
 
.item {
  align-self: center;
}

5. Practical Examples:
Creating a Simple Flexbox Layout:

 
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
Responsive Navigation Bar:

 
.nav {
  display: flex;
  justify-content: space-around;
}
6. Exercises and Practice:

Exercise 1: Create a simple two-column layout using flexbox.
Exercise 2: Design a responsive header with flexbox.
 
