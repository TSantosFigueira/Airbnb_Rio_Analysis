# Airbnb Data - Rio de Janeiro Analysis

Analysis of Airbnb room rents data of Rio de Janeiro, Brazil. This analysis is part of the Data Scientist Nanodegree program by Udacity.

I explored the dataset to answer a few questions:

- What is the most popular neighborhood for renting a room?
- What is the most popular room type?
- What is the most expensive room type?
- The most expensive rooms are located in which neighborhood?
- What is the expected average price per neighborhood?

You can find an explanation of the results in the following post: https://tsfigueira.medium.com/analyzing-the-airbnb-dataset-of-rio-de-janeiro-e00db78b4370
Also, you can use Nbviewer (https://nbviewer.jupyter.org/) to better visualize the notebook. A few additional details about the project are below.

1. Installations
2. File Description
3. Summary of Results
4. Acknowledgments


### 1. Installations

Through the [Anaconda toolkit](https://www.anaconda.com/), I used the Python Libraries: Pandas, Numpy, Matplotlib, and Seaborn.

### 2. File Description

You should look at the notebook (.ipynb) file called Airbnb_Rio_Notebook.ipynb for the source code. 
In the repository, you can also find the datasets used for this analysis. The file listings.csv contains the data we effectively analyze. The file neighbourhoods.geojson has the coordinates for each neighborhood, so it was used in the map.

### 3. Summary of Results

- What is the most popular neighborhood for renting a room?: Ipanema
- What is the most expensive room type?: entire home/apts
- What is the most popular room type? entire home/apts
- What is the most expensive neighborhood to rent a room? Joá is the most expensive neighborhood in Rio. We would expect to pay, on average, 3926.83 per room. Half of the rooms are above the 2277.5 price line; half are below.

The image below shows the map that presents the average price per neighborhood in Rio de Janeiro:

![alt text](https://github.com/TSantosFigueira/Airbnb_Rio_Analysis/blob/main/price_per_neighborhood.png)


### 4. Acknowledgments

Spcecial thanks to the team at Udacity that gave me awesome feedback for this project!
