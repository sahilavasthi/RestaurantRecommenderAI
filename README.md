# Project Name
RestaurantRecommenderAI


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Project Background:
In today's digital age, a Restaurant Recommender is an intelligent system designed to suggest restaurants based on user preferences, location, cuisine preferences, reviews, and other factors. Using machine learning and data analysis, it tailored recommendations to individual tastes, ensuring users discover new and highly rated dining experiences. Whether you're searching for a hidden gem, a trendy spot, or a budget-friendly option, a Restaurant Recommender makes dining decisions effortless and personalized. 
### Project Goal:
To address this, we will develop RestaurantRecommender AI, a chatbot that combines the power of large language models and rule-based functions to ensure accurate and reliable information delivery.
### Problem Statement:
Given Zomato restaurants dataset from Kaggle containing information about restaurants (restaurant names, restaurant types, rating, average cost, cuisine type, area etc.), I will build a chatbot that parses the dataset and provides accurate restaurants recommendations based on the user requirements.

### Approach:
1.	Conversation and Information Gathering: The chatbot will utilize language models to understand and generate natural responses. Through a conversational flow, it will ask relevant questions to gather information about the user's requirements.
2.	Information Extraction: Once the essential information is collected, rule-based functions come into play, extracting top 3 restaurant that best matches the user's needs. We will be using function calling to extract information from the csv file & for data comparisons
3.	Personalized Recommendation: Leveraging this extracted information, the chatbot engages in further dialogue with the user, efficiently addressing their queries and aiding them in finding the perfect restaurant

Link to dataset: https://www.kaggle.com/datasets/abhijitdahatonde/zomato-restaurants-dataset

## Conclusions
Appropriate results are achieved,

The chatbot recommends the list of restaurants to the user that have passed the validation layer and provides further feedback to find the best possible solution
In case, no restaurants pass the validation layer, the chatbot ends the conversation and recommends connecting to a human expert

## Technologies Used
- Python - version 3.10
- Pandas - version 2.2.2
- OpenAI - version GPT 4.1

## Acknowledgements
TensorFlow, Pandas, Medium, Stackoverflow, OpenAI Docs, Cohere

## Contact
Created by [@sahilavasthi] - feel free to contact me!