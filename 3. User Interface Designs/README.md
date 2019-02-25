# 3. Sequence Diagrams

To get the most up to date tempanomaly map predictions to the users on their browsers, the following components speak to each other:
- **NASA's database** holding the raw historical tempanomaly data in a NetCDF file format.
- **Our database** which is where we store predictions and history as png's as well as the weights of the neural network used to make these predictions
- Our **back end** which handles two things
  1. Makes predictions using a neural network and stores them as png's
  2. Delivers predictions stored as png's to the front end by fetching it from our database.
- **Front end** which requests png's as the user scrolls through the website travelling through time.

https://github.com/jamin-hu/Reaktor-Ennakkotehtava/raw/master/3.%20User%20Interface%20Designs/Sequence%20Diagram.jpg
