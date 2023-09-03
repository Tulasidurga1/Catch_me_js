# Catch_me_js
# Hosted Link:-https://tulasidurga1.github.io/Catch_me_js/
### HTML:

- The HTML structure is basic, containing a <head> section with a title and a <link> tag to link an external CSS file called "style.css."
- The <body> section contains a <div> element with the id "box" and a <p> element inside it with the text "Catch Me."
- At the end of the <body>, there's a <script> tag that links an external JavaScript file called "script.js."
### CSS (style.css):

- The CSS code applies a few styles:
- The universal selector * sets padding and margin to 0 and uses box-sizing: border-box to ensure that padding and borders are included in the element's total width and height calculation.
- The #box selector styles the div with the id "box."
- It sets its width and height to 7vw (7% of the viewport width), giving it a square shape.
- It sets the background color to a red shade (#f42516).
- The cursor: pointer style makes the cursor change to a pointer when hovering over the box, indicating that it's interactive.
- The position: absolute style positions the box absolutely within its containing element.
- display: flex with justify-content: center and align-items: center centers the content (the "Catch Me" text) both horizontally and vertically within the box.
- The #box p selector styles the text within the box, setting its font size and color.
### JavaScript (script.js):

- It starts by selecting the HTML element with the id "box" and assigns it to the button constant.
- An event listener is added to the button element that listens for the "mouseover" event (when the mouse pointer enters the box).
- When the mouse hovers over the box, the event listener triggers a function that does the following:
- Generates random values for top and left, representing the new top and left positions for the box within its containing element.
- Updates the button element's style.left and style.top properties to move the box to the new random position.
-As a result, the box will appear to "jump" to a random position on the screen when you hover over it.
