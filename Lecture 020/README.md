Lecture 19: CSS Animations
1. Introduction to CSS Animations:
Definition: CSS animations allow you to create multiple keyframes, specifying intermediate points along the animation sequence.
Importance: They enable complex animations without the need for JavaScript.

2. Keyframes in CSS Animations:
Definition: Define the intermediate steps in an animation sequence.
Example:
@keyframes example2 {
  from {
    background-color: red;
  }
  to {
    background-color: yellow;
  }
}

3. Applying CSS Animations:
animation-name:
Definition: Specifies the name of the @keyframes animation.
Example:
.box {
  animation-name: example;
}

animation-duration:
Definition: Specifies the duration of the animation.
Example:
.box {
  animation-duration: 4s;
}

4. Other Animation Properties:
animation-timing-function:
Definition: Specifies the speed curve of the animation.
Example:
.box {
  animation-timing-function: ease-in-out;
}
Values: ease, linear, ease-in, ease-out, ease-in-out, cubic-bezier(n,n,n,n)
ease: This is the default timing function. It starts slow, accelerates, and then slows down again before ending.

ease-in: This timing function starts slow and then speeds up.

ease-out: This timing function starts fast and then slows down.

ease-in-out: This timing function starts slow, speeds up in the middle, and then slows down again towards the end.

linear: This timing function has a constant speed from start to finish.

cubic-bezier(n,n,n,n): This allows you to create a custom timing function by defining your own cubic Bezier curve. The four values represent points in a cubic Bezier curve.

animation-delay:
Definition: Specifies a delay before the animation starts.
Example:
.box {
  animation-delay: 2s;
}

animation-iteration-count:
Definition: Specifies the number of times the animation should be played.
Example:
.box {
  animation-iteration-count: infinite;
}

animation-direction:
Definition: Specifies whether the animation should play in reverse on alternate cycles.
Example:
.box {
  animation-direction: alternate;
}


5. Practical Example of CSS Animations:
Example:
.box {
  position: absolute;
  animation-name: example;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}
@keyframes example {
  0%   {background-color: red; left: 0px; top: 0px;}
  25%  {background-color: yellow; left: 200px; top: 0px;}
  50%  {background-color: blue; left: 200px; top: 200px;}
  75%  {background-color: green; left: 0px; top: 200px;}
  100% {background-color: red; left: 0px; top: 0px;}
}
