---
layout: project
type: project
image: images/Titanic_Survival_Prediction_icon.png
title: Titanic Survival Prediction
permalink: projects/Titanic
# All dates must be YYYY-MM-DD format!
date: 2019-04-25
labels:
  - Machine Learning
summary: Predicting what sorts of people were more likely to survive on Titanic.
---

<img class="ui image" src="../images/Titanic_Survival_Prediction_Banner.png">

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

<b>Problem Statement</b> : In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

<b>Source</b> : [https://www.kaggle.com/c/titanic/overview](https://www.kaggle.com/c/titanic/overview)

<b>Data Description</b> : 

<b>pclass</b> : A proxy for socio-economic status (SES) 1st = Upper; 2nd = Middle; 3rd = Lower;

<b>age</b> : Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5;

<b>sibsp</b> : The dataset defines family relations in this way...

<b>Sibling</b> = brother, sister, stepbrother, stepsister

<b>Spouse</b> = husband, wife (mistresses and fiancés were ignored);

<b>parch</b> : The dataset defines family relations in this way...

<b>Parent</b> = mother, father

<b>Child</b> = daughter, son, stepdaughter, stepson

<b>Some children travelled only with a nanny, therefore parch=0 for them.</b>

<b>Real-world/Business Objectives and Constraints</b> : 
1. The cost of a mis-classification not very high.
2. No strict latency concerns.

To learn more please visit : [Here](https://github.com/Souravban/Titanic-Survival-Prediction)
