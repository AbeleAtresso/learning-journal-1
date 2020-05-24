## Programming with JavaScript

### Duckett: JavaScript & jQuery, Introduction and Chapter 1a, pages 1-24
JavaScript can be used to select/access HTML elements, attributes, and content, such as text. JavaScript can then be used to add and modify the elements, attributes, and content. JavaScript can be used to respond to user events such as page loads, clicks, form submissions, mouse movements, or time intervals. JavaScript programming rules are similar to other traditional programming languages. 

Before coding, programmers can develop a flowchart that define the goal of a program then sketch out the individual tasks needed to solve a problem in the form of a flowchart. Each task can be broken down into a sequence of steps which can then be translated into code. Coding requires an understanding of vocabulary and syntax. The programmer must specify every detail of what the program is expected to do. When something goes wrong the programmer will debug their code and make corrections.

### Duckett: JavaScript & jQuery, Chapter 2, pages 74-79
Expressions are lines of code that results in a single value and end with a semi-colon. Expressions rely on operators (`+`, `-`, `*`, `/`, `%`, `++`, `--`, `>`, `>=`, `<`, `<=`, `===`, `!==`, `&&`, `||`) to calculate values. 

Expressions are commonly used to assign values to variables or display results. [View this repl.it file](https://repl.it/@mlhauschildt/Programming-with-JavaScript-Duckett-book) to test the following code. 
- `var name = 'Marc';` Assigns a string to a variable.
- `var greeting = 'Hi ' + name + '!';` Combines multiple strings together. The result of this expression is `Hi Marc!`.
- `var age = 39;` Assigns a number to a variable.
- `age++;` Adds one to the age variable. Two minus signs `--` can be used to subtract one. The result of this expression is `40`.
- `age = age + 1;` Another way to add one to a variable. The result of this expression is `41`.
- `var isEven = (age % 2 === 0);` Performs a logical expression and assigns a boolean (`true` or `false`) to a variable. The `%` divides two numbers and returns the remainder. The three equal signs `===` test equality. The result of `age % 2` is `1` (`41` divided by `2` is `20` with a remainder of `1`). The result of the whole expression is `false` (`1` is not equal to `0`).
- `var result = 6 + 5 - 4 * 3 / 2;` Mathematical expressions are evaluated left to right, however multiplication and division will be performed before addition and substraction (PEMDAS). The result of this expression is `5` (`4 * 3` results in `12`, `12 / 2` results in `6`, `6 + 5` results in `11`, `11 - 6` results in `5`).
- `result = 6 + (5 - 4) * 3 / 2;` To change the order of operations values in parenthesis will be evaluated first. The result of this expression is `7.5` (`5 - 4` results in `1`, `1 * 3` results in `3`, `3 / 2` results in `1.5`, `6 + 1.5` results in `7.5`).

### Duckett: JavaScript & jQuery, Chapter 2, pages 88-94
A function is a named group of one or more expressions that perform a specific task to achieve a goal. A function can be declared by writing the keyword `function`, followed by a name, followed by a list of required inputs inside parenthesis (called parameters), followed by a set of curly brackets. The expressions needed are placed inside the parenthesis (called a code block). Please note that a semi-colon is not needed after the closing curly bracket. 

The following function will respond by returning the result of multiplying the values of the two required parameters.
```JavaScript
function multiply(x, y) {
  return x * y;
}
```
When we need to perform the task we _call_ the function by writing an expression that includes the function name and a list of data inputs inside parenthesis (called arguments). When it has finished, the code continues to run from the point where it was initially called. In JavaScript the function call can be written before or after the function declaration because of _hoisting_, meaning that all declarations will be automatically moved to the top of the script.

The following expression will call the multiply function passing two values as arguments. The returned result will be `6`.
```JavaScript
var num1 = 3;
var num2 = 2;
var result = multiply(num1, num2);
```

Functions can even be called from inside other functions. The following expressions will call the calculateVolume function passing three values as arguments, which itself calls the calculateArea function passing two values as arguments. The returned result will be `24`.
```JavaScript
function calculateArea(w, h) {
  return width * height;
}

function calculateVolume(w, h, d) {
  return calculateArea(w, h) * d;
}

var width = 3;
var height = 2;
var depth = 4;
var volume = calculateVolume(width, height, depth);
```


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
- [Programming with JavaScript](PROGRAMMING_WITH_JAVASCRIPT.md)