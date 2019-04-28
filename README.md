# Capstone-Final-Project-Ashwini
Capstone Final Project Ashwini
Project Title: Recommending the location to launch an Angel  
			Coffee Shop Based on K-means Algorithm


### 1.	Introduction

A Global Marketing Consultancy may be one of the challenging businesses to start among digital marketing platform industry. The planning, executing the needs of customers will help to create a successful business that will endure a time. So, to fulfil the customer needs, the key point location should be energy efficient. This project mentions the location to an entrepreneur to launch an Angel marketing consulting company in New York City using data science. Whenever people want to launch a new marketing consulting company, they must explore the location and try to fetch as much information as possible around it. It can be the neighbourhood, venues, etc., This can be named as request for a search algorithm which typically returns the requested features such as population rate, schools/colleges/offices around, weather conditions, recreational facilities etc. It would be beneficial to have an application which could make easy by considering a comparative analysis between the neighbourhood with provided factors.

2.	Data Section
New York City Neighbourhood Names point file from https://en.wikipedia.org/wiki/Neighborhoods_in_New_York_City
https://ibm.box.com/shared/static/fbpwbovar7lf8p5sgddm06cgipa2rxpe.json,
it has a total of 5 boroughs and 306 neighbourhoods
2.1 Foursquare API:
It has a database of more than 105 million places. This project would use Four-square API as its prime data gathering source.
2.2 Python Library Files:
•	Pandas - Library for Data Analysis

•	NumPy – Library to handle data in a vectorized manner

•	JSON – Library to handle JSON files

•	Folium – Map rendering Library

•	Matplotlib – Python Plotting Module

•	Geopy – To retrieve Location Data

•	Requests – Library to handle http requests

•	Sklearn – Python machine learning Library


2.3 Folium:
Python visualization library would be used to visualize the neighbourhoods cluster distribution of Chicago city over an interactive leaflet map. Extensive comparative analysis of two randomly picked neighbourhoods world be carried out to derive the desirable insights from the outcomes using python’s scientific libraries Pandas, NumPy and Scikit-learn.

3.	Methodology:

Once the neighbourhood GPS data has been acquired for any given city the foursquare API call can be used to acquire the 10 most common ‘Trending’ venues around each neighbourhood GPS point. The radius was set to 500m with a limit of 100 venues to be returned.
The returned venues are then grouped using a hot encoding method to display for top 5 venues for each neighbourhood. Refer table 2.
3.1 Unsupervised machine learning algorithm:¶
K-mean clustering would be applied to form the clusters of different categories of places in and around the neighbourhoods. Each of them would be analysed individually and comparatively to derive the best location.

4.	Results:
The most visited/common venue is the best location for opening new shop. This model identified 9 best locations to open a new coffee shop based on input.

5.	Discussion:

From the results, an entrepreneur can apply this model to any city and produce a best location suggestion without any prior knowledge of the city. The drawback of this system is location suggestion not considered population density and crime rate of the city. Using other end points may be a better solution.
