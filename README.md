# Sentiment Analysis in the banking sector using Twitter API, AWS Comprehend and AWS SageMaker

[![lisence](https://img.shields.io/github/license/cbarros7/sentiment-analysis-banking-sector?style=plastic)](https://github.com/cbarros7/sentiment-analysis-banking-sector/blob/master/LICENSE)

[![Twitter Carlos](https://img.shields.io/twitter/follow/cbarros27?label=CarlosBarros&style=social)](https://twitter.com/cbarros27)

## Description :speech_balloon:
According to the 2019 report published by the company DOMO (give link 1) in which they study the amount of data collected in each minute states that people are tweeting their thoughts at 511,200 tweets per minute.

This project aims to share source code for sentiment analysis in the banking sector using the Twitter API, AWS Comprehend and AWS SageMaker.

**What is the objective with this project?**  In this project, three fundamental questions are posed:

* Which bank has the highest number of tweets?
* What is the customer's perception of the city where the bank is headquartered?
* What is the perception of the clients classified by city?

## Tools :hammer:
The tools used to develop the project were:


![jupyter_python_numpy width-808](https://user-images.githubusercontent.com/60367519/80153609-7e09c180-8583-11ea-80da-ccaffb4b8889.png)


To carry out the above, it has been decided to take the following structure in the project: 

## Project structure :notebook_with_decorative_cover:

### Data acquisition and cleaning
#### Data sources
The data is extracted from the Twitter API. Because 3 banks are analyzed, each one represented in totally different datasets, it is also worth adding that the tweets were taken into account, the date that was published and the place of origin (SEE TABLE 1). Later on, new columns are added with the different types of positive, negative and neutral score respectively. 



#### Data cleaning
For this phase of exploratory analysis it is fundamental to check the existence of null values and for this case in the column "location" there are 10 null values (SEE TABLE 2). In this way the data is cleaned (SEE TABLE 3). 



### Exploratory Data Analysis
#### Bancolombia
The data generated through the twitter API with the hashtag #bancolombia, extracted a total of 59 tweets, however, in the process of data cleaning, explained in the section data sources, the dataset was left with 49 tweets. The date is in the range of 06/16/2020 to 06/23/2020. In CHART 2, the main cities can be seen, being Bucaramanga the one with the highest negative score with an average of 0.8217, followed by Cartagena, Cali and Medellín with 0.5923, 0.4703 and 0.3444 respectively. 



## Authors :black_nib:
**Carlos Barros** [Portfolio](https://carlosbarros.netlify.app/)
                  [Github](https://github.com/cbarros7)
                  [LinkdIn](https://www.linkedin.com/in/carlosbarros7/)
                  [Tableau Public](https://public.tableau.com/profile/carlos.barros#!/?newProfile=&activeTab=0)
