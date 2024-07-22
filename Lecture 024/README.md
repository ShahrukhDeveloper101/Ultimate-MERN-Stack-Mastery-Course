1. Lecture 24: Bootstrap Grid System

Breakpoints
Bootstrap’s grid system uses a series of breakpoints to determine how layouts change across different screen sizes. Here are the predefined breakpoints in Bootstrap:

Breakpoint	             Class infix	            Dimensions
X-Small	                    None	                <576px
Small	                    sm	                    ≥576px
Medium	                    md	                    ≥768px
Large	                    lg	                    ≥992px
Extra large	                xl	                    ≥1200px
Extra extra large	        xxl	                    ≥1400px

Each breakpoint corresponds to a range of screen sizes, allowing you to create responsive layouts that adapt to different devices.

Bootstrap 12 Columns in a Row
Bootstrap's grid system is built on a 12-column layout, which means you can create up to 12 columns in a single row. Each column can span a number of these 12 available columns.

For example:

A column with .col-6 will take up half the row's width.
A column with .col-4 will take up a third of the row's width.
Rows and Columns
To create a grid layout, you need to use the .row class to wrap your columns. Each row can contain up to 12 columns. Here’s a basic example:

<div class="container">
    <div class="row">
        <div class="col-4">Column 1</div>
        <div class="col-4">Column 2</div>
        <div class="col-4">Column 3</div>
    </div>
</div>
In this example, each of the three columns takes up 4 of the 12 available columns, making them equally spaced within the row.

Column Classes: col-sm, col-md, col-lg, etc.
Bootstrap provides specific classes for different breakpoints to control how many columns a column should span at various screen sizes. These classes are:

col-sm-*: Applies to small screens and up (≥576px).
col-md-*: Applies to medium screens and up (≥768px).
col-lg-*: Applies to large screens and up (≥992px).
col-xl-*: Applies to extra large screens and up (≥1200px).
col-xxl-*: Applies to extra extra large screens and up (≥1400px).
Here’s how you can use these classes to create responsive layouts:

<div class="container">
    <div class="row">
        <div class="col-sm-6 col-md-4 col-lg-3">Column 1</div>
        <div class="col-sm-6 col-md-4 col-lg-3">Column 2</div>
        <div class="col-sm-12 col-md-4 col-lg-6">Column 3</div>
    </div>
</div>
In this example:

Column 1 and Column 2: Span 6 columns on small screens, 4 columns on medium screens, and 3 columns on large screens.
Column 3: Spans 12 columns (full width) on small screens, 4 columns on medium screens, and 6 columns on large screens.