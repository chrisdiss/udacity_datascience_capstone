# udacity_datascience_capstone
This repository has all the code and report for my Udacity Data Scientist Nanodegree Capstone project.
For a full report visit my [blog post](https://christoph-emmert.medium.com/how-to-understand-starbucks-customers-and-individualize-promotional-offers-26cbcd234e4a).

## Objective & overview
Goal of the project is to analyze data from Starbucks about their consumer behaviour regarding to certain offer strategies. It should be analyzed which offer strategies apply to which group of customers best, if there is a significant difference between groups. With this in mind Starbucks could gain insights about the way how to best promote and offer coupons and increase the efficacy of such offers.

First, it is necessary to get familiar with the data and to perform some data wrangling and cleaning. After this some descriptive and some more advanced statistical analyses will be done to find possible insights in the data. The insights will be supported with useful visualizations.

## Installation
For running this project, the most important library is Python version of Anaconda Distribution. It installs all necessary packages for analysis and building models.

## Data
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer which makes this project a challenge.

## File Descriptions
This repo contains 4 files.There is a notebook available here to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above qustions

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Conclusion

To see the bigger picture it was necessary to deep dive into the data and into single steps. For me starting point of the analysis was to see if the user journey from receiving an offer to viewing and completing it has some special characteristics to inform further offer strategies.

Looking at a user level it can be seen that women tend to be a more lucrative source for Starbucks as they tend to have a higher completion rate of the offers and also have a higher average transaction value. Also income seems to increase for the users that complete an offer. Interestingly men have a slightly higher increase which could make men with a higher income a potential target for new offers.

Compared to the descriptive analysis made the implication that women have a higher completion rate was true which makes them potentially interesting for placing some kind of promotional offers. Also interestingly a small difference can be observed in the offer type insights. Especially men can be reached in a more succesful way by offering a discount. The descriptive analysis showed that discounts have a higher completion rate whereas the recommendation system provides information that bogo and discount have more or less the same chance of success in women and others. Only within the male user group discounts perform clearly better. Looking at the distribution channels we can provide information that leads to the assumption that social performs best. Only looking at the ten different offers the one that performs best is "buy 10 dollars get 2 dollars off within 10 days".

To sum up, to increase the offer effectiveness Starbucks could focus on female users using the web channel and offering more discounts.

## Licensing, Authors, Acknowledgements, etc.
Data for coding project was provided by Udacity.
