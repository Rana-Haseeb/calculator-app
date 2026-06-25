# CALC - Dark Edition

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Site-7c3aed?style=for-the-badge&logo=github&logoColor=white)](https://rana-haseeb.github.io/calculator-app/)

A sleek, single-file calculator built with plain HTML, CSS, and JavaScript. It combines a neon dark interface with a responsive layout, keyboard support, and polished calculator behavior for everyday arithmetic.

![CALC Dark Edition](https://img.shields.io/badge/CALC-Dark%20Edition-00ff9d?style=for-the-badge)
![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![Single File](https://img.shields.io/badge/Single%20File-HTML%20%2B%20CSS%20%2B%20JS-7c3aed?style=for-the-badge)

## Overview

This project is a compact calculator application designed to run directly in the browser with no build step and no external framework. It is ideal as a portfolio piece, internship task, or reference project for learning DOM interaction, state handling, and UI styling.

The interface focuses on clarity and visual impact:

- Glowing dark theme with neon accents
- Animated background grid and soft light effects
- Large, readable display with expression history
- Dedicated backspace button in the display area
- Support for both mouse/touch input and keyboard input

## Features

- Basic arithmetic: add, subtract, multiply, divide
- Decimal input
- Percentage calculations
- Sign toggle for positive/negative values
- Clear and backspace actions
- Chained operations with expression preview
- Error handling for invalid results and divide-by-zero cases
- Auto-resizing result text for long numbers
- Responsive layout for smaller screens
- Keyboard shortcuts for faster input

## Preview

The app has a modern retro-futuristic look with:

- Orbitron-style result text
- Neon green calculator display
- Cyan operator buttons
- Pink special-action buttons
- Purple gradient equals button

## How To Run

No installation is required.

1. Open the project folder.
2. Double-click `calculator.html`.
3. The calculator will open in your default browser.

You can also open the file from VS Code using Live Server or a similar extension if you prefer a local preview workflow.

## Controls

### On-Screen Buttons

| Button     | Action                          |
| ---------- | ------------------------------- |
| `AC` / `C` | Clear all / clear current entry |
| `+/-`      | Toggle sign                     |
| `%`        | Convert value to percent        |
| `⌫`        | Delete the last digit           |
| `÷ × − +`  | Choose an operator              |
| `=`        | Calculate the result            |

### Keyboard Shortcuts

| Key                  | Action            |
| -------------------- | ----------------- |
| `0-9`                | Enter digits      |
| `.` or `,`           | Decimal point     |
| `+ - * /`            | Operators         |
| `Enter` or `=`       | Evaluate          |
| `Backspace`          | Delete last digit |
| `Delete` or `Escape` | Clear             |
| `%`                  | Percent           |

## Project Structure

| File              | Purpose                                                |
| ----------------- | ------------------------------------------------------ |
| `calculator.html` | Main app file containing markup, styling, and behavior |
| `README.md`       | Project overview and usage guide                       |

## Implementation Notes

- The calculator is fully self-contained inside one HTML file.
- JavaScript manages the app state through a small internal state object.
- The display updates dynamically to show both the current value and the expression line.
- Long values are shortened or resized so they remain readable.
- The app uses keyboard listeners and button dispatching so both input methods stay in sync.

## Browser Support

The project is expected to work in any modern browser that supports:

- ES6 JavaScript
- CSS Grid and Flexbox
- Modern DOM events and rendering behavior

For the best visual result, use a current version of Chrome, Edge, Firefox, or Safari.

## Customization

If you want to change the look and feel, the easiest place to start is the CSS variable block near the top of the file. That section controls:

- Background colors
- Button colors
- Glow effects
- Border radius values
- Display and operator accent colors

This makes it straightforward to reskin the calculator without changing the underlying logic.

## Notes

- The Google Fonts import requires an internet connection for the intended typography to load.
- Without internet access, the calculator still works, but the visual style may fall back to default system fonts.
- The project is designed as a front-end demo and does not store data or require a backend.

## Future Ideas

- Add history memory
- Add a theme switcher
- Support scientific functions
- Allow copying results with one click
- Split CSS and JavaScript into separate files for larger maintenance work

## License

No license file is currently included. Add one if you want to publish or reuse the project publicly.
