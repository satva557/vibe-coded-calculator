# Responsive Calculator with History and Dark/Light Mode Toggle

## Overview
This is a fully responsive calculator built with HTML, CSS, and JavaScript. It includes:
- **Keyboard Support** for easy input.
- **Responsive Design** that adapts to both mobile and desktop screens.
- **Calculation History** to store and reuse previous results.
- **Dark/Light Mode Toggle** to switch between themes.

## Features
- **Keyboard Support**:
  - Use number keys, operators (`+`, `-`, `*`, `/`), decimal point (`.`), `Enter` for evaluation, `Backspace` to delete, and `Escape` to clear.
  
- **Responsive Layout**:
  - The calculator adapts to different screen sizes using relative units (`vw`, `%`, etc.).

- **Calculation History**:
  - Keeps track of the last 10 calculations, allowing you to click on any previous result to reuse it.

- **Dark/Light Mode**:
  - Switch between dark and light themes with a toggle button at the top. Your theme preference is saved and applied automatically on future visits.

## Installation
To use the calculator, simply download the HTML file and open it in your browser.

### Steps:
1. Clone or download this repository.
2. Open the `index.html` file in a browser to start using the calculator.

## Usage
1. **Enter Numbers and Operators**: Use the on-screen buttons or type numbers, `+`, `-`, `*`, `/`, and `.` on your keyboard.
2. **Evaluate Expression**: Press the `=` button or hit `Enter` on your keyboard.
3. **Clear the Calculation**: Press the `Clear` button or hit `Escape` on your keyboard.
4. **View History**: Past calculations will appear below the calculator. Click any entry to reuse it.
5. **Toggle Themes**: Click the moon icon in the top right to toggle between dark and light modes.

## Features in Detail

### 1. Calculation History
- Stores the last 10 calculations in the browser's `localStorage`.
- Allows you to click on any past result to insert it back into the current calculation.

### 2. Dark/Light Mode
- The mode is toggled via a button in the top right corner (`🌙` for dark mode and `🌞` for light mode).
- The selected theme is saved in the browser's `localStorage` and automatically applied when you revisit the page.

### 3. Responsive Design
- The calculator layout adjusts based on screen size, ensuring a great user experience on both mobile and desktop devices.

## Tech Stack
- **HTML5**: Used for the basic structure of the calculator.
- **CSS3**: For styling the layout and responsive design.
- **JavaScript**: To handle the calculator logic, keyboard support, history, and theme toggle.

## Contributing
Feel free to fork this project, make improvements, or create issues for any bugs you encounter.
