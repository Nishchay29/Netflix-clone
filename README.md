# Netflix India Landing Page Clone

This project is a responsive, single-page front-end clone of the Netflix India homepage, built to demonstrate modern web layout techniques. 

## Features

* **Responsive Layout:** The design adapts to different screen sizes, utilizing media queries for screens under 1300px to adjust navigation widths, hero text sizing, and grid layouts[cite: 2].
* **Interactive Carousel:** Includes a horizontal scrollable "Trending Now" movie container with functioning left and right navigation buttons powered by vanilla JavaScript[cite: 1].
* **Modern UI Components:** Replicates the core Netflix UI elements, including the hero email signup form, feature cards ("Enjoy on your TV", "Download your shows", etc.), and a styled FAQ list[cite: 1].
* **Custom Typography:** Integrates Google Fonts, specifically Poppins and Martel Sans, for accurate brand styling[cite: 2].
* **Hidden Scrollbars:** The trending movie carousel uses CSS to hide native scrollbars while maintaining smooth horizontal scroll functionality[cite: 2].

## Technologies Used

* **HTML5:** Provides the semantic structure of the page, including navigation, sections, and the footer grid[cite: 1].
* **CSS3:** Handles all styling, utilizing Flexbox for aligning navigation and feature cards, and CSS Grid for the footer layout[cite: 2]. 
* **JavaScript:** A lightweight inline script handles the `scrollBy` method to horizontally scroll the movie container by 500 pixels in either direction[cite: 1].

## File Structure

* `index.html`: The main structural file containing the layout, text content, SVG icons, and inline JavaScript for the carousel[cite: 1].
* `net.css`: The external stylesheet containing all visual rules, hover effects (like card scaling), and responsive breakpoints[cite: 2].
* `images/`: The directory where the referenced movie thumbnails and promotional images are stored (e.g., `images.jpg`, `unforgettable.webp`)[cite: 1].

## Usage

To view the project locally, clone or download the repository to your machine. Ensure both `index.html` and `net.css` are in the same directory. Open `index.html` in any modern web browser to view and interact with the page[cite: 1, 2]. Ensure the `images` folder is populated with the corresponding image files referenced in the HTML for the complete visual experience[cite: 1].
