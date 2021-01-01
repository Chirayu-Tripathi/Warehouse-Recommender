# Warehouse-Recommender
In this project I have worked on weighted k_means clustering along with web scraping to allocate warehouse or cold-storage location for various pizza-hut outlets accross california(USA)


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)


## General info
This project is based on weighted k-means clustering(implemented from scratch) in which I have grouped various outlets to form a cluster. basically, all the nearest outlets are grouped as one and assigned to a particular cluster. In this project I have created 4 clusters which will result in 4 warehouses and these warehouses will contains various similar(based on distance) outlets. Project flow goes as, First I scraped pizza-hut website for outlet data and downloaded california population data from USA government sensus website followed by conversion of City names to Longitude and Latitude using geopy for calculating haversine metric in k-means clustering after this I implemented k-means clustering from scratch as scikit-learn's K-means clustering does not support haversine distance directly followed by certain error metric and plotting and at last I plotted outlet along with clusters on california(USA) map for better intuition.

	
## Technologies
Project is created using:
* Beautiful Soup
* Numpy
* Pandas
* Requests
* Matplotlib
* Geopy
* Sklearn
* mpl_toolkits
