# project-1-blog-post
Nano Degree Assignment 1 - Write a Data Science Blog Post

I have decided to look at Edinburgh AirBnB data as that is the city I was born in - I think it's a great place to visit, but do others agree?
I sourced the data from here: http://insideairbnb.com/get-the-data.html

Info about the files from AirBnB:
File Name	Description
10 July, 2021	Edinburgh	listings.csv.gz	Detailed Listings data for Edinburgh
10 July, 2021	Edinburgh	calendar.csv.gz	Detailed Calendar Data for listings in Edinburgh
10 July, 2021	Edinburgh	reviews.csv.gz	Detailed Review Data for listings in Edinburgh
10 July, 2021	Edinburgh	listings.csv	Summary information and metrics for listings in Edinburgh (good for visualisations).
10 July, 2021	Edinburgh	reviews.csv	Summary Review data and Listing ID (to facilitate time based analytics and visualisations linked to a listing).
N/A	Edinburgh	neighbourhoods.csv	Neighbourhood list for geo filter. Sourced from city or open source GIS files.
N/A	Edinburgh	neighbourhoods.geojson	GeoJSON file of neighbourhoods of the city.

I used gzip -dk filnename.csv.gz in my Linux command line to unzip the bigger data files:
https://phoenixnap.com/kb/extract-tar-gz-files-linux-command-line


Packages used:
-- pandas
-- matplotlib
-- numpy
-- scipy
-- sklearn

Useful guides:
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html


Later:
-- do I want to install geopandas and draw some maps?
https://www.python-graph-gallery.com/map-read-geojson-with-python-geopandas