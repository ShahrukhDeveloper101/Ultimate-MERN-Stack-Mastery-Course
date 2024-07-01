Lecture 17: Introduction to CSS Grid

Introduction to CSS Grid:

Definition: CSS Grid Layout is a two-dimensional layout system for the web, allowing you to design web pages with rows and columns.
Importance: CSS Grid provides precise control over layout and alignment of elements, making it ideal for creating complex and responsive grid-based layouts.
Grid Container and Grid Items:

Grid Container:
Definition: The parent element where the display: grid; property is applied.
Example:

.container {
  display: grid;
}

Grid Items:
Definition: The child elements within a grid container that are laid out using rows and columns defined by the grid.

Grid Properties:

grid-template-rows:
Definition: Defines the height of each row in the grid.
Example:
 
.container {
  display: grid;
  grid-template-rows: 100px 200px;
}
grid-template-columns:
Definition: Defines the width of each column in the grid.
Example:

.container {
  display: grid;
  grid-template-columns: 1fr 2fr;
}

grid-gap:
Definition: Defines the size of the gap between rows and columns in the grid.
Example:

.container {
  display: grid;
  grid-gap: 10px;
}

Grid Item Properties:

grid-row-start, grid-row-end, grid-column-start, grid-column-end:
Definition: Specifies where a grid item starts and ends within the grid rows and columns.
Example:

.item {
  grid-row-start: 1;
  grid-row-end: 3;
  grid-column-start: 1;
  grid-column-end: 3;
}


Practical Examples:

Creating a Basic Grid Layout:

.container {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  grid-template-rows: 100px 200px;
  grid-gap: 10px;
}

Responsive Grid Layout:

.container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  grid-gap: 10px;
}
Exercises and Practice:

Exercise 1: Create a 3x3 grid layout with defined row and column sizes.
