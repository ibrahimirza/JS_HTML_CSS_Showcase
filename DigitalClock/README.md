# Your Local Time

This is a simple web application that displays the user's local time on the webpage. The time is updated every second using JavaScript's `setInterval()` function. The project demonstrates basic HTML, CSS, and JavaScript to create a live clock.

## Features

- Displays the current local time of the user.
- The time automatically updates every second.
- Simple and clean design with centered content and a responsive layout.
- Includes a navigation bar with a link to a YouTube channel.

## Project Structure

- **index.html**: The main HTML file which structures the layout of the page.
- **script.js**: Contains the JavaScript code to fetch and update the current time.
- **styles.css** (optional): An external stylesheet that can be included for additional styling (assumed to exist based on the provided HTML).

## How It Works

1. **HTML**:
    - The webpage has a navigation bar with two links: one for the homepage and one for an external YouTube channel.
    - The time is displayed inside a `div` with the `id` of `clock`.
2. **CSS**:
    - The page is styled with basic CSS rules, including a dark background and a bright orange background for the time display.
    - The `.center` class ensures that the content is vertically and horizontally centered.
3. **JavaScript**:
    - The script selects the `clock` element using `document.getElementById()`.
    - A `setInterval()` function updates the inner HTML of the `clock` div every second with the user's local time using `date.toLocaleTimeString()`.

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/ibrahimirza/your-local-time.git
