---
title: "Newer work"
layout: single
permalink: /newer-work/
author_profile: true
---

## [A topic and sentiment analysis of Amazon music reviews](https://github.com/walkermoskop/Amazon-music-review-sentiment-and-topic-analysis)  

For an NLP project, I used [Latent Dirichlet Allocation](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) to group 100,000 Amazon music reviews into a set of distinct topics. I also performed a sentiment analysis of the reviews, all of which were scored on a 1-5 scale (1-2 were assumed as negative, 4-5 were labeled as positive, and neutral 3-star reviews were removed). For the sentiment analysis, I experimented with using a support vector machine classifier, Naive Bayes and regularized logistic regression.

## [A county-level analysis of COVID fatality rates in Midwestern states](https://github.com/walkermoskop/covid-fatality-analysis)

Using linear mixed effects models to evaluate the extent to which policy measures intended to slow COVID helped explain variation in fatality rates across Midwestern counties.

## [Visualizing eight years of Giannis Antetokounmpo's shot data](https://github.com/walkermoskop/Giannis-Antetokounmpo-Shooting-Analysis/blob/main/giannis-shooting-analysis.ipynb)

I took raw data for all of Giannis' career shots and built a variety of shot charts looking at how his shot selection and shooting efficiency have changed as his career has progressed.

## [Finding an optimal route between cities](https://github.com/walkermoskop/Best-Route-Finder)

For an [Elements of AI course](https://luddy.indiana.edu/academics/courses/class/iub-fall-2020-csci-b551#:~:text=CSCI%2DB%20551%20ELEMENTS%20OF%20ARTIFICIAL%20INTELLIGENCE%20(3%20CR.)&text=Principles%20of%20reactive%2C%20goal%2Dbased,%2C%20reasoning%20under%20uncertainty%2C%20planning.) I took in my data science program, I wrote a python script that uses [A* search](https://en.wikipedia.org/wiki/A*_search_algorithm) to find the most efficient route between destinations in a variety of scenarios.

## [Building a Naive Bayes classifier from scratch](https://github.com/walkermoskop/Naive-Bayes-tweets-classifier)

I built a naive bayes classifier to model and predict locations of tweets based on the text in the tweets. This project involed processing, tokenizing and vectorizing the raw text of tweets from a training file, which was then used to build a model that accurately classifies about 68% of the locations in an unseen test dataset.

## [Analyzing property values in Milwaukee neighborhoods](https://github.com/walkermoskop/mke_neighborhood_home_values)

I downloaded a dataset of [Milwaukee single family home assessed values](https://data.milwaukee.gov/dataset/mprop) (I know these don't always accurately capture market value, but it's the best free, publicly available dataset available for all city parcels) and joined in a variety of Census economic and demographic data as well as [crime statistics](https://data.milwaukee.gov/dataset/wibr) to build a regression model to 1) examine what variables appeared most influential in understanding property values and 2) give a sense of which neighborhoods had median values that were above/below what the model expected.