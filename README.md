# Image Slider Project

## Overview
This is a simple image slider built using HTML, CSS, and JavaScript. It displays a series of images that can be navigated through using previous and next buttons. The images also change automatically every 10 seconds, creating a smooth, continuous slideshow effect.

## Features
- Automatic image sliding every 10 seconds.
- Manual navigation using "Next" and "Previous" buttons.
- Smooth fade-in/fade-out animation between slides.
- Responsive design that adapts to different screen sizes.
  
## Technologies Used
- **HTML**: To structure the webpage.
- **CSS**: For styling the slider, images, and buttons.
- **JavaScript**: To add functionality for slide transitions and navigation.

## Project Files
- `index.html`: The main HTML file for the project.
- `style.css`: The CSS file for styling the slider.
- `script.js`: The JavaScript file for controlling the image transitions and button clicks.

## How It Works
- The slider contains multiple images, each within a `div` element with the class `slide`.
- Initially, only the first image is displayed, and the others are hidden using `display: none;`.
- JavaScript is used to switch between slides every 10 seconds, and users can also manually navigate using the "Next" and "Previous" buttons.
- The CSS defines a smooth fade animation between the images for a visually appealing effect.

## Customization
- To add or replace images, update the `<img>` tags in the `index.html` file.
- You can change the automatic transition timing by modifying the `setInterval` function in `script.js`.
