# Onebyte

![onebyte](https://user-images.githubusercontent.com/74225074/225815174-f17b930d-568b-4121-bd7f-136a3d21de6a.png)


## Overview

Onebyte is a Python project that performs data analytics on the reviews and ratings of pizza restaurants from the One Bite website. The website is a repository of all the pizza reviews conducted by Dave Portnoy, as well as the scores given to pizza restaurants by users of the One Bite app.

The project aims to provide insights into the ratings and reviews of pizza restaurants, by analyzing the data scraped from the website. The data includes restaurant names, locations, Yelp scores, Dave's scores, the average user score found within the app, number of user reviews, number of Yelp reviews, and date of Dave's review.

## Features

### Data Scraping

The ScrapeOneBite.ipynb script performs data scraping of the One Bite website to collect the data mentioned above. The script uses the Python requests library to send HTTP requests to the website, and BeautifulSoup to extract the relevant information from the HTML pages.

The script also requires a personal Google API Key to retrieve location data for each restaurant. Once the script is run, it takes around 10-15 minutes to scrape the entire website, and outputs the data as a CSV file (~2000 entries).

The collected data can be used for further analysis using other tools and techniques such as machine learning, data visualization, and statistical analysis.

The youtubevideos.ipynb script is used to obtain the latest video statistics from the One Bite YouTube channel. You will need to provide your personal YouTube Data API Key to run this notebook. Please note that there may be rate limits associated with using the API, which may require payment to bypass. The output data is saved as a CSV file.


### Data Analysis
The GraphingData.ipynb script is used to perform analysis on the data collected by the ScrapeOneBite.ipynb script. The script uses Python libraries such as pandas, numpy, and matplotlib to perform statistical analysis, generate graphs, and visualize the data in various ways.

The script provides insights into the distribution of pizza restaurant ratings and the factors that influence ratings, such as location, restaurant type, and user reviews. The data analysis can help businesses in the food industry to make informed decisions about their products, marketing strategies, and operations.

## Usage
To use this project, you will need to have Python 3.x and the following libraries installed: requests, BeautifulSoup, pandas, numpy, googlemaps, google-auth, google-auth-oauthlib, google-auth-httplib2, and google-api-python-client.


## Contributing
Contributions to this project are welcome. Please feel free to submit pull requests or raise issues if you encounter any bugs or have suggestions for improvements.

