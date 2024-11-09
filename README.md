## Movie App - HTML, CSS, and JavaScript

This project implements a simple movie search app using HTML, CSS, and JavaScript. Users can search for movies by title or browse through different categories. The app features:

### Functionality

* **Search:** Users can search for movies by entering their title into a search bar and clicking the search button.
* **Category Browsing:** The app includes categories like "Latest," "Bollywood," and "Hollywood" that users can explore to find movies within specific genres or regions.
* **Movie Details:** Clicking on a movie result will fetch and display detailed information about the movie, including poster, title, year, rating, genre, writer, actors, plot, language, and awards.
* **Watching History:** The app remembers movies the user has clicked on and stores them in local storage. Users can access their watching history with a dedicated button.
* **Responsive Design:** The app is designed to be responsive and work well on various screen sizes, from large desktops to mobile devices.

### HTML Features

* **Structure:** The HTML defines the layout of the app using elements like `<header>`, `<main>`, and `<footer>`.
* **Search Bar:** The search bar is implemented using an `<input type="text">` element and a search button.
* **Movie Results:** The movie results are displayed using a `<div>` element with a grid layout (`grid-template-columns`).
* **Movie Details:** Movie details are displayed within a `<div>` element with appropriate styling.
* **Category Dropdown:** A category dropdown is implemented using `<div>` elements with appropriate CSS classes to achieve the desired functionality.

### CSS Features

* **Styling:** CSS is used to style the elements of the app, including colors, fonts, margins, paddings, and positioning.
* **Responsive Design:** Media queries are used to adjust the layout and styling for different screen sizes, ensuring a good user experience across devices.
* **Visual Effects:** CSS transitions and animations are used to create visual effects like hover effects and movie item transitions.

### JavaScript Features

* **DOM Manipulation:** JavaScript is used to manipulate the DOM (Document Object Model) to create and modify elements dynamically.
* **Event Handling:** Event listeners are used to respond to user interactions like clicking search button, navigating through categories, and selecting movie results.
* **API Integration:** The app integrates with the OMDb API to fetch movie information based on search terms or categories.
* **Local Storage:** JavaScript uses local storage to store the user's watching history.
* **Error Handling:** JavaScript includes error handling to gracefully handle API failures and provide appropriate user feedback.

### Project Files

* **index.html:** The main HTML file containing the structure and content of the app.
* **style.css:** The CSS file containing the styles for the app.
* **script.js:** The JavaScript file containing the logic and functionality of the app.

This movie app is a basic demonstration of using HTML, CSS, and JavaScript to build interactive web applications. It demonstrates how to use API integration, local storage, responsive design, and DOM manipulation to create a dynamic and user-friendly web experience.
