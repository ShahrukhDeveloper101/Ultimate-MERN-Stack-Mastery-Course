Pseudo-Classes and Pseudo-Elements in CSS


1- Pseudo-Classes



:hover: Changes the color of a link when the mouse hovers over it.
a:hover {
  color: red;
}



:active: Changes the background color of a button when it is clicked.
button:active {
  background-color: yellow;
}




:focus: Changes the border color of an input field when it is focused.
input:focus {
  border-color: blue;
}




:nth-child(n): Selects the nth child of its parent.
  <ul>
    <li>First item</li>
    <li>Second item (This will have a light blue background)</li>
    <li>Third item</li>
    <li>Fourth item</li>
  </ul>
li:nth-child(2) {
  background-color: lightblue;
}

The CSS rule li:nth-child(2) selects the second <li> element within its parent <ul> element.






:first-child: Selects the first child of its parent.
<div>
    <p>This is the first paragraph inside a div.</p>
    <p>This is the second paragraph inside a div.</p>
    <p>This is the third paragraph inside a div. It will be italic.</p> <!-- This paragraph will be italic -->
  </div>
 
p:first-child {
  font-weight: bold;
}

The CSS rule p:first-child selects the first <p> element of its parent.



:last-child: Selects the last child of its parent. 
 <div>
    <p>This is the first paragraph inside a div.</p>
    <p>This is the second paragraph inside a div.</p>
    <p>This is the third paragraph inside a div. It will be italic.</p> <!-- This paragraph will be italic -->
  </div>

p:last-child {
  font-style: italic;
}
The CSS rule p:last-child selects the last <p> element of its parent.





:nth-of-type(n): Selects the nth child of its type.

  <p>This is the first paragraph of type 'p'.</p>
  <div>
    <p>This is the first paragraph inside a div.</p>
    <p>This is the second paragraph inside a div. It will be green.</p>
    <p>This is the third paragraph inside a div.</p>
    <div>
        <p>this is first para</p>
        <p>this is second para</p>
    </div>
  </div>
  <p>This is the second paragraph of type 'p'. It will be green.</p>
  <p>This is the third paragraph of type 'p'.</p>
  
p:nth-of-type(2) {
  color: green;
}





:not(selector): Selects elements that do not match the selector.
This rule will apply the color: gray; style to all <p> elements that do not have the class intro.

<p>This paragraph will be gray.</p>
<p class="intro">This paragraph will not be affected.</p>
<p>Another paragraph that will be gray.</p>

p:not(.intro) {
  color: gray;
}

Only the first and third <p> elements will have the color: gray; style applied to them, as they do not have the class intro. The second <p> element with the class intro will not be affected by this rule.




2- Pseudo-Elements


::before: Inserts content before an element.
p::before {
  content: "Note: ";
  font-weight: bold;
  color: red;
}



::after: Inserts content after an element.
p::after {
  content: " [End]";
  font-weight: bold;
  color: blue;
}


::first-letter: Styles the first letter of an element.
p::first-letter {
  font-size: 2em;
  color: purple;
}


::first-line: Styles the first line of an element. 
p::first-line {
  font-weight: bold;
}


::selection: Styles the part of an element that is selected by a user.
::selection {
  background-color: yellow;
  color: black;
}