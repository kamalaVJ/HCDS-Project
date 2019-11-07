
## Title: What makes trending Youtube videos REALLY trending?

## Motivation & Problem Statement
I am interested in finding out what  factors make popular or viral youtube videos go viral. I also want to find out if these factors vary from country to country and how so. While the former part of my question involves a large amount of quantitative analysis. I aim to incorporate some qualitative study to understand exactly why or how these factors differ. It would be interesting to find out if there is a difference category wise, region wise or if it's simply based on the most trending topics on youtube overall. The goal is to extract as much information as possible about the users and content creator associations on Youtube.In order to determine the factors, I will implement Linear regression models due to ease of interpretability of the outcomes.
I believe that insights from this research study will hold value for two groups mainly, the viewers and the content creators. Creators can have a better understanding of what governs the popularity of their video and how they can change/incorporate their current content publishing practices. Viewers can (hopefully) learn to differentiate between click-bait thumbnail videos and gain clarity on how to identify the trending videos in each category.
## Data 
Data : Collected from Youtube API  
Data source: https://www.kaggle.com/datasnaek/youtube-new  
Licence: CC0 Public Domain  
This dataset contains all the information related to the top trending/viral Youtube videos region wise. It contains information of about 200 trending videos per day for several months in different regions(USA, Great Britain, Germany, Canada,France,Russia, Mexico, South Korea, Japan and India) such as:   
video_id  
trending_date  
title  
channel_title  
category_id  
publish_time  
tags  
views  
likes  
dislikes  
comment_count  
thumbnail_link  
comments_disabled  
ratings_disabled  
video_error_or_removed  
description  
I would be using a subset of the data as it is a very huge dataset(514 MB)

## Possible bias/dependencies in Data
As I aim to determine what factors make a Youtube video popular overall and in each country, this analysis may inherently be dependent on the privacy laws and laws governing mass media and communication, the censor board laws and so on, of each region. So there is a possibility that the results cannot be completely generalized to all regions. I also suspect that access to internet and technology among the population would vary between each region and this would also be a governing factor in which videos make it to the top trending list. I will aim to include some qualitative research as well to the outcomes I find in my analysis.
 


