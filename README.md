# Mini-card

This project involves creating a "Mini Card" component based on the provided design. The project uses jQuery for interactivity, SCSS for styling, and the BEM methodology for class naming. The component is responsive and toggles the button color between green and red when clicked.

## GitHub Link

https://github.com/marta-prieto/Mini-card

## Features

- **Responsive design**: The component adapts to both desktop and mobile views, with a breakpoint set at 768px.
- **BEM methodology**: The project follows the BEM (Block, Element, Modifier) convention for clean, maintainable CSS class naming.
- **Interactivity**: The button inside the Mini Card toggles its color between `#7AB800` (green) and `#CC292B` (red) when clicked, using jQuery.

## Tech Stack

- **jQuery**: Used for handling button click events and DOM manipulation.
- **SCSS**: Utilized for styling, including responsive design, and organized using the BEM methodology.
- **BEM**: For naming CSS classes in a scalable and maintainable manner.
- **Nunito font**: The Nunito font is used throughout the component, following the design guidelines.

# Project Structure

├── src/
│   ├── scss/
│   │   └── style.scss     # Main SCSS file (using BEM naming)
│   ├── css/
│   │   └── style.css      # Compiled CSS file
│   ├── js/
│   │   └── app.js         # JavaScript file for jQuery interaction
│   └── index.html         # Main HTML file
└── README.md              # Project documentation


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/marta-prieto/Mini-card.git


2. Compile SCSS to CSS:
sass src/scss/style.scss src/css/style.css
