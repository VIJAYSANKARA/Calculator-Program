#Calculator-Program
🧮 Calculator using HTML, CSS & JavaScript
This is a responsive web-based Calculator built using core web technologies: HTML for structure, CSS for styling, and JavaScript for functionality. It supports basic arithmetic operations and is styled with a clean, modern UI.

🔧 Key Features and Functionality:
Interactive UI: Built with HTML form elements styled with custom CSS for a dark theme interface with glowing buttons.

Basic Operations: Supports addition, subtraction, multiplication, division, and decimal input.

Control Buttons:

AC clears all input.

DE deletes the last entered digit.

= evaluates the expression in real-time using JavaScript.

Responsive Layout: Uses viewport scaling and flexbox to center the calculator on any screen size.

Stylish Effects: Neumorphic design using subtle shadows and glowing operator buttons (#33ffd8 for standout operators).

🧠 How it Works:
HTML Structure:

A container centers the calculator both vertically and horizontally.

A form inside .calculator holds all buttons and the input display.

Each button is an input element with onclick JavaScript logic.

CSS Styling:

The .calculator has a dark background with padding and rounded corners.

Buttons are styled with hover-ready box shadows to mimic physical keys.

Operators are highlighted in teal (#33ffd8), and the equal button is wider for better usability.

JavaScript Logic (Inline):

display.value += appends digits/operators to the screen.

eval(display.value) evaluates the full expression.

slice(0, -1) deletes the last character for corrections.

" " resets the display on clear.

Responsive Design:

Uses viewport meta tag and flexible CSS to adapt to various screen sizes.

Perfectly usable on both desktop and mobile browsers.
