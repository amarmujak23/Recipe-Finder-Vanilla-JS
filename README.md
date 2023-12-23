# Recipe-Finder-Vanilla-JS
A recipe finder made in HTML CSS and JavaScript


HTML Structure:
Title: "Recipe Finder"
Input Field: Where users can type a dish name they want to find recipes for.
Search Button: Triggers the search for the entered dish.
Result Section: Where the recipe details will be displayed.
JavaScript Functionality:
Event Listener: Listens for a click on the search button.
Fetch Function: Uses the fetch API to retrieve data from an external source (in this case, https://www.themealdb.com/api/json/v1/1/search.php?s=).
Data Handling: Processes the retrieved data (if valid) to extract information about the dish, such as its image, name, area, instructions, and ingredients.
Display: Dynamically updates the HTML to show the retrieved recipe details.
Show/Hide Recipe: Allows users to view or hide the recipe instructions.
CSS Styling:
Overall Styling: Sets up the layout, colors, fonts, and responsiveness for different screen sizes.
Search Container Styling: Formats the input field and search button.
Recipe Details Styling: Styles the displayed recipe details, including the image, name, area, ingredients, and instructions.
