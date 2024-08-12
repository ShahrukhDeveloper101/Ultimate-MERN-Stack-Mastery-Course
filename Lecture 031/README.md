1. Documentation for Bootstrap Popover
Overview
The Bootstrap Popover is a powerful component that can be used to show additional content when hovering or clicking on an element. It's an excellent tool for providing context or extra information.

Creating a Popover
To create a basic popover, use the data-bs-toggle="popover" attribute on any element.

<button type="button" class="btn btn-secondary" data-bs-toggle="popover" title="Popover title" data-bs-content="And here's some amazing content. It's very engaging. Right?">
  Click to toggle popover
</button>

Popover Options
Trigger: You can control how the popover is triggered (e.g., click, hover, focus).
data-bs-trigger=""

Placement: You can position the popover on top, right, bottom, or left of the element.
data-bs-placement=""

javascript
var popoverTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="popover"]'))
var popoverList = popoverTriggerList.map(function (popoverTriggerEl) {
  return new bootstrap.Popover(popoverTriggerEl)
})


2. Documentation for Bootstrap Spinner

Overview
Bootstrap Spinner is used to display a loading state in your projects. They can be used as a standalone element or embedded within buttons.

Creating a Spinner
To create a basic spinner, use the .spinner-border class for a circular spinner or .spinner-grow for a growing spinner.

<div class="spinner-border" role="status"></div>

Spinner Options
Color: You can customize the color of the spinner by using Bootstrap’s contextual classes (e.g., .text-primary, .text-danger).

<div class="spinner-border text-primary" role="status"></div>

Size: You can control the size of the spinner by adding .spinner-border-sm or using custom CSS.

<div class="spinner-border spinner-border-sm" role="status"></div>

Button Spinners: You can use spinners inside buttons to indicate loading states.

<button class="btn btn-primary" type="button" disabled>
  <span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"></span>
  Loading...
</button>