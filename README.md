# TheLone | PranavRaam

This is an interactive tile-based website featuring a unique flip animation and background block highlight effect. The project is built using HTML, CSS, JavaScript, and GSAP for animations. It showcases a responsive board with tiles that flip and blocks that highlight based on user interactions.

## Features

- **Interactive Tiles**: The webpage features a 6x6 tile grid where each tile responds to hover actions by flipping, with dynamic tilting effects.
- **GSAP Animations**: Smooth tile flipping animations and staggered tile transitions are powered by GSAP.
- **Block Highlighting**: The page includes a background layer with blocks that get highlighted as the user moves their cursor over them.
- **Responsive Design**: The tile grid and blocks adapt to different screen sizes.
- **Customizable Tile Backgrounds**: Each tile has front and back faces that display images, allowing easy customization of the tile's appearance.

## Technologies Used

- **HTML5**: The structure of the page.
- **CSS3**: Styling of the tiles, blocks, and overall layout.
- **JavaScript**: Functionality for tile animations and block interactions.
- **GSAP (GreenSock Animation Platform)**: Used for smooth and customizable animations on the tiles.
  
## Project Structure

- **index.html**: The main HTML file containing the structure and links to styles and scripts.
- **styles.css**: The CSS file for styling the layout, tiles, and blocks.
- **script.js**: The JavaScript file where tile animations and block highlights are implemented.

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/TheLone-PranavRaam.git
    ```

2. Open the `index.html` file in your browser.

3. To customize the tile backgrounds, replace the `front.jpg` and `back.jpg` images inside the `assets` folder with your own.

## Usage

- Hover over the tiles to see them flip with dynamic tilt angles based on their position.
- Click on the "Flip All Tiles" button to flip all the tiles at once.
- Move your mouse across the screen to see blocks in the background highlight dynamically.

## Dependencies

This project uses GSAP for animations. It is included via CDN:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
