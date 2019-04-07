# Pandas_Folium_example
demonstrate power of Pandas and Folium

This notebook demonstrates the power of the Pandas and Folium packages to efficiently get answers from data sets.

### Background
A high school science class assignment asked students to download the last 15 days of earthquake data from www.usgs.gov and identify the date, location city, latitude/longitude, and the magnitude of the largest recorded quake each day.  Using a pivot table in Excel it is straight forward to get a table of the date and magnitude of the largest quake.

However, adding the additional information into the pivot table isn't as simple. Knowing the date and magnitude allows one to filter the raw data consisting of 150+ data points per day and 4000+ data points total to copy and paste the desired data into a summary table.  There's probably other ways to get the desired data using Excel or Excel with VBA.

But using pandas and folium the data can be summarized and plotted very quickly.
