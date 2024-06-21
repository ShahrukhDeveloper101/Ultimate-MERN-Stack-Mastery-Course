Notes for Lecture 14: CSS Positioning

1. Introduction to CSS Positioning:

Definition: The position property specifies the type of positioning method used for an element.
Importance: Understanding positioning is crucial for creating complex layouts and controlling the exact placement of elements on a webpage.

2. Types of Positioning:
Static Positioning:
Definition: Default positioning method; elements are positioned according to the normal document flow.
Example:
<style>
  .static {
    position: static;
    background-color: lightblue;
  }
</style>
<div class="static">Static Positioning</div>

Relative Positioning:
Definition: Element is positioned relative to its normal position.
Example:
<style>
  .relative {
    position: relative;
    top: 20px;
    left: 20px;
    background-color: lightgreen;
  }
</style>
<div class="relative">Relative Positioning</div>

Absolute Positioning:
Definition: Element is positioned relative to its nearest positioned ancestor or initial containing block.
Example:
<style>
  .container {
    position: relative;
    background-color: lightcoral;
    height: 200px;
  }
  .absolute {
    position: absolute;
    top: 50px;
    left: 50px;
    background-color: lightgoldenrodyellow;
  }
</style>
<div class="container">
  <div class="absolute">Absolute Positioning</div>
</div>

Fixed Positioning:
Definition: Element is positioned relative to the viewport, meaning it stays in the same place even when the page is scrolled.
Example:
<style>
  .fixed {
    position: fixed;
    bottom: 10px;
    right: 10px;
    background-color: lightpink;
  }
</style>
<div class="fixed">Fixed Positioning</div>

Sticky Positioning:
Definition: Element is treated as relative until it crosses a specified threshold, then it is treated as fixed.
Example:
<style>
  .sticky {
    position: -webkit-sticky; /* For Safari */
    position: sticky;
    top: 0;
    background-color: lightcyan;
  }
</style>
<div class="sticky">Sticky Positioning</div>

3. Combining Positioning Types:
Example:
<style>
  .relative-container {
    position: relative;
    height: 200px;
    background-color: lightcoral;
  }
  .absolute-inside-relative {
    position: absolute;
    bottom: 10px;
    right: 10px;
    background-color: lightgoldenrodyellow;
  }
</style>
<div class="relative-container">
  <div class="absolute-inside-relative">Absolute inside Relative</div>
</div>

4. Exercises and Practice:
Exercise 1: Create a layout using relative and absolute positioning.
Exercise 2: Implement a fixed header that stays at the top of the page when scrolling.
Exercise 3: Use sticky positioning to keep an element in view within its parent container.