# New-Year Eve's Resolutions

## Table of Contents
- [Overview](#overview) 
- [Project objectives](#project-objectives)
- [Metadata](#metadata)
- [Data Description](#data-description)
- [Tool Used](#tool-used)
- [Process](#process)
- [Findings  and Insights](#findings-and-insights)
- [Conclusion](#conclusion)
- [ Recommendations for Future Analysis](#recommendations-for-future-analysis)

## Overview

This project focuses on analyzing New Year's Eve resolutions shared on Twitter in 2015. The dataset consists of tweets containing resolutions made by users, along with metadata such as the date and time of the tweet, geographic location, original text, and the resolution category. The goal of the project is to uncover insights into the most popular resolution categories, the timing of tweets, and the geographic distribution of these resolutions within the United States.

The analysis was conducted using **Microsoft Excel** for data cleaning, analysis, and visualization. The project involved several steps, including data cleaning, aggregation, and visualization, to answer key questions about the dataset.

![Screenshot (10)](https://github.com/user-attachments/assets/ea84d162-7f7b-43ed-a918-5d90d22367be)


## Project objectives

The primary objectives of this project were:

1. Identify the most and least popular resolution categories based on the number of tweets.
2. Determine which resolution category was retweeted the most and least.
3. Analyze the timing of tweets to find the most popular hour of the day for tweeting resolutions.
4. Visualize the geographic distribution of tweets within the United States to identify which state had the highest number of New Year's Eve resolution tweets.


## METADATA
- **File Types**: CSV
- **Data Structure**: Single table
- **Number Of Records** : 4,723
- **Number Of Fields**: 10
- **Date Added**: 12/08/2020
- **Source**: data.world

##  Data Description

The dataset contains the following fields for each tweet:

- Date & Time: The timestamp when the tweet was created.
- Geographic Location: The location from which the tweet was sent (including U.S. states).
- Original Text: The content of the tweet, which includes the New Year's resolution.
- Resolution Category: The category to which the resolution belongs (e.g., personal growth, finance, career, etc.).


## Tool Used

   -  **Microsoft Excel**: Used for data cleaning, analysis, and visualization.

     
## Process

 ### 1. Data Cleaning
- Removed duplicate: Ensured that no duplicate tweets were included in the analysis.
- Ensured proper data types: Verified that each column (e.g., date, time, category) had the correct data type for accurate analysis.
- Filtered U.S. states: Focused on tweets originating from the United States for geographic analysis.

 ### 2. Data Analysis
- Aggregated tweets by category: Calculated the total number of tweets for each resolution category to determine the most and least popular categories.
- Aggregated retweets by category: Calculated the total number of retweets for each category to identify the most and least retweeted resolutions.
- Grouped tweets by hour: Rounded the tweet creation time to the nearest hour and calculated the number of tweets per hour to determine the most active hour for tweeting resolutions.
- Filtered by U.S. states: Identified which U.S. state had the highest number of resolution tweets.

 ### 3. Data Visualization
- **Line chart**: Used to visualize the number of tweets by hour of the day.
- **Bar chart**: Used to compare the number of retweets across different resolution categories.
- **Map visualization**: Used to display the geographic distribution of tweets acros **U.S. states**.

## Findings and Insights
	
### 1. Most and Least Popular Resolution CategorieS
   - The most popular resolution category was **Personal Growth**, with **1,678 tweets**.
   - The least popular category was **Philanthropic**, with only **83 tweets**.

### 2. Most and Least Retweeted Categories:
   - The most retweeted category  was **Finance**, with a total of **5,025 retweets**.
   - The least retweeted category was **Career**, with only **10 retweets**

### 3. Most Active Hour for Tweeting Resolutions:
   - The highest number of tweets occurred between **8:00 AM and 9:00 AM** with a total of  **505 tweets**.

### 4. U.S. State with the Most Tweets:
   - The state with the **highest number of resolution tweets** was **Illinois (IL)**, with **19 tweets**.

---

## Conclusion

This project successfully analyzed New Year's Eve resolution tweets from 2015, providing insights into popular resolution categories, retweet behavior, and the timing and geographic distribution of tweets. The use of Excel for data cleaning, analysis, and visualization proved effective in uncovering these insights. The findings can be useful for understanding social media trends related to New Year's resolutions and for planning targeted campaigns or content based on popular categories and peak engagement times.

---

## Recommendations for Future Analysis

1. **Expand the dataset**: Include data from multiple years to identify trends over time.
2. **Incorporate sentiment analysis**: Analyze the sentiment of the tweets to understand the emotional tone of resolutions.
3. **Explore additional geographic data**: Include international data to compare resolution trends across different countries.
4. **Use advanced visualization tools**: Consider using tools like Tableau or Power BI for more interactive and detailed visualizations.



  

     
 
