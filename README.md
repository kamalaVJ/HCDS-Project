### Project Proposal
## Title: What makes trending Youtube videos REALLY trending?

## Motivation & Problem Statement
I am interested in finding out what  factors make popular or viral youtube videos go viral. I also want to find out if these factors vary from country to country and how so. While the former part of my question involves a large amount of quantitative analysis. I aim to incorporate some qualitative study to understand exactly why or how these factors differ. It would be interesting to find out if there is a difference category wise, region wise or if it's simply based on the most trending topics on youtube overall. The goal is to extract as much information as possible about the users and content creator associations on Youtube.In order to determine the factors, I will implement Linear regression models due to ease of interpretability of the outcomes.
I believe that insights from this research study will hold value for two groups mainly, the viewers and the content creators. Creators can have a better understanding of what governs the popularity of their video and how they can change/incorporate their current content publishing practices. Viewers can (hopefully) learn to differentiate between click-bait thumbnail videos and gain clarity on how to identify the trending videos in each category.


## Data 
Data : Collected from Youtube API  
Data source: https://www.kaggle.com/datasnaek/youtube-new (https://github.com/DataSnaek/Trending-YouTube-Scraper)**    
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
I would be using a subset of the data as it is a very large dataset(514 MB)

## Dataset License
Licence: BSD 2-Clause "Simplified" License ** 

## Possible bias/dependencies in Data
As I aim to determine what factors make a Youtube video popular overall and in each country, this analysis may inherently be dependent on the privacy laws and laws governing mass media and communication, the censor board laws and so on, of each region. So there is a possibility that the results cannot be completely generalized to all regions. I also suspect that access to internet and technology among the population would vary between each region and this would also be a governing factor in which videos make it to the top trending list. I will aim to include some qualitative research as well to the outcomes I find in my analysis.

## Research questions and/or hypotheses   
1) What are the factors that determine the popularity of a youtube video? How do these vary in each category?
2) How do these factors vary from country to country?

## Background and/or Related Work  
It is known that youtube videos released by channels/creators with high number of subscribers receive more views,likes,comments and therefore become popular/trending. There are probably many analyses of the like that try to determine which factors control the popularity. However, the aim of this project is to see how these factors differ from country to country and why do they differ? Can these differences be reasoned by statistics pertaining to the demography in each country or is there more to it? Are socio-economic or political atmosphere of the country have a role as well? The aim is to also observe how the popularity factors vary from category to category. Thsi analysis will also include some qualtitative insights presented along with the statistical inferences.
There are several kernels that have used this dataset for analyses, although I have described how and why my analyses will be different from the existing ones, the exploratory data analyses might be similar due to the nature of data and prevailing assumptions.

## Methodology  
* Pre-processing  
A subset of the data will be used for the analyses. The size of this subset will be decided after performing some exploratory data analysis to understand how sparse/not sparse is the data. To determine how these factors vary over different categories, a set of 5-10 categories will be chosen for comparison.
* Statitical Analysis Method    
Linear Regression models will be used to train and determine the predictors. This method is appropriate as all the data points are independent and the sample size is large enough to meet the normality assumption. This also provides ease in interpreting the results and verifying the correlations statitiscally.
* Result  
The results will be presented in a comprehensive compilation of visualizations and comparison tables.
 
** Updated License and source to original source inplace of kaggle

