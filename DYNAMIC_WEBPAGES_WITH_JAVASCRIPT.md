## Dynamic Webpages with JavaScript
JavaScript is a programming language that allows me to write code that instructs the browser how to behave when a user interacts with my app. When the browser reads HTML, the document object model (or DOM) is established. JavaScript and jQuery can be used to access and manipulate the DOM, making the user's experience dynamic and interactive. 

### Duckett: JavaScript & jQuery, Chapter 1c, pages 43 - 52
- HTML establishes the page content and structure. CSS establishes the presentation and appearance. JavaScript enables behavior and interactivity, enhances usability.
- JavaScript files can go inside their own text file with a .js extension. Inside the HTML we tell the browser when to run the JavaScript code by adding a set of `<script></script>` tags. The script element has an `src` attribute which is used to identify the URL of the script file.
- JavaScript can be added directly between the script tags, however that may cause the page to take longer to load. It's better to keep it in a separate file so it can be used on several pages, rather than one.
- Objects are collections of data that can be manipulated with JavaScript. The whole web page defines the document object. 
- Methods can be called using objects to perform tasks. 
- Parameters are additional pieces of data that are sent to the methods for processing. 
- In `document.write('Hello World');`, **document** is the _object_, **write()** is the _method_, and **'Hello World'** is the _parameter_ that gets sent to the method. Combined together this code prints some text on the web page. 

### Duckett: JavaScript & jQuery, Chapter 2, pages 53 - 69
- Statements are steps of instructions that the browser will follow. Each statement starts on a new line and ends with a semi-colon to indicate that that the step is complete.
- Code blocks are groups of statements surrounded by curly brackets. It is not necessary to put semicolons at the end of code blocks. Code blocks help organize code and make it more readable.
- Comments are lines of code that are ignored by the browser. They can be used to explain code to other people who read the code, or as a way to temporarily disable code. Single line comments in JavaScript start with `//` while multi-line comments start with `/*` and end with `*/`
- Variables are statements that store values in memory for later use. Values can change (or vary) during the execution of the script. Variables will be held in the browser's memory until the page is re-loaded or the user leaves the page.
- Variable statements are declared by using the `var` keyword, followed by a name that represents the type of data being stored. Variable names should most often start with a lowercase letter and have no spaces. If a variable name requires more than one word, an underscore can substitute the space. Or the variable name can be written in camel case where the first word is all lowercase while the second or third words have their first letter capitalized. Variable names are case-sensitive.
- Variables are assigned values by typing an equals sign after the variable name then typing the data to be stored. If a variable is assigned a value after it has been declared, we start the statement with just the variable name, not `var`.
- Variables can be declared without a value (to be assigned later), or they can be assigned a value immediately.
- Variable can store numerical data (examples: 4, 1.75, etc.), string data (any text that contains letters or other characters), boolean data (true or false), arrays (a collection of data organized by an index value), objects (a collection of data organized by key values), functions (code blocks that define a sequence of statements), and node elements (the HTML blocks stored in the DOM). 
- String data must be surrounded by single or double quotes. Numerical and boolean data do not use quotation marks. If double quotes are needed inside the string the programmer could surround the string with single quotes and then safely use the double quotes inside the string. If single quotes are needed inside the string and the programmer wants to surround the string in single quotes, the quotes inside the string need a backslash added before the quote to tell the browser that the quote is part of the string and not the end of it.
- Boolean values must be typed in all lowercase letters. Booleans can represent true/false, on/off, 0/1, or other equivalent binary combinations. We will eventually use booleans to write conditions which will control alternative code blocks for our code to take.
- Multiple variables can be declared and assigned on the same line by using the `var` keyword once, followed by the variable names (and values) each separated by commas. 




## Site Navigation
- [Home](README.md)
- [Growth Mindset](GROWTH_MINDSET.md)
- [Learning Markdown](LEARNING_MARKDOWN.md)
- [Coder's Computer](CODERS_COMPUTER.md)
- [Revisions and the Cloud](REVISIONS_AND_THE_CLOUD.md)
- [Structure Webpages With HTML](STRUCTURE_WEBPAGES_WITH_HTML.md)
- [Design Webpages With CSS](DESIGN_WEBPAGES_WITH_CSS.md)
- [Dynamic Webpages with JavaScript](DYNAMIC_WEBPAGES_WITH_JAVASCRIPT.md)
- [Computer Architecture and Logic](COMPUTER_ARCHITECTURE_AND_LOGIC.md)
- [Programming with JavaScript](PROGRAMMING _WITH_JAVASCRIPT.md)