Notes for Lecture 15: CSS Float, Clear, and Background Image Properties

1. Introduction to CSS Float:

Definition: The float property in CSS is used for positioning and formatting content on a web page. It allows elements to be taken out of the normal document flow and positioned to the left or right of their container. This causes the surrounding text and inline elements to wrap around the floated element.

Importance: Float is commonly used for creating layouts, particularly before the introduction of Flexbox and Grid. It was a popular method for designing web pages with multiple columns, floated images, and other complex layouts..

How Float Works:

  Floating Elements:

  When an element is floated, it is removed from the normal flow of the document and aligned to the left or right of its containing element.
  Other content, such as text and inline elements, will wrap around the floated element.

  Values of the Float Property:

  left: Floats the element to the left side of its container.
  right: Floats the element to the right side of its container.
  none: Default value; the element does not float.


2. Float Property Values:

left: The element floats to the left of its container.
 
<style>
  .float-left {
    float: left;
    background-color: lightblue;
    width: 50%;
  }
</style>
<div class="float-left">This is a left floated element.</div>
<p>This paragraph will wrap around the floated element.</p>

right: The element floats to the right of its container.
 
<style>
  .float-right {
    float: right;
    background-color: lightgreen;
    width: 50%;
  }
</style>

<div class="float-right">This is a right floated element.</div>
<p>This paragraph will wrap around the floated element.</p>

none: The element does not float (default).
<style>
  .no-float {
    float: none;
  }
</style>

<div class="no-float">This element is not floated.</div>

3. Using Float for Layouts:

Creating Multi-Column Layouts:
 
<style>
  .column {
    float: left;
    width: 50%;
    background-color: lightcoral;
    padding: 10px;
    box-sizing: border-box;
  }
</style>
<div class="column">Column 1</div>
<div class="column">Column 2</div>

Floating Images and Text Wrapping:
 
<style>
  .float-image {
    float: right;
    margin-left: 10px;
  }
</style>

<img src="https://via.placeholder.com/150" class="float-image" alt="Floating Image">
<p>This text will wrap around the floated image.</p>

4. The Clear Property:

Definition: The clear property specifies what elements can float beside the cleared element and on which side.
Using clear:
left: No floating elements allowed on the left side.
right: No floating elements allowed on the right side.
both: No floating elements allowed on either side.
 
<style>
  .clear-both {
    clear: both;
  }
</style>
<div class="float-left">Float Left</div>
<div class="float-right">Float Right</div>
<div class="clear-both">This element clears both floats.</div>

5. Background Image Properties:

background-image: Sets the background image for an element.
<style>
  .bg-image {
    background-image: url('https://via.placeholder.com/500');
  }
</style>
<div class="bg-image">This div has a background image.</div>

background-repeat: Controls the repetition of the background image.
<style>
  .bg-no-repeat {
    background-image: url('https://via.placeholder.com/150');
    background-repeat: no-repeat;
  }
</style>
<div class="bg-no-repeat">No-repeat background image.</div>

background-position: Specifies the position of the background image.
<style>
  .bg-position {
    background-image: url('https://via.placeholder.com/150');
    background-repeat: no-repeat;
    background-position: center;
  }
</style>
<div class="bg-position">Center-positioned background image.</div>

background-size: Specifies the size of the background image. 
<style>
  .bg-cover {
    background-image: url('https://via.placeholder.com/500');
    background-size: cover;
  }
</style>
<div class="bg-cover">Cover-sized background image.</div>

background-attachment: Controls whether the background image scrolls with the page or is fixed. 
<style>
  .bg-fixed {
    background-image: url('https://via.placeholder.com/500');
    background-attachment: fixed;
  }
</style>
<div class="bg-fixed">Fixed background image.</div>

6. Exercises and Practice:

Exercise 1: Create a two-column layout using float.
Exercise 2: Float an image to the right and wrap text around it.
Exercise 3: Add a background image with various properties.