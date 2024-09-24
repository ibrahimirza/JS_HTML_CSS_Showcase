# Unlimited Colors

This project is a simple web application that dynamically changes the background color of the webpage every second upon clicking the "Start" button. The background color changes randomly using hexadecimal color codes. The user can stop the color changes by clicking the "Stop" button.

## Features

- **Random Background Color Change**: The webpage background color changes every second when the "Start" button is clicked.
- **Stop Functionality**: The background color changes can be stopped by clicking the "Stop" button.
- **Hexadecimal Color Generation**: Colors are generated randomly using hexadecimal values.

## Project Structure

- **index.html**: The HTML file that provides the basic structure of the webpage, including two buttons: one for starting the color change and one for stopping it.
- **style.css**: The CSS file that styles the webpage, including the buttons and text.
- **script.js**: The JavaScript file responsible for the background color change logic.

## How It Works

1. **HTML**:
    - Contains two buttons labeled "Start" and "Stop".
    - A heading explaining the functionality is displayed.
2. **CSS**:
    - The webpage has a dark background and uses simple styling for the buttons.
    - The buttons have borders and are styled with rounded corners for a modern look.
3. **JavaScript**:
    - The `randomColor()` function generates a random hexadecimal color.
    - The `startChangingColor()` function starts an interval that changes the background color every second.
    - The `stopChangingColor()` function stops the background color change by clearing the interval.
    - Event listeners are added to the "Start" and "Stop" buttons to trigger the respective functions.


