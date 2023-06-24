# SA-Languagues

### Table of Contents
[1) Overview](#1-overview)     
[2) Dataset Description](#2-Dataset-Description)   
[3) File Descriptions](#3-File-Descriptions)  
[4) Language IDs](#4-Language-IDs)  
[5) Rules for the Kaggle Competition](#5-Rules-for-the-Kaggle-Competition)


## 1) Overview
South Africa is a multicultural society known for its rich linguistic diversity. Language plays a crucial role in deepening democracy and contributing to the social, cultural, intellectual, economic, and political life of the country. With 11 official languages, South Africans are multilingual, often fluent in two or more languages. As a result, our systems and devices also need to be able to communicate in multiple languages.

In this challenge, the goal is to identify the language of a given text, which can be written in any of South Africa's 11 official languages. This task falls under the realm of Natural Language Processing (NLP) and specifically focuses on Language Identification, i.e., determining the natural language in which a piece of text is written.
From [South African Government](https://www.gov.za/about-sa/south-africas-people)
![image](https://github.com/Cephas-Peter/SA-Languagues/assets/82019073/9c718353-8b90-4234-b56a-a4c878e30601)


With such a multilingual population, it is only obvious that our systems and devices also communicate in multi-languages.

In this challenge, you will take text which is in any of South Africa's 11 Official languages and identify which language the text is in. This is an example of NLP's Language Identification, the task of determining the natural language that a piece of text is written in.

[Image credit](https://bilingua.io/how-to-say-hello-in-100-languages)

## 2) Dataset Description
The dataset used for this challenge is the NCHLT Text Corpora collected by the South African Department of Arts and Culture & Centre for Text Technology (CTexT, North-West University, South Africa). The training set was improved through additional cleaning done by Praekelt.


The data is in the form Language ID, Text. The text is in various states of cleanliness. Some NLP techniques will be necessary to clean up the data.

## 3) File descriptions
test_set.csv: The test set containing unlabeled text entries.   
train_set.csv: The training set consisting of labeled text entries for model training.   
sample_submission.csv: A sample submission file demonstrating the correct format for submitting predictions.

## 4) Language IDs
afr - Afrikaans 
eng - English  
nbl - isiNdebele  
nso - Sepedi  
sot - Sesotho  
ssw - siSwati  
tsn - Setswana  
tso - Xitsonga  
ven - Tshivenda  
xho - isiXhosa  
zul - isiZulu  

## 5) Rules for the Kaggle Competition
This is a private hackathon whose primary purpose is for the members of the EXPLORE Data Science Academy to apply what they have learned. If you are part of EDSA contact your mentor for the secret code.

You may use only the datasets provided within this competition. Your solution must use machine learning with an emphasis on classification analysis and related techniques.

Participation within this competition occurs on an individual basis for all students.

Multiple accounts per user are not allowed. Collaboration between individuals is not allowed.

You are not allowed to share your solution code, except where EDSA staff or instructions explicitly request you to do so.

The solution must use publicly available, open-source packages only. Maximum 20 solutions submitted per day. Your highest-scoring solution will be the one by which you are judged.
