# Udacity Restaurant Review App

This is the 5th project in the Front-End Development Nanodegree

## Getting Started

The following instructions will tell you how to get a copy of the project up and running on your local machine for reviewing and testing. 

### Prerequisites

Python 2 or 3 are required to run this web application. For Linux/Unix based systems, as well as MacOS, Python is usually included. Go to terminal and check your Python version by typing ```Python -V```.

For Windows based system, you can get the installer [here](https://www.python.org/downloads/windows/), and follow the instructions. Be sure with the Windows installer to add Python to your system path, this will be an option available while installing.

This project also requires a MapBox API key, which can be aquired at: [MapBox](https://www.mapbox.com/). Depending on when this is viewed, you could be prompted to place a MapBox key into the indicated location in the `main.js` and `restaurant_info.js` files.

Udacity provided starter code for this project that was updated to ES6, this means the application is best run in Chrome, FireFox or Edge browsers. Older versions may not display the app or it may not function optimally.

### Options to view, download or clone the project:

1. The repository for my project is located at (https://github.com/bobbypapson/restaurant-review-app)
2. You can clone or download the project from here

### Starting the Server

These are the instructions Udacity has provided to get the application running on a Python based server and to get it opened in the browser. Assuming Python is on your system path, navigate to main folder of the project you downloaded or cloned above and do the following:

1. Navigate to the main project folder and run the following in your terminal:
    * **Python2.x**: `python -m SimpleHTTPServer 8000`
    * **Python3.x**: `python3 -m http.server 8000`
2. Open a browser such as Chrome or FireFox to:
    * `http://localhost:8000`
    * Should be able to view and use the application.

## Using the Application

The Restaurant Review App is simple to use: You are provided with a map and filtering options. Select the neighborhood in New York City and the type of cuisine you are interested in from the drop down selectors. The options will be filtered based on your preferences, and the map will update as well with your selections. Once your options are provided below, as restaurant cards with a photo, you can select one to view more information. A full photo, a map, and all the reviews will be provided for the selected restaurant. There is a breadcrumb navigation near the top of this view to return to the selection screen. Easy as that!

## Built With

* [MapBox](https://www.mapbox.com/) - The Map API Used
* [Leaflet.js](https://leafletjs.com/) - Library used with Mapbox

## Authors

* **Bobby Papson** - *Initial work* - (https://github.com/bobbypapson).
* Project starter code provided by Udacity as part of a NanoDegree requirement.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

