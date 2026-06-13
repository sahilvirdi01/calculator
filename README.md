# Calculator

A simple, elegant web-based calculator application built with vanilla HTML, CSS, and JavaScript.

## Overview

This calculator is a lightweight, user-friendly tool for performing basic arithmetic operations. It features a clean, modern interface with a dark theme and responsive button design.

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division
- **Clear Function**: Easily reset the display with the "C" button
- **Error Handling**: Graceful error messages for invalid calculations
- **Decimal Support**: Calculate with decimal numbers
- **Responsive Design**: Centered, accessible interface that works on different screen sizes
- **Modern UI**: Dark theme with highlighted operator buttons for better visibility

## Project Structure

```
calculator/
├── index.html      # HTML markup and calculator layout
├── style.css       # Styling and visual design
├── script.js       # JavaScript functionality and logic
└── README.md       # This file
```

## File Descriptions

### `index.html`
- Contains the HTML structure of the calculator
- Includes a display input field (read-only)
- 16 buttons arranged in a 4-column grid:
  - Number buttons (0-9)
  - Operator buttons (+, -, *, /)
  - Decimal point button (.)
  - Equals button (=)
  - Clear button (C)

### `style.css`
- Implements the dark theme design with light gray background
- Centers the calculator on the page using flexbox
- Styles buttons as circles with hover and active states
- Highlights operator buttons in orange for distinction
- Large, easy-to-read font sizes (5rem for display, 3rem for buttons)

### `script.js`
- `appendToDisplay(input)`: Adds clicked value to the display
- `clearDisplay()`: Resets the display to empty
- `calculate()`: Evaluates the expression and displays the result
- Basic error handling using try-catch for invalid expressions

## How to Use

1. Open `index.html` in any modern web browser
2. Click buttons to enter numbers and operations
3. Click `=` to calculate the result
4. Click `C` to clear the display
5. Repeat as needed

## Example Calculations

- **Addition**: 15 + 23 = 38
- **Subtraction**: 50 - 12 = 38
- **Multiplication**: 6 * 7 = 42
- **Division**: 100 / 4 = 25

## Browser Compatibility

Works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Flexbox and grid layout, styling
- **Vanilla JavaScript**: DOM manipulation and calculation logic

## Future Enhancements

Potential improvements for future versions:
- Keyboard input support
- Calculation history
- Scientific calculator functions (trigonometry, logarithms)
- Different theme options
- Keyboard shortcuts (e.g., Enter for equals, Escape for clear)
- Mobile optimization with touch feedback

## License

This project is open source and available for personal and educational use.

## Author

Created by [sahilvirdi01](https://github.com/sahilvirdi01)

---

Feel free to fork, modify, and improve this calculator for your own projects!
