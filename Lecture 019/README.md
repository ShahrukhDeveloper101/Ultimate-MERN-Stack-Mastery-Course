Lecture 19: CSS Transitions  
1. Introduction to CSS Transitions:
Definition: CSS transitions allow you to change property values smoothly (over a given duration).
Importance: Enhances user experience by adding smooth visual feedback and dynamic effects.

2. Properties of CSS Transitions:
transition-property:
Definition: Specifies the CSS property to which the transition is applied.
Example:
.box {
  transition-property: background-color;
}

transition-duration:
Definition: Specifies the duration of the transition.
Example:
.box {
  transition-duration: 2s;
}

transition-timing-function:
Definition: Specifies the speed curve of the transition.
Values: ease, linear, ease-in, ease-out, ease-in-out, cubic-bezier(n,n,n,n)
ease: This is the default timing function. It starts slow, accelerates, and then slows down again before ending.

ease-in: This timing function starts slow and then speeds up.

ease-out: This timing function starts fast and then slows down.

ease-in-out: This timing function starts slow, speeds up in the middle, and then slows down again towards the end.

linear: This timing function has a constant speed from start to finish.

cubic-bezier(n,n,n,n): This allows you to create a custom timing function by defining your own cubic Bezier curve. The four values represent points in a cubic Bezier curve.

Example:
.box {
  transition-timing-function: ease-in-out;
}

transition-delay:
Definition: Specifies the delay before the transition starts.
Example:
.box {
  transition-delay: 1s;
}

3. Applying Multiple Transitions:
Example:
.box {
  transition: background-color 2s ease-in-out, transform 1s;
}

4. Practical Example of CSS Transitions:
Example:
.box {
  width: 100px;
  height: 100px;
  background-color: blue;
  transition: background-color 2s, transform 2s;
}
.box:hover {
  background-color: red;
  transform: rotate(45deg);
}


 
