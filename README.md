# Calculator Project

This is a simple calculator project built using HTML, CSS, and JavaScript. It provides basic calculator functionalities such as addition, subtraction, multiplication, and division.

## Getting Started

To use the calculator, simply open the `index.html` file in a web browser. The calculator interface will be displayed, allowing you to perform calculations.

## Features

- Addition: Click the `+` button or use the `+` key to add numbers.
- Subtraction: Click the `-` button or use the `-` key to subtract numbers.
- Multiplication: Click the `*` button or use the `*` key to multiply numbers.
- Division: Click the `/` button or use the `/` key to divide numbers.
- Decimal Point: Click the `.` button or use the `.` key to add a decimal point to a number.
- Delete: Click the `DEL` button to delete the last entered digit.
- All Clear: Click the `AC` button to clear the calculator's display and reset the calculations.
- Equals: Click the `=` button or use the `Enter` key to calculate the result.

## Code Structure

The project consists of the following files:

- `index.html`: The HTML structure of the calculator interface.
- `styles.css`: The CSS file that styles the calculator interface.
- `script.js`: The JavaScript file that contains the calculator logic.

The JavaScript code defines a `Calculator` class with various methods to handle different calculator operations, such as clearing the display, deleting digits, appending numbers, choosing operations, computing the result, and updating the display.

The `updateDisplay` method is responsible for updating the calculator's display with the current and previous operands.

## Special Functions Used

The project utilizes several JavaScript functions and concepts, including:

- `querySelectorAll`: This function is used to select multiple elements from the DOM using CSS selectors.
- Event Listeners: The `addEventListener` function is used to attach event listeners to the calculator buttons, enabling them to respond to user clicks.
- String Manipulation: The code uses various string manipulation methods, such as `slice`, `toString`, `split`, and `innerText`, to manipulate and display numbers.
- Parsing: The `parseFloat` function is used to parse the operands as floating-point numbers for accurate calculations.
- Switch Statement: The `switch` statement is used to perform different computations based on the chosen operation.
- Object Initialization: The `Calculator` class constructor is used to initialize the calculator's previous and current operands, as well as the operation.

## Conclusion

This calculator project provides a simple implementation of a calculator interface using HTML, CSS, and JavaScript. It can be further enhanced and customized to add more functionality or improve the user experience. Feel free to modify and adapt the code to suit your specific requirements.

