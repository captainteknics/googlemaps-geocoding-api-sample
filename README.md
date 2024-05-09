# googlemaps-geocoding-api-sample
Sample Code for Google Maps Platform - Geocoding ApI implementation for Beginners and Experts.

This HTML file sets up a simple web application called "My GeoCode App" that allows users to input a location, which is then sent to the Google Maps Geocoding API using Axios, a promise-based HTTP client. Upon submitting the form, the application retrieves data about the location, including its formatted address, address components (such as locality, administrative area, etc.), and geometry (latitude and longitude). This information is displayed on the webpage for the user to see.

The `geocode()` function handles the submission of the location form. It constructs a GET request to the Google Maps Geocoding API, passing the user-entered location and an API key as parameters. Upon receiving a successful response, it parses the data and populates the respective HTML elements with the formatted address, address components, and geometry information. If the response status is not 'OK', an error message is logged to the console.

Additionally, the `saveVariableValues()` function is invoked within `geocode()` after successfully retrieving and displaying the location information. This function assembles the variable names and values (including the location, formatted address, address components, and geometry) into a text string. Then, it creates a downloadable text file named "variableValues.txt" containing this information and prompts the user to save it.

# +254715560734
# captainteknics@gmail.com
