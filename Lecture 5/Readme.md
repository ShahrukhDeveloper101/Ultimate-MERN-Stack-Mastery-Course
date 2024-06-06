Block-level Elements
Block-level elements typically start on a new line and take up the full width available. They are used to define larger sections or blocks in the document.

<div>: Defines a division or a section.
<p>: Defines a paragraph.
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>: Define HTML headings.
<ul>: Defines an unordered list.
<ol>: Defines an ordered list.
<li>: Defines a list item.

<header>: Defines a header for a document or section.
<footer>: Defines a footer for a document or section.
<section>: Defines a section in a document.
<article>: Defines an article.
<nav>: Defines navigation links.
<aside>: Defines content aside from the content it is placed in.
<blockquote>: Defines a section that is quoted from another source.
<pre>: Defines preformatted text.
<table>: Defines a table.
<form>: Defines an HTML form for user input.
<main>: Defines the main content of a document.
<figure>: Defines self-contained content, like illustrations, diagrams, photos, etc.
<figcaption>: Defines a caption for a <figure> element.
<!-- block level elements ends here -->


Inline Elements
Inline elements do not start on a new line and only take up as much width as necessary. They are used for smaller pieces of content within block-level elements.

<span>: Defines a section in a document.
<a>: Defines a hyperlink.
<strong>: Defines important text (usually bold).
<em>: Defines emphasized text (usually italic).
<img>: Defines an image.
<br>: Inserts a single line break.
<i>: Defines a part of text in an alternate voice or mood (italic).
<b>: Defines bold text.
<u>: Defines underlined text.
<small>: Defines smaller text.
<mark>: Defines marked/highlighted text.
<sub>: Defines subscripted text.
<sup>: Defines superscripted text.

<abbr>
Definition: Defines an abbreviation or acronym.
Purpose: Provides a full form of the abbreviation or acronym when hovered over, making the content more understandable.
Attributes: The title attribute is commonly used to provide the full form.
<abbr>: Defines an abbreviation or acronym.
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

<cite>
Definition: Defines the title of a work.
Purpose: Used to reference the title of a creative work, such as a book, article, or song.
Use: It is commonly used in bibliographies, quotes, and references.

<cite>: Defines the title of a work.
<p>One of my favorite books is <cite>The Great Gatsby</cite> by F. Scott Fitzgerald.</p>

<code>
Definition: Defines a piece of computer code.
Purpose: Specifies text that represents code, which is often displayed in a monospaced font.
Use: Used for inline code snippets within a paragraph.
<code>: Defines a piece of computer code.
<p>To print "Hello, World!" in Python, use the command <code>print("Hello, World!")</code>.</p>

<q>
Definition: Defines a short inline quotation.
Purpose: Used for short quotations that are integrated into the main text. Browsers typically add quotation marks around the content.
Attributes: The cite attribute can be used to provide the source of the quote.
<q>: Defines a short quotation.
<p>Albert Einstein once said, <q>Imagination is more important than knowledge.</q></p>

<time>
Definition: Defines a specific time (or datetime).
Purpose: Represents dates and times in a machine-readable format, making it easier for browsers, search engines, and other tools to process.
Attributes: The datetime attribute specifies the date and/or time.
<time>: Defines a specific time (or datetime).
<p>The event will take place on <time datetime="2024-06-06T14:00">June 6, 2024, at 2:00 PM</time>.</p>

<var>
Definition: Defines a variable in programming or math.
Purpose: Indicates a variable, which is usually displayed in an italic font.
Use: Commonly used in mathematical expressions and programming code.
<var>: Defines a variable in programming or math.
<p>Let <var>x</var> be the number of apples. If <var>x</var> = 10, then we have 10 apples.</p>

<kbd>
Definition: Defines keyboard input.
Purpose: Represents text that users should type or keyboard input, typically displayed in a monospaced font.
Use: Used in instructions and documentation to indicate keyboard commands.
<kbd>: Defines keyboard input.
<p>To save your work, press <kbd>Ctrl</kbd> + <kbd>S</kbd>.</p>
