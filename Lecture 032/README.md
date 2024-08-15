Documentation Overview for Bootstrap Toast & Tooltip
1. Bootstrap Toast:

Purpose: Bootstrap Toasts are used to show lightweight notifications or alerts that don’t interrupt the user’s interaction with the page.

Basic Usage: Toasts are created using the .toast class. You can place them anywhere in your HTML, and they can be triggered either manually or automatically after a specific event.


Example: 
<div class="toast" role="alert" aria-live="assertive" aria-atomic="true">
  <div class="toast-header">
    <strong class="me-auto">Bootstrap</strong>
    <small class="text-muted">just now</small>
    <button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
  </div>
  <div class="toast-body">
    Hello, world! This is a toast message.
  </div>
</div>

Initialization:
You can initialize a toast using JavaScript:

javascript

var toastEl = document.querySelector('.toast');
var toast = new bootstrap.Toast(toastEl);
toast.show();

Customization: You can customize toast position, duration, and behavior. Toasts can be configured to auto-hide after a few seconds or stay until dismissed.

2. Bootstrap Tooltip:

Purpose: Tooltips are small pop-up boxes that appear when a user hovers over or focuses on an element. They provide additional context or information about an element on the page.


Example: 
<button type="button" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="top" title="Tooltip on top">
  Hover me to see tooltip
</button>

Initialization:
You need to initialize tooltips using JavaScript:

javascript
 
var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'))
var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
  return new bootstrap.Tooltip(tooltipTriggerEl)
})

Customization: Tooltips can be placed at the top, bottom, left, or right of an element. You can also control how they are triggered (click, hover, focus).