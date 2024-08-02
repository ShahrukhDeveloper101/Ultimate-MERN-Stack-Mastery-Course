Documentation for Bootstrap Buttons:

Overview
Bootstrap Buttons are used to trigger actions in web applications. They come in various styles and sizes, and you can customize them easily with predefined classes.

Creating Buttons
To create a button, use the .btn class along with contextual classes like .btn-primary, .btn-secondary, .btn-success, .btn-danger, .btn-warning, .btn-info, .btn-light, and .btn-dark.

<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-light">Light</button>
<button type="button" class="btn btn-dark">Dark</button>



Button Sizes
You can adjust the size of buttons using the .btn-lg for large buttons and .btn-sm for small buttons.

<button type="button" class="btn btn-primary btn-lg">Large button</button>
<button type="button" class="btn btn-secondary btn-lg">Large button</button>

<button type="button" class="btn btn-primary btn-sm">Small button</button>
<button type="button" class="btn btn-secondary btn-sm">Small button</button>



Button States
Buttons can have different states like active and disabled.

<button type="button" class="btn btn-primary active">Active Button</button>
<button type="button" class="btn btn-secondary" disabled>Disabled Button</button>



Documentation for Bootstrap Button Groups:

Overview
Button Groups allow you to group a series of buttons together on a single line. This is useful for forms, navigation, and other interactive elements.

Creating Button Groups
To create a button group, wrap a series of buttons in a <div> with the class .btn-group.


<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-secondary">Left</button>
  <button type="button" class="btn btn-secondary">Middle</button>
  <button type="button" class="btn btn-secondary">Right</button>
</div>


Vertical Button Groups
You can create vertical button groups by adding the .btn-group-vertical class.

<div class="btn-group-vertical" role="group" aria-label="Vertical button group">
  <button type="button" class="btn btn-secondary">Button 1</button>
  <button type="button" class="btn btn-secondary">Button 2</button>
  <button type="button" class="btn btn-secondary">Button 3</button>
</div>


Documentation for Bootstrap Cards:
Overview
Bootstrap Cards provide a flexible and extensible content container with multiple variants and options. They can include a variety of content types like text, images, links, and more.

Creating a Basic Card
To create a basic card, use the .card class along with the .card-body class for the card content.

<div class="card" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="card-link">Card link</a>
    <a href="#" class="card-link">Another link</a>
  </div>
</div>

Card Images
You can add images to cards using the .card-img-top or .card-img-bottom class.

<div class="card" style="width: 18rem;">
  <img src="https://www.imgacademy.com/sites/default/files/styles/scale_1700w/public/2022-07/img-homepage-meta_0.jpg?itok=LMirU0Ik" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
