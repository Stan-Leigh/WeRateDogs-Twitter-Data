# WeRateDogs-Twitter-Data
## Introduction
This project is part of Udacity's Data Analyst nanodegree projects. It was designed to test the students ability to gather, assess and clean data following the Data Wrangling process. 

## Data Wrangling
The Data Wrangling process consists of three stages:
> 1. Gather stage
>
> 2. Assess stage
>
> 3. Clean stage


#### Gather stage
This is the stage where the data relevant to your analysis is collected. The datasets were gathered from three sources. The first piece of the dataset was available locally on my device. The second piece of dataset was on a web server and it was gatheres using the *requests* library. The third piece of data was gotten from the WeRageDogs Twitter page. This data was gathered by using Twitter's API and the *tweepy* library for importing tweets to query and get the data.

#### Assess stage
The next stage of my Data wrangling was to assess the data. This is divided into two; **Visual assessment** and **Programmatic assessment**. Visual assessment entails looking through the data with your eyes to check if you can spot anything wrong with the data. Programmatic assessment entails using the pandas package and python's libraries and functions to check for **Completeness** (checking if the data is complete without missing values), **Validity**(checking if the data is in the correct format), **Accuracy**(checking if the data was inputted correctly without mistakes) and **Consistency**(checking if the data follows a standard throughout). The problems that were identified were divided into **Dirty data**(data that has issues with its content, quality issues) and **Messy data**(data that has issues with its structure, tidiness issues) and written down. Some of the issues identified in the datasets are;
1. Null values in some of the columns.
2. Inaccurate names of dogs.
3. Incorrect data types for some columns.
4. Unnecessary text in some columns that needed to be removed.
5. Inconsistent case in some columns.
6. Column names that were not descriptive enough

#### Clean stage
The last stage of my Data wrangling process was to clean the data. This was the stage where I acted on the issues that was discovered in the Assess stage. Before starting the actual cleaning, I created copies of the datasets so that I would have something like a backup of the data incase something goes wrong while cleaning the data.

## Analysis 
After wrangling the data and storing the assessed and cleaned dataset, it was time to analyze the data to generate insights. Before starting the analysis, I generated five questions that I would use the dataset to answer. These questions were;

1. What breed of dog is the most popular (number of times a breed of dog is rated) in this dataset?

2. What breed of dog is liked/favorited overall?

3. Is there a relationship between number of words/characters in a text and favorite_count?

4. Where does WeRateDogs tweets originate from the most?

5. How are tweets distributed by weekday and by month?

## Conclusions
After generating visualizations to answer the questions posed above, I arrived at the following conclusions;
1. The Golden Retriever is the dog breed that has been rated the most on WeRateDogs.

2. The Golden Retriever is also the dog breed with the highest favorite count.

3. There is very little/ no correlation between number of text characters and favorite count.

4. Most of the tweets on WeRateDogs originated from one source (Twitter for iPhone).

5. Monday is the busiest weekday with more tweets rolling out on this day. December is also the busiest month, with more tweets rolling out in this month.

## Summary
In this project, we went through all the stages of the Data Wrangling process, from gathering the data from three different sources (locally, from a website and gathering data from an API), to assessing the data to identify errors and inconsistencies in the data, to cleaning the data using pandas/python's functions and modules. After, we analyzed the data and visualized it in order to generate insights.
