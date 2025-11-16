# Sign-up Form - The Odin Project

This is a responsive sign-up page layout built from scratch using HTML and CSS. This project demonstrates intermediate CSS concepts, including complex form styling, absolute positioning, and creating grid-like layouts using only Flexbox.

***

## Screenshot

![App Screenshot](./screenshot/Screenshot%20from%202025-11-16%2008-30-51.png)


## Live Demo

You can access it here: https://laym00n.github.io/odin-sign-up-form/

## Features

* **Split-Screen Layout:** Features a full-height background image sidebar on the left and a clean content section on the right.

* **Custom Form Layout:** Uses Flexbox with `flex-wrap` and `calc()` logic to create a responsive two-column input grid without using CSS Grid.

* **Interactive Input States:**
    * **Focus:** Inputs glow with a custom color (Odin Green) and a soft shadow when clicked.
    * **Validation:** Inputs display a red border only when the user has typed invalid data (using the `:not(:placeholder-shown)` trick).

* **Layered Visuals:** Implements a "sandwich" design effect using white backgrounds and drop shadows to make the form appear to float above the page.

* **Custom Typography:**
    * Loads a local font ("Norse-Bold") using `@font-face` for the logo.
    * Uses Google Fonts (Roboto) for the main interface text.

* **Translucent Overlay:** Uses absolute positioning relative to the sidebar to create a semi-transparent logo header strip.

## Technologies Used

1.  **HTML5:** Used semantic tags like `<fieldset>`, `<legend>`, and `<form>` to structure the page content.

2.  **CSS3:** Handled all styling, including:
    * **Flexbox:** Used for the main split layout and the input grid system.
    * **Positioning:** Used `absolute` and `relative` positioning for the logo overlay.
    * **Box Model:** extensive use of padding, margins, and `box-shadow` to create depth.
    * **Local Assets:** Linked local font files and images manually.