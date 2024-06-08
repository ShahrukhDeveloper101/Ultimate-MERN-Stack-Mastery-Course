1. What is CSS?

Definition:
CSS (Cascading Style Sheets) is a language used to describe the presentation of a document written in HTML or XML.
It controls the layout of multiple web pages all at once.

Purpose of CSS:
Web pages ki look aur feel ko behtar banata hai.
Layout par flexibility aur control deta hai.

2. Basic Syntax and Structure

CSS Syntax:
A CSS rule consists of a selector and a declaration block.

selector {
  property: value;
}

Selectors:
Identifies which HTML elements to style.

Properties and Values:
Property: The aspect of the element to style (e.g., color, font-size).
Value: The specification for the property (e.g., red, 16px).

3. Including CSS in HTML

a. Inline Styles:
CSS code is added directly to an HTML element using the style attribute.

<!-- yah ham tab use karain gy jab ham na kuch hi line ka code likhna ha -->
<h1 style="color: red;">
    This is a heading
</h1>

<!-- yah ham tab use karain gy jab ham na properties tu beshak zyda use krni ha but elements bht thura sa ha hamra pass -->
b. Internal Styles:
CSS code is placed within a <style> tag in the HTML document's <head>.
 
<head>

  <style>
    h1 {
      color: blue;
    }
  </style>

</head>

c. External Styles:
CSS code is written in a separate file with a .css extension and linked to the HTML document.

 
<head>
    <!-- both work same -->
  <link rel="stylesheet" type="text/css" href="styles.css">
  <link rel="stylesheet" href="styles.css">
</head>

 
h1 {
  color: blue;
}