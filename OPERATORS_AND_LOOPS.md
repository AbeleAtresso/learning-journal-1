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

| a | b | a && b | a || b | !a |
|---|---|--------|--------|----|
| t | t |   t    |   t*   | f  |
| t | f |   f    |   t*   | f  |
| f | t |   f*   |   t    | t  |
| f | f |   f*   |   f    | t  |

Short circuit evaluation (items marked with * above) means that the first condition can provide enough information to get an answer, so that the program will not evaluate the second condition. When dealing with the AND operator, if the first condition is false the entire expression is false. When dealing with the OR operator, if the first condition is true then the entire expression is true.

### Duckett: JavaScript & jQuery, Chapter 4, pages 170-173, and 176

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