# Color-changing Rectangle on Mousemove

This is a small JavaScript code snippet using GSAP (GreenSock Animation Platform) to create a color-changing effect on a rectangle element based on mouse movement.

## Overview

The code listens to the `mousemove` event on a specified HTML element (`#center` in this case), calculates the mouse position relative to the element, and adjusts the background color of the element accordingly. The left half of the rectangle transitions from red to white, while the right half transitions from white to blue.

## Prerequisites

Make sure you include GSAP library in your project before using this code. You can include it by adding the following script tag in your HTML file:

```html
<script src="https://unpkg.com/gsap@3.9.0/dist/gsap.min.js"></script>


Usage
Include the GSAP library in your HTML file.
Add an HTML element with the id center that represents the rectangle you want to apply the effect to.
Copy and paste the provided JavaScript code into your project.
Customize the code or integrate it with your existing codebase as needed.
Explanation
The mousemove event triggers a function that calculates the mouse position relative to the left edge of the rectangle.
The mapRange function from GSAP is used to map the mouse position to RGB values, creating a color transition effect.
The rectangle's background color is animated using GSAP's to method.
On mouseleave, the rectangle transitions back to a white background.
