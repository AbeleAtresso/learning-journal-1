## Operators and Loops

### Duckett: JavaScript & jQuery, Chapter 4, pages 150-151, 156, and 157
Comparison operators can be used to evaluate two values. The result will be a Boolean (true or false).
- Is equal to: `==` or `===`
- Is not equal to: `!=` or `!==`
- Greater than [or equal to]: `>` or `>=`
- Less than [or equal to]: `<` or `<=`

Logical operators can be used to compare the results of two or more comparison operators.
- AND (tests more than one condition): `&&`
- OR (tests at least one condition): `||`
- NOT (inverts boolean value): `!`

When multiple logical operators are used in a single expression, the AND operator(s) will be evaluated before OR operator(s).

| a | b | a && b | a \|\| b | !a |
|---|---|--------|--------|----|
| t | t |   t    |   t*   | f  |
| t | f |   f    |   t*   | f  |
| f | t |   f*   |   t    | t  |
| f | f |   f*   |   f    | t  |

Short circuit evaluation (items marked with * above) means that the first condition can provide enough information to get an answer, so that the program will not evaluate the second condition. When dealing with the AND operator, if the first condition is false the entire expression is false. When dealing with the OR operator, if the first condition is true then the entire expression is true.

### Duckett: JavaScript & jQuery, Chapter 4, pages 170-173, and 176
Loops are groups of one or more expressions that repeat a specific task. Loops are controlled with boolean expressions, called conditions, and will only run when the condition is true. The loop will repeat until the same condition returns false. The conditions are usually expressed with a numerical counter variable, a string variable based on user input, or state of a game.

There are 3 types of loops:
- For loops run code for a specific number of times (called iterations). They will always operate with a numeric counter variable.
- While loops run code for an unspecified number of times (called iterations). They can operate with numeric, string, or state variables.
- Do while loops are the same as while loops but are guaranteed to run at least once. 

The variables used to control the loops must first be initialized;
- `var i = 0;` It is common to use `i`, `j` or `counter` as a numerical variable name.
- `var prediction = prompt('What am I thinking of?');` You can use any variable name that makes sense when prompting for string input.
- `var gameOver = false;` You can use an variable name that makes sense when setting the state of the loop.

After the variable is initialized a conditional must be specified to indicate when the loop should stop.
- `i < 10`
- `prediction === 'pizza'`
- `!gameOver`

Lastly, there must be some way to update or assign a new value of the variable before it gets evaluated again.
- `i++` (add one), `i -= 2` (subtract two), etc.
- `prediction = prompt('Incorrect, guess again.');`
- `if(score >= 100) { gameOver = true; }`

Here are examples of each of the items discussed above:
- [For loops](https://repl.it/@mlhauschildt/JavaScript-For-Loops#script.js)
- [While loops](https://repl.it/@mlhauschildt/JavaScript-While-Loops#script.js)
- [Do While loops](https://repl.it/@mlhauschildt/JavaScript-Do-While-Loops#script.js)

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
- [Operators and Loops](OPERATORS_AND_LOOPS.md)