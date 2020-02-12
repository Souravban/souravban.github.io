---
layout: project
type: project
image: images/Quora_Question_Pair_Similarity_icon.png
title: Quora Question Pair Similarity
permalink: projects/Quora
# All dates must be YYYY-MM-DD format!
date: 2019-07-01
labels:
  - Machine Learning
summary: Identify which questions asked on Quora are duplicates of questions that have already been asked.
---

<img class="ui image" src="../images/Quora_Question_Pair_Similarity_Banner.png">

Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

<b>Problem Statement</b> : In this challenge, we have to Identify which questions asked on Quora are duplicates of questions that have already been asked. This could be useful to instantly provide answers to questions that have already been answered. We are tasked with predicting whether a pair of questions are duplicates or not.

<b>Source</b> : [https://www.kaggle.com/c/quora-question-pairs/data](https://www.kaggle.com/c/quora-question-pairs/data)

<b>Data Description</b> : 

Data will be in a file Train.csv <br>
Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate <br>
Size of Train.csv - 60MB <br>
Number of rows in Train.csv = 404,290

<b>Real-world/Business Objectives and Constraints</b> : 
1. The cost of a mis-classification can be very high.
2. You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
3. No strict latency concerns.
4. Interpretability is partially important.

To learn more please visit : [Here](https://github.com/Souravban/Quora-Question-Pair-Similarity)
