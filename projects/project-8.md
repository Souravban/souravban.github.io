---
layout: project
type: project
image: images/Facebook_Friend_Recommendation_icon.png
title: Facebook Friend Recommendation
permalink: projects/Facebook
# All dates must be YYYY-MM-DD format!
date: 2019-07-25
labels:
  - Machine Learning
summary: Given a directed social graph, we are predicting missing links to recommend users.
---

<img class="ui image" src="../images/Facebook_Friend_Recommendation_Banner.png">

The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the aggregate rating of each restaurant, establishment of different types of restaurant at different places, Bengaluru being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world. With each day new restaurants opening the industry has'nt been saturated yet and the demand is increasing day by day. Inspite of increasing demand it however has become difficult for new restaurants to compete with established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don't have time to cook for themselves. With such an overwhelming demand of restaurants it has therefore become important to study the demography of a location. What kind of a food is more popular in a locality. Do the entire locality loves vegetarian food. If yes then is that locality populated by a particular sect of people for eg. Jain, Marwaris, Gujaratis who are mostly vegetarian. These kind of analysis can be done using the data, by studying different factors.

<b>Problem Statement</b> : In this challenge, Given a directed social graph, we have to predict missing links to recommend users (Link Prediction in graph)

<b>Source</b> : [https://www.kaggle.com/c/FacebookRecruiting/data](https://www.kaggle.com/c/FacebookRecruiting/data)

<b>Mapping the problem into supervised learning problem</b> : Generated training samples of good and bad links from given directed graph and for each link got some features like no of followers, is he followed back, page rank, katz score, adar index, some svd fetures of adj matrix, some weight features etc. and trained ml model based on these features to predict link.

<b>Real-world/Business Objectives and Constraints</b> : 
1. No low-latency requirement.
2. Probability of prediction is useful to recommend ighest probability links.

To learn more please visit : [Here](https://github.com/Souravban/Facebook-Friend-Recommendation)
