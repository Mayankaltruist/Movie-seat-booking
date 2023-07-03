# Movie Seat Booking

This is a seat booking app implemented in vanilla JavaScript. It allows users to select and book seats for a movie screening.

## Functionality

- Displays a seating layout with available seats.

- Allows the user to select seats by clicking on them.

- Updates the seat count and total price dynamically based on the selected seats.

- Persists the selected seats, movie selection, and related data in the browser's localStorage to retain the state      between page reloads.

## Usage

1. To use the Seat Booking App, follow these steps:

2. Include the necessary HTML markup and CSS styling for the seating layout and other elements in your webpage.

3. Create a JavaScript file, such as script.js, and include the provided code in your file.

4. Customize the code according to your specific needs, such as changing class names, modifying the seat selection logic, or adjusting the ticket price calculation.

5. Ensure that you have a container element with the class name "container" that wraps the seating layout.

6. Make sure to have an element with the ID "count" to display the number of selected seats, an element with the ID "total" to display the total price, and a select element with the ID "movie" to choose the movie and update the ticket price.

7. Include the necessary HTML elements for the seating layout, with seats represented by elements having the class name "seat" and unoccupied seats having no additional class.

8. Add event listeners and handlers as needed to respond to seat selections, movie changes, and other user interactions.

9. Customize the populateUI() function if you want to load data from the localStorage and populate the UI with any previously selected seats or movie.

10. Customize the setMovieData() function if you want to save the selected movie index and price to the localStorage.

11. Customize the updateSelectedCount() function if you want to modify how the selected seat count and total price are updated in the UI.

12. Finally, load your webpage in a browser to see and interact with the Seat Booking App.
