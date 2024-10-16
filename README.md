# JS30-3-Variables

# CSS Variables and JavaScript Interaction

This project demonstrates how to update CSS variables dynamically using JavaScript. It allows the user to interact with a set of controls (range sliders and color picker) to change the spacing, blur, and base color of an image on the webpage.

## Features

- **CSS Variables**: The project uses CSS custom properties (variables) to control the styling of an image and text.
- **JavaScript Interaction**: JavaScript is used to capture user input from the controls and update the CSS variables in real-time.
- **Controls**:
  - **Spacing**: Adjusts the padding around the image.
  - **Blur**: Controls the blur effect applied to the image.
  - **Base Color**: Changes the base color of the text and image background.

## How It Works

### HTML

The HTML provides:

- A header with the title.
- A control panel with sliders to adjust spacing and blur, and a color input to select the base color.
- An image element that is affected by the CSS variables.

### CSS

The CSS sets default values for the CSS variables `--spacing`, `--blur`, and `--base`. These values are applied to the image and text styles. The `:root` selector is used to define global CSS variables that can be updated dynamically.

### JavaScript

JavaScript captures the changes in the input controls and updates the CSS variables using `document.documentElement.style.setProperty()`. It listens for both the `change` and `mousemove` events on the inputs to ensure smooth updating.

## Code Structure

- **HTML**: The structure of the page with input controls and an image.
- **CSS**: Styling of the image and text using CSS variables.
- **JavaScript**: Event listeners to update the CSS variables when user interaction happens.

## How to Run

1. Clone or download the repository.
2. Open the `index.html` file in a web browser.
3. Adjust the controls (spacing, blur, and base color) to see the image and text styling update dynamically.

## Project Screenshot

![screenshot](![alt text](./image/image.png))

## Technologies Used

- HTML5
- CSS3 (including CSS Variables)
- JavaScript (DOM Manipulation)

## Lessons Learned

- How to use CSS variables.
- How to manipulate CSS variables in JavaScript.
- Dynamic interaction between HTML controls and CSS styles.
