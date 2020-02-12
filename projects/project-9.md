---
layout: project
type: project
image: images/Personalized_Cancer_Diagnosis_icon.png
title: Personalized Cancer Diagnosis
permalink: projects/Cancer
# All dates must be YYYY-MM-DD format!
date: 2019-05-17
labels:
  - Machine Learning
summary: Classify the given Genetic variations/mutations based on evidence from text-based clinical literature.
---

<img class="ui image" src="../images/Personalized_Cancer_Diagnosis_Banner.png">

Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

For this competition MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations. We need your help to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.

<b>Problem Statement</b> : In this challenge, we are trying to classify the given genetic variations/mutations based on evidence from text-based clinical literature.

<b>Source</b> : [https://www.kaggle.com/c/msk-redefining-cancer-treatment/data](https://www.kaggle.com/c/msk-redefining-cancer-treatment/data)

<b>Data Description</b> : 

We have two data files : one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.

Both these data files are have a common column called ID

Data file's information :
training_variants (ID , Gene, Variations, Class)
training_text (ID, Text)

<b>Real-world/Business Objectives and Constraints</b> : 
1. No low-latency requirement.
2. Interpretability is important.
3. Errors can be very costly.
4. Probability of a data-point belonging to each class is needed.

To learn more please visit : [Here](https://github.com/Souravban/Personalized-Cancer-Diagnosis)
