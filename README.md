# Calculator App

A simple, responsive calculator web application that performs basic arithmetic operations. Built with HTML, CSS, and JavaScript, this calculator allows users to perform addition, subtraction, multiplication, and division.

## Features

- **Basic Operations**: Supports addition (+), subtraction (-), multiplication (*), and division (/).
- **Clear and Delete**: Options to clear all input or delete the last character.
- **Responsive Design**: Adjusts layout for different screen sizes.
- **Error Handling**: Displays "Error" for invalid operations.

## Project Structure

- `index.html`: The HTML file that contains the structure of the calculator.
- `style.css`: The CSS file that styles the calculator layout and buttons.
- `index.js`: The JavaScript file that contains functions to handle button clicks and perform calculations.

## Getting Started

1. Clone the repository or download the source code.
2. Open the `index.html` file in your browser.

## Usage

- Enter numbers by clicking the buttons on the calculator.
- Use `+`, `-`, `*`, and `/` for arithmetic operations.
- Click `=` to calculate the result.
- `C` clears the entire input.
- `Del` deletes the last entered character.

## Code Overview

### HTML (index.html)

Defines the structure of the calculator, including:
- An input field to display numbers and results.
- Buttons for numbers, operations, and actions.

### CSS (style.css)

Styles the calculator layout and button appearance, including:
- Button colors and hover effects.
- Display field styling for a polished look.

### JavaScript (index.js)

Contains the main logic for the calculator:
- **appendToDisplay(value)**: Adds the clicked button's value to the display.
- **clearDisplay()**: Clears all text from the display.
- **deleteLast()**: Deletes the last character from the display.
- **calculate()**: Evaluates the expression and updates the display with the result.

## Example

```html
<div class="calculator">
    <input type="text" id="display" placeholder="0">
    <button onclick="appendToDisplay('1')">1</button>
    <button onclick="calculate()">=</button>
</div>
