# WeRateDogs-Wrangling-Analysis
 Wrangle and Analyze Data
Udacity Data Analyst July 2022 - October 2022

Project 2: Wrangle and Analyze Data - WeRateDogs twitter account

# Project Overview
## Introduction
This project is a qualification for the Udacity Data Analysis Nanodegree (DAND). Its goal is to showcase expertise in the Data Wrangling stage of the Data Analysis Process. Three different types of data sources were provided to us for this project, and we approached each one in a unique way. Then we tried to asses our data visually and with programming in order to collect the different issues (Quality and Tideness). I was able to collect 8 quality problems and 2 tideness issues, which I cleaned afterwards. Finally, I was able to draw a variety of inferences and observations regarding the WeRateDogs Dataset thanks to this process.

## About the data
The tweet history of Twitter user @dog rates, better known as WeRateDogs, is the dataset I will be dealin with (wragling, studying and visualizing). WeRateDogs is a Twitter account that rates users' dogs and adds light hearted joke abou the puppies. The denominator of these ratings is almost always 10. H owever, the numerators? frequently over 10. 11/10, 12/10, 13/10, etc. Why? because "hey're good dogs Brent."  The sentence has even gained notoriety as a meme.

![image](https://user-images.githubusercontent.com/83359499/191959082-76ced852-0898-4aa0-93e0-7d4299fcf200.png)

Over 6 million people follow WeRateDogs, and it has been featured in international media.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets.

## What Software Do I used?

![image](https://user-images.githubusercontent.com/83359499/191959253-dbbccb7b-409b-4859-ae85-e6b906feaac1.png)

-Jupyter Notebook (Anaconda)
- The following packages (libraries) need to be installed (via conda or pip). 
  - pandas
  - NumPy
  - requests
  - tweepy
  - json

# Project Specifications

## Gathering Data

![image](https://user-images.githubusercontent.com/83359499/191959320-79e51d57-4625-4ff9-9ffb-b360fec0dbd3.png)

The first source of data was a csv file that contained Twitter WeRateDogs Archives. The retrieval of this data was the easiest of the three because all that was required was to click on the URL supplied to open csv file and save it to the current working directory. The second source was a machine learning algorithm's prediction findings after training on a sample of archived tweet data's image data. Similarly, the collection of this file was super easy. To get the third source we were required to utilize Tweepy to query the Twitter API in order to obtain more data beyond what is contained in the WeRateDogs Twitter archive. Understanding the structure of the tweet object JSON was our first challenge to overcome in the data wrangling process.
**Data is successfully gathered! NEXT..**


## Assessing Data

![image](https://user-images.githubusercontent.com/83359499/191959410-ce93851c-1287-4c9b-b3d8-7c6009addd8f.png)

A visual assessment and a programmatic assessment were both conducted after the data gathering. 
   - Visual assessment: each piece of gathered data is displayed in the Jupyter Notebook for visual assessment purposes. Once displayed, data can additionally be assessed in an external application (e.g. Excel, text editor).
   - Programmatic assessment: pandas' functions and/or methods are used to assess the data.
During the visual assessment stage, we noticed issues ranging from the individual categories of a variable being split across four columns (dog_stages) to the HTML tags surrounding the name of the platform from which the tweet was made. We were able to identify more subtle problems with quality and orderliness thanks to programmatic assessment, including duplicate data, the existence of meaningless data, and wrong datatype for some columns.


## Cleaning Data

![image](https://user-images.githubusercontent.com/83359499/191959468-3f297361-7523-4443-951d-4a253f1f8ed1.png)

The cleaning part is always my favourite; In fact, I think that the define-code-test procedure described in the lessons and that I applied to clean the data was really benificial and helped me providing a structured report. The majority of the quality and structure issues were simple to clean. Some of the tidiness and quality flaws, however, proved more difficult to fix. The main difficulty we ran into when cleaning the data was extracting the correct information from each tweet's text because there were so many scenarios that needed to be taken into account.

Even though I made numerous edits to the cleaning section, in the end, this procedure helped me to acquire useful information about the data that made it simple for me to create visualizations.

## Storing and Acting on Wrangled Data

![image](https://user-images.githubusercontent.com/83359499/191959560-c274d204-fb25-4287-988c-b618ddb84ebc.png)

After the cleaning step, the new data was stored in a csv file. Few insgihts and visualizations were made.
