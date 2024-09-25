# JS-HTML-CSS Showcase

This repository contains multiple small web applications that demonstrate various JavaScript, HTML, and CSS functionalities. These projects cover topics such as event handling, DOM manipulation, dynamic styling, and generating random colors or displaying key codes. Each project has a distinct functionality to showcase core web development concepts.

## Projects Overview

### 1. **JavaScript Background Color Switcher**

A simple web app that allows users to switch the background color of the webpage by clicking on buttons representing different colors.

- **Features**: 
  - Four colors: grey, white, blue, and yellow.
  - Dynamic background color change based on user input.
  
- **How it Works**:
  - Each button corresponds to a color.
  - JavaScript listens for `click` events and updates the background color based on the clicked button.

- **Files**: 
  - `index.html`, `script.js`, `style.css`

---

### 2. **Your Local Time Display**

A web application that dynamically displays the user's local time, which updates every second.

- **Features**: 
  - Displays real-time local time.
  - Simple UI with centered content.
  
- **How it Works**:
  - JavaScript's `setInterval()` is used to update the time every second using `Date().toLocaleTimeString()`.

- **Files**: 
  - `index.html`, `script.js`

---

### 3. **Event KeyCodes Display**

This project displays the key, keycode, and code of any key pressed on the keyboard. It dynamically updates the table with each key press.

- **Features**: 
  - Displays information about the pressed key in real-time.
  - Includes a table with columns for Key, Keycode, and Code.
  
- **How it Works**:
  - JavaScript listens for the `keydown` event and updates the page content with the pressed key’s properties.

- **Files**: 
  - `index.html`, `script.js`

---

### 4. **Unlimited Background Colors**

A fun project where the background color changes randomly every second upon clicking the "Start" button. The user can stop the color change by clicking the "Stop" button.

- **Features**: 
  - Generates random background colors using hex values.
  - Start and Stop buttons to control the color change.
  
- **How it Works**:
  - The `randomColor()` function generates a random hexadecimal color.
  - JavaScript’s `setInterval()` changes the background color every second when "Start" is clicked.
  - The color change is stopped by clearing the interval when "Stop" is clicked.

- **Files**: 
  - `index.html`, `script.js`, `style.css`

---

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/ibrahimirza/DOM_JavaScript_Project.git

2. Navigate to the projec directory:
   ```bash
   cd project-folder-name

3. Open index.html in your browser to view the project :
    ```bash
    open index.html
