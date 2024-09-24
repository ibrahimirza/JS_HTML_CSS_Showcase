# Event KeyCodes

This is a simple web application that displays the JavaScript event properties for any key pressed on the keyboard. It shows the key's name, keycode, and event code in a tabular format.

## Features

- Displays real-time information about the key pressed.
- Shows three event properties: `Key`, `Keycode`, and `Code`.
- Interactive, simple, and easy-to-use design.
- Responsive layout with flexible design using CSS.

## Project Structure

- **index.html**: The HTML file that provides the structure of the webpage.
- **script.js**: JavaScript file that handles the key press event and dynamically updates the page content.

## How It Works

1. **HTML**:
   - The page contains a simple layout with a `div` where the key event data is displayed.
   - The default text instructs the user to press any key.
2. **CSS**:
   - The inline CSS styles the table and positions the content in the center of the screen.
   - Flexbox is used for centering the content vertically and horizontally.
   - Dark background with contrasting white text for clarity.
3. **JavaScript**:
   - JavaScript listens for the `keydown` event on the `window` object.
   - When a key is pressed, the event properties (`key`, `keyCode`, and `code`) are displayed in a dynamically generated HTML table.
   - The key event data is updated in real-time with each keypress.


