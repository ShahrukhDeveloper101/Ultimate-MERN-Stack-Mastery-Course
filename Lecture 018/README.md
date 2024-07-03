Lecture 18: CSS Media Queries
1. Introduction to Media Queries
Definition: Media queries are a feature of CSS that allow you to apply styles based on the characteristics of the device rendering the content, such as its width, height, and orientation.

Importance: Media queries are essential for responsive web design, ensuring your website looks good on all devices, from desktops to tablets to mobile phones.

2. Basic Syntax
Example: 
@media (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
This media query applies the specified styles when the viewport width is 600 pixels or less.

3. Media Features
Width and Height: You can target specific widths and heights.
Example:
 
@media (min-width: 768px) {
  .container {
    width: 75%;
  }
}
Orientation: You can target landscape or portrait mode.
Example: 
@media (orientation: landscape) {
  body {
    background-color: lightgreen;
  }
}

4. Combining Media Queries
Using Multiple Features: Combine features for more specific targeting.
Example: 
@media (min-width: 600px) and (max-width: 1200px) {
  .container {
    width: 50%;
  }
}

5. Common Use Cases
Responsive Typography: Adjust font sizes for different screen sizes.
Example: 
@media (max-width: 600px) {
  h1 {
    font-size: 1.5em;
  }
}
@media (min-width: 601px) and (max-width: 1200px) {
  h1 {
    font-size: 2em;
  }
}
@media (min-width: 1201px) {
  h1 {
    font-size: 2.5em;
  }
}
Hiding and Showing Elements: Show or hide elements based on screen size.
Example: 
@media (max-width: 600px) {
  .sidebar {
    display: none;
  }
}

6. Exercises and Practice
Exercise 1: Create a responsive layout that adjusts the number of columns based on screen width.
 
 