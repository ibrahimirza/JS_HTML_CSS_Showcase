# JavaScript Background Color Switcher

This is a simple web application that allows users to switch the background color of the page by clicking on different color buttons. The project demonstrates basic HTML, CSS, and JavaScript for DOM manipulation.

## Features

- Change the background color of the webpage by clicking on color buttons.
- Four colors are available: Grey, White, Blue, and Yellow.
- Responsive layout for different screen sizes.

## Project Structure

- **index.html**: The main structure of the webpage, containing the HTML elements.
- **style.css**: The CSS file (assumed to be present) to style the elements in the HTML.
- **script.js**: The JavaScript file responsible for changing the background color based on user interaction.

## How It Works

1. The webpage has a set of color buttons represented by spans with specific `id`s for each color (grey, white, blue, yellow).
2. The JavaScript listens for click events on the entire body. When a button is clicked, the `id` of the clicked element is used to update the background color of the page.
3. Each button's `id` corresponds to a color, and when clicked, the `body`'s background color is updated to that specific color.

## Code Explanation

- **HTML**: Defines a simple structure for a webpage with a header (`h1`), instruction text (`h2`), and four clickable buttons (`span` elements).
- **CSS**: (Assumed) Used to style the buttons and layout.
- **JavaScript**: 
  - Selects all elements with the class `.button` and listens for clicks on the `body` element.
  - On each click, the script checks the `id` of the clicked element and sets the background color of the body to match the clicked button's `id`.

