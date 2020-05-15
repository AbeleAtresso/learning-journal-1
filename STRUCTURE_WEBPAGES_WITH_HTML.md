## Structure Webpages with HTML
Hypertext Markup Language (HTML) is a programming language used to define the structure of webpage content. Most standard HTML elements comprise of an opening and closing tag. Between the tags we put content such as text or other HTML elements. Attributes can be added to opening HTML tags to provide additional information about the element. Here is [the code](https://repl.it/@mlhauschildt/DeltaV-101) and [the hierarchy](https://docs.google.com/drawings/d/1ecK-waRVLa5_njxA51rhuG5xpDDmlq-TtkarK-nvp0c/edit?usp=sharing) that I use to teach DeltaV's Code 101 course.

### Duckett: HTML & CSS, Chapter 18 - Process & Design
Before I start any coding I need to plan my process and design. I need to understand the people that will use my site/app and learn what they will be using it for. I need to obtain the content they will expect to find. I will use sitemaps and wireframes to organize the content so visitors can easily find what they're looking for. I will apply design theory practices to make the presentation of my site/app attractive and professional.

### Duckett: HTML & CSS, Chapter 1 - Structure
Webpages are electronic versions of newspapers, documents, games, and other real life things. HTML elements are used to create containers around content to setup the structure of a webpage. There are many HTML elements to learn. They don't need to be memorized, but it's important to know what elements are available and where to find documentation on their uses.

### Duckett: HTML & CSS, Chapter 17 - HTML5 Layout
HTML5 introduced new sets of HTML elements used to define webpage structure. Previously, web designers would structure their apps with deeply nested sets of div elements. Now, web designers can use header, nav, main, article, section, aside, and footer elements (among others) that work in the same way as div elements, but give better understanding to what content goes inside each.

### Duckett: HTML & CSS, Chapter 8 - Extra Markup
- `<!DOCTYPE html>` is used at the top of an HTML file to tell the browser what version of HTML the page is using. 
- `<!-- Comment goes here -->` Any content that is part of a comment will not processed by the browser. Comments are useful to add human-readable messages in code and to temporarily force the browser to ignore some code.
- `<div id="unique-identifer">` ID attributes can be added to the opening tag of any HTML element to give it a unique identifier. That identifier can be styled with CSS or provided interactivity with JavaScript. IDs are used for single elements that need unique style or functionality.
- `<div class="group-identifier">` Class attributes can be added to one or more opening tags of any element to give it an identifier that describes a group that it belongs to. That identifier can be styled with CSS or provided interactivity with JavaScript. Classes are used when multiples elements need to share the same style or functionality.
- `<div>` and `<span>` tags are generic block and inline elements that are used to group content.
- Block elements are those that consume 100% width of their parent container. They will always appear to start on a new line apart from sibling content. Block elements can have width, height, padding, margin, and border CSS properties adjusted. Examples include: `<div>`, `<header>`, `<main>`, `<footer>`, `<article>`, `<aside>`, `<h1>`, `<p>`, `<ul>`, `<li>`. 
- Inline elements are those that only consume the space needed for their content and will always appear to continue in the same line as sibling elements. Inline elements do not have width or height. Margin, padding, and borders can be applied horizontally but not vertically (horizontal changes will cause other inline elements to move away). Examples include: `<a>`, `<strong>`, `<em>`, `<img>`, `<span>`. Block elements can become inline elements, and vice versa, through the use of the CSS `display` property.
- `<iframe>` allows us to display other webpages within our webpages. This may be useful to embed a Google doc, YouTube video, or social media feed into our app.
- Escape characters are characters that we often want to include on our webpages but need a special code to render them correctly. Since HTML elements use greater-than and less-than signs, if we actually want the &lt; and &gt; characters to display on the screen we need to type `&lt;` and `&gt;`. To display a &copy; copyright symbol we need to type `&copy;`.

## Site Navigation
- [Home](README.md)
- [Growth Mindset](GROWTH_MINDSET.md)
- [Learning Markdown](LEARNING_MARKDOWN.md)
- [Coder's Computer](CODERS_COMPUTER.md)
- [Revisions and the Cloud](REVISIONS_AND_THE_CLOUD.md)
- [Structure Webpages With HTML](STRUCTURE_WEBPAGES_WITH_HTML.md)
- [Design Webpages With CSS](DESIGN_WEBPAGES_WITH_CSS.md)
- [Dynamic Webpages with JavaScript](DYNAMIC_WEBPAGES_WITH_JAVASCRIPT.md)
