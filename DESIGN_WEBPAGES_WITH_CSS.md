## Design Webpages with CSS
Cascading Style Sheets (CSS) is a programming language used to add style and design to the elements of a webpage. CSS style rules consist of a selector that identifies which HTML element(s) to apply style to, followed by a set of curly brackets. Between the curly brackets we declare one or more style values and properties. A colon goes between the value and property, while a semi-colon goes at the end of each property. Here is [the CSS code](https://deltav-101.mlhauschildt.repl.co/style.css) that I use to teach DeltaV's Code 101 course.

### Duckett: HTML & CSS, Chapter 10 - Introducing CSS
In my discussion about [Structuring Webpages with HTML](STRUCTURE_WEBPAGES_WITH_HTML.md) I described and gave examples of block and inline elements. It's important to know that all elements have an invisible box around them. We use CSS to control the style and appearance of each box. For instance, a paragraph of text can have it's font and color changed with this code:
```css
p {
  font-family: Arial;
  color: blue;
}
```
This code selects all HTML `<p></p>` elements and declares that the font-family should be Arial and the text color should be blue. 

CSS can be used in 3 places: (1) Externally, (2) Internally, and (3) Embedded. 
  1. To create CSS _externally_, the programmer will create a new file with a name like `styles.css` and nest a `<link href="styles.css" rel="stylesheet">` tag between the `<head></head>` tags of each HTML file. The code to style paragraphs, and many more, can be placed inside this file to be rendered across all linked HTML files.
  2. To create CSS _internally_, the programmer will nest `<style></style>` tags between the `<head></head>` tags of each HTML file. The code to style paragraphs, and many more, can be placed inside this file to be rendered across a single HTML file.
  3. To create _embedded_ CSS, you can add style rules directly to HTML tags using the `style=""` attribute. For instance, this code will apply style to a single paragraph element. `<p style="font-family: Arial; color: blue;">Text content</p>

There are [many types of CSS selectors to learn](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors). The most common ones include: universal selectors, type selectors, class selectors, id selectors, child selectors, descendant selectors, and many more.

[The word "cascading"](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance) refers to the order in which competing style rules are applied. If two style rules have the same property and are created using the same selector, the last one in the code will be applied. In the following code, all p elements would have a green background color.

```css
p { 
    background-color: yellow; 
}
p { 
    background-color: green; 
}
```
If two style rules have the same property but are created using different selectors that apply to the same element, the one in the code that is the most specific will be applied. In the following code, any p element with a class attribute set to "highlight" will have a yellow background color. 

```css
.highlight { 
    background-color: yellow; 
}
        
p { 
    background-color: green; 
}
```

### Duckett: HTML & CSS, Chapter 11 - Color
There are [6 ways to specify colors in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value): (1) color names, (2) Hexadecimal values, (3) RGB values, (4) HSL values, (5) HSV values, and (6) CMYK values. Colors can be used for text color, background color, and border color.
- Color names: There are over 100 predefined names including red, white, blue, green, etc.
- Hexadecimal and RGB values: There are over 16 million color combinations that can be made with both Hexadecimal and RGB values. Additionally, both support an alpha channel to control transparency.
- HSL values allows us to control the hue, saturation, and lightness of a color. This is one of my favorites because it allows me to create a set of matching colors easily. 

It's important that text is readable (has high contrast) to make sure that all users have equitable access to the website/app. Dark text on light background colors, and vice versa, are recommended.

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