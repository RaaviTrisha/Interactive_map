# Interactive_map
Overview
This project implements an interactive map using Leaflet.js, displaying points of interest (POIs) in New York City. The map allows users to view specific locations, click on markers to learn more about the sites, and search for locations by name. The project utilizes OpenStreetMap tiles and basic JavaScript for map interactivity.

Features
Interactive Map: Displays an interactive map of New York City.
Markers for Points of Interest: Markers are placed on the map for various tourist locations (Statue of Liberty, Central Park, etc.).
Popup Information: Each marker displays a popup with the name and description of the location when clicked.
Search Functionality: Users can search for specific locations by name, and the map will zoom to the matching location and display its information.
Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/interactive-map.git
Open the project folder:

bash
Copy code
cd interactive-map
Open the index.html file in your web browser to view the map.

Alternatively, you can host the project on a local server using tools like Live Server in VS Code or any web server of your choice.

Files
index.html: The HTML structure of the map, including the search input and button.
interactive_map.js: The JavaScript code that handles the map initialization, marker placement, and search functionality.
style.css (optional): If you decide to add custom styles, this file can be used to enhance the visual appearance of the map and page.
How It Works
Map Initialization: The map is initialized with a default view centered around New York City using the Leaflet.js library.
Adding Markers: An array of predefined locations (points of interest) is created. Markers are added to the map for each of these locations, with popups displaying the name and description of the place.
Search Functionality: When the user types in the search box and clicks the search button, the script searches for a matching location by name. If found, the map centers on the location, and a popup appears showing the location's information.
Demo
You can view a live demo of the project by visiting this link.

Requirements
A modern web browser that supports JavaScript.
Internet connection for loading the OpenStreetMap tiles.
Dependencies
Leaflet.js: A JavaScript library for interactive maps.

You can include it in your project by using the following CDN:

html
Copy code
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
Contributing
Feel free to fork this repository, create pull requests, or suggest improvements. If you encounter any bugs or have suggestions for new features, open an issue and I’ll do my best to address it.

Steps to contribute:
Fork the repository
Create a new branch for your feature or bug fix
Make changes and commit them
Push to your forked repository
Open a pull request to the main repository
License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to modify or extend the project to include more features, such as adding additional POIs, customizing the map's appearance, or integrating it with other data sources.
