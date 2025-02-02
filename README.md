# AUTOMATED-REPORT-GENERATION

**COMPANY NAME** :CODTECH IT SOLUTIONS

**NAME** :N.Hima Bindu Aparna

**INTERN ID** :CT08LGO

**DOMINE** : PYTHON

**BATCH DURATION** :January 10th, 2025 to February 10th, 2025.

**MENTOR NAME** :Neela Santhosh Kumar 

**output** :https://github.com/aparnanelapolu/AUTOMATED-REPORT-GENERATION 

**discription** :The code fetches weather data for a specified city (London in this case) using the OpenWeatherMap API and then visualizes the temperature trends for the next 7 days using a line plot.

Steps:

Import necessary libraries:

requests: Used to send HTTP requests to the API.
matplotlib.pyplot: Used for creating plots and charts.
datetime: Used for handling dates and times.
Define API credentials and parameters:

API_KEY: Your personal API key from OpenWeatherMap (replace 'your_api_key' with your actual key).
CITY: The city for which you want to fetch weather data (set to 'London').
URL: The API endpoint URL, including the city and API key.
Fetch weather data:

Sends a GET request to the API using requests.get(URL).
Checks if the request was successful (status code 200).
If successful, extracts weather data from the response as a JSON object.
Extract and organize data for plotting:

Iterates through the forecast data for the next 7 days.
Extracts the date and temperature for each day.
Stores the dates and temperatures in separate lists.
Create and display the plot:

Creates a figure and axes using plt.figure() and plt.plot().
Plots the temperatures against the dates as a line graph.
Sets the plot title, labels, and grid.
Rotates the x-axis labels for better readability.
Displays the plot using plt.show().
Error handling:

If the API request was not successful (status code other than 200), prints an error message.
