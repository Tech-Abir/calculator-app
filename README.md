# Responsive Calculator

MIT-licensed, single-file web calculator that performs basic arithmetic operations. It is responsive, accessible, and handles invalid input gracefully.

## Overview
Features:
- Buttons for digits 0–9, decimal, and basic operators (+, −, ×, ÷)
- Live display updates as you click buttons
- Computes results on pressing the equals button (=) or Enter key
- Clear (C) button to reset the calculator
- Input validation and graceful error handling (e.g., trailing operators, multiple decimals)
- Responsive layout with keyboard support (0–9, + - * /, ., Enter, Esc)

Accessibility:
- Screen-reader friendly display (aria-live)
- Visible focus states for keyboard navigation

## Setup
- No build tools required.
- Open index.html in any modern browser.

## Usage
- Click number and operator buttons to build an expression. The display updates as you go.
- Press “=” (or Enter) to evaluate.
- Press “C” (or Esc) to clear and start over.
- Invalid expressions (e.g., ending with an operator) are auto-sanitized before evaluation; any remaining errors are shown as “Error,” after which you can start fresh.

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.