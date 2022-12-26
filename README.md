# Wrangle and Analyze Twitter Data

## Introduction
Real-world data rarely come clean. Using Python and its libraries, we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. We will document our wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.
The dataset that we will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.
The purpose and goal of this project are to create a trustworthy and interesting analysis and visualization based on the wrangled data.

## Project Details
This part of the project is divided into three steps, which are as follows:
- Data Gathering
- Data Assessment
- Data Cleaning

## Data Gathering
This project requires working on three different datasets, which are acquired as follows:
• Twitter archive: The twitter_archive_enhanced dataset is a csv file that was given by Udacity to be downloaded manually from their side, uploaded into the Jupyter notebook, and read into a panda’s DataFrame.
• Tweet image predictions: This file (image_predictions.tsv) is present in each tweet according to a neural network. It is hosted on Udacity's servers and should be downloaded programmatically using the Requests library.
• Twitter API and JSON: We used Udacity’s ready-scrapped Twitter data, which was stored in txt file, we have extracted the important data (tweet-id, retweet-count, and favorite-count) and stored it in a separate DataFrame.

## Data Assessment
After gathering all three pieces of data, assess them visually and programmatically for quality and tidiness issues. Visually by displaying data in the Jupyter Notebook and in Excel sheets. And programmatically by using pandas' functions and/or methods used to assess the data.
