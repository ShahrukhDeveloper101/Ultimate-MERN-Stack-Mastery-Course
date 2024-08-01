Documentation for Bootstrap Alerts

Overview
Bootstrap Alerts are used to provide feedback messages to the users. They can be used to display success messages, warnings, errors, and informational messages. Bootstrap provides predefined classes to style these messages and make them visually distinct.

Creating Alerts
To create an alert, you simply need to use the .alert class along with the specific alert type class such as .alert-success, .alert-warning, .alert-danger, or .alert-info.
 
<div class="alert alert-success" role="alert">
  This is a success alert—check it out!
</div>
<div class="alert alert-warning" role="alert">
  This is a warning alert—check it out!
</div>
<div class="alert alert-danger" role="alert">
  This is a danger alert—check it out!
</div>
<div class="alert alert-info" role="alert">
  This is an informational alert—check it out!
</div>

Dismissing Alerts
You can make alerts dismissible by adding the .alert-dismissible class and including a close button.
 
<div class="alert alert-warning alert-dismissible fade show" role="alert">
  This is a dismissible warning alert—check it out!
  <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
</div>

Adding Additional Content
Alerts can also contain additional HTML elements like headings, paragraphs, and links.
 
<div class="alert alert-success" role="alert">
    <div class="text-end">
        <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
    </div>
  <h4 class="alert-heading">Well done!</h4>
  <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
  <hr>
  <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>

Documentation for Bootstrap Badges

Overview
Bootstrap Badges are used to add extra information to any content. They are typically used for notifications, counts, or labeling elements.

Creating Badges
To create a badge, use the .badge class. Badges can be used inside other elements such as headings, buttons, and list items.

<h1>Example heading <span class="badge bg-secondary">New</span></h1>
<h2>Example heading <span class="badge bg-secondary">New</span></h2>
<h3>Example heading <span class="badge bg-secondary">New</span></h3>

Contextual Variations
Bootstrap provides several contextual classes for badges to indicate different types of information.
 
<span class="badge bg-primary">Primary</span>
<span class="badge bg-secondary">Secondary</span>
<span class="badge bg-success">Success</span>
<span class="badge bg-danger">Danger</span>
<span class="badge bg-warning text-dark">Warning</span>
<span class="badge bg-info text-dark">Info</span>
<span class="badge bg-light text-dark">Light</span>
<span class="badge bg-dark">Dark</span>

Badge as Part of a Button
Badges can be used within buttons to show counts or labels.
 
<button type="button" class="btn btn-primary">
  Notifications <span class="badge bg-secondary">4</span>
</button>

Pill Badges
For rounded badges, use the .rounded-pill class.
 
<span class="badge rounded-pill bg-primary">Primary</span>
<span class="badge rounded-pill bg-secondary">Secondary</span>
<span class="badge rounded-pill bg-success">Success</span>
<span class="badge rounded-pill bg-danger">Danger</span>
<span class="badge rounded-pill bg-warning text-dark">Warning</span>
<span class="badge rounded-pill bg-info text-dark">Info</span>
<span class="badge rounded-pill bg-light text-dark">Light</span>
<span class="badge rounded-pill bg-dark">Dark</span>


<button type="button" class="btn btn-primary position-relative">
    Inbox
    <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
        99+
        <span class="visually-hidden">unread messages</span>
    </span>
</button>
