1. Lecture 23: Bootstrap Typography, Colors, and Utilities
Heading Styles
Bootstrap provides a set of predefined heading styles that help maintain consistent typography across your web pages. These styles are based on HTML heading tags (<h1> to <h6>).

Basic Heading Styles: Use Bootstrap's heading classes to apply different heading sizes.
 
<h1 class="display-1">Display 1</h1>
<h2 class="display-2">Display 2</h2>
<h3 class="display-3">Display 3</h3>
<h4 class="display-4">Display 4</h4>
<h5 class="h1">Heading 1</h5>
<h6 class="h2">Heading 2</h6>

Customizing Headings: 
You can customize the heading styles using Bootstrap's utility classes. For example, you can change the text color, alignment, and more.

 
<h1 class="text-primary text-center">Centered Primary Heading</h1>
<h2 class="text-success">Success Heading</h2>
<h3 class="text-danger">Danger Heading</h3>

Text Alignment and Transformation
Bootstrap provides utility classes to control text alignment and transformation, making it easy to align text and transform its case.

Text Alignment: Use classes like .text-left, .text-center, and .text-right to align text.
 
<p class="text-left">Left aligned text.</p>
<p class="text-center">Center aligned text.</p>
<p class="text-right">Right aligned text.</p>

Text Transformation: Use classes like .text-lowercase, .text-uppercase, and .text-capitalize to transform text.

<p class="text-lowercase">Lowercase text.</p>
<p class="text-uppercase">Uppercase text.</p>
<p class="text-capitalize">Capitalized text.</p>

Text and Background Colors
Bootstrap offers a variety of classes to change the text and background colors of elements.

Text Colors: Use classes like .text-primary, .text-secondary, .text-success, .text-danger, .text-warning, .text-info, .text-light, .text-dark, and .text-muted to change text color.
 
<p class="text-primary">Primary text.</p>
<p class="text-secondary">Secondary text.</p>
<p class="text-success">Success text.</p>
<p class="text-danger">Danger text.</p>
<p class="text-warning">Warning text.</p>
<p class="text-info">Info text.</p>
<p class="text-light bg-dark">Light text on dark background.</p>
<p class="text-dark">Dark text.</p>
<p class="text-muted">Muted text.</p>

Background Colors: Use classes like .bg-primary, .bg-secondary, .bg-success, .bg-danger, .bg-warning, .bg-info, .bg-light, and .bg-dark to change background color.

<div class="bg-primary text-white">Primary background.</div>
<div class="bg-secondary text-white">Secondary background.</div>
<div class="bg-success text-white">Success background.</div>
<div class="bg-danger text-white">Danger background.</div>
<div class="bg-warning text-dark">Warning background.</div>
<div class="bg-info text-white">Info background.</div>
<div class="bg-light text-dark">Light background.</div>
<div class="bg-dark text-white">Dark background.</div>

Utility Classes for Spacing and Display 
Bootstrap provides a range of utility classes to control spacing & display properties of elements.

Spacing Utilities: Use classes like .m-0, .mt-1, .mb-2, .ml-3, .p-1, .pt-2, .pb-3, etc., to control margin and padding.
we have margin & padding 1 - 5 like m-1, m-2, ... , m-5

m-1, m-2, m-3, m-4, m-5 => provide margin on each side 

mt-1, mt-2, mt-3, mt-4, mt-5 => provide margin on top only 

mb-1, mb-2, mb-3, mb-4, mb-5 => provide margin on bottom only 

ms-1, ms-2, ms-3, ms-4, ms-5 => provide margin on start/left only 

me-1, me-2, me-3, me-4, me-5 => provide margin on end/right only

mx-1, mx-2, mx-3, mx-4, mx-5 => provide margin on x axis / left & right

my-1, my-2, my-3, my-4, my-5 => provide margin on y axis / top & bottom

p-1, p-2, p-3, p-4, p-5 => provide padding on each side 

pt-1, pt-2, pt-3, pt-4, pt-5 => provide padding on top only 

pb-1, pb-2, pb-3, pb-4, pb-5 => provide padding on bottom only 

ps-1, ps-2, ps-3, ps-4, ps-5 => provide padding on start/left only 

pe-1, pe-2, pe-3, pe-4, pe-5 => provide padding on end/right only

px-1, px-2, px-3, px-4, px-5 => provide padding on x axis / left & right

py-1, py-2, py-3, py-4, py-5 => provide padding on y axis / top & bottom
 
<div class="m-3 p-3 bg-light">Margin and padding example.</div>
<div class="mt-5 mb-2 p-2 bg-secondary text-white">Top and bottom margin with padding.</div>

Display Utilities: Use classes like .d-block, .d-inline, .d-inline-block, .d-flex, .d-none, etc., to control display properties.

<div class="d-block">Block level element.</div>
<span class="d-inline">Inline element.</span>
<div class="d-flex justify-content-between">
  <div>Flex item 1</div>
  <div>Flex item 2</div>
</div>
<div class="d-none">Hidden on small screens, visible on medium and larger screens.</div>
<div class="d-block">Hidden on small screens, visible on medium and larger screens.</div>
 

