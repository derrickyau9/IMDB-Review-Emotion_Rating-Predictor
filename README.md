# IMDB-Review-Emotion_Rating-Predictor
ISE 540 Text Analytics Final Group Project 

# Inferring Reaction Tags from the IMDB Movie Reviews Dataset
Team Members: Yifu Shao, Chenxi Zhang, Fangyi Wang, Derrick Yao

# Dataset: IMDB Movies Dataset
Link: https://huggingface.co/datasets/imdb

# Background and Significance:
Annually, thousands of movies compete for attention in a digitalized market. The accelerated process of digitizing material consumption has resulted in a significant proportion of audience members expressing their reviews through online channels, such as IMDB. The insights behind these reviews have the potential to inform decision-making in studios, improve review suggestions by considering emotional impact, and provide a more comprehensive understanding of the movies. reaction-centric analysis can tailor movie recommendations, guide content production, and highlight the range of viewer emotions.

# The Problem Statement:
We aim to infer the emotion tags of each individual review and give an audience star rating based on the emotions conveyed. The existing labels within the dataset serve to classify reviews as either positive or negative, which may inadvertently obscure a range of moods, themes, and issues. The fundamental challenge of this project is to understand the underlying emotions and estimate the probability of diverse emotions in the texts, such as happiness, sadness, disgust, fear, surprise, anger, etc. It’s common that there are multiple emotional themes in one single review, we have to dive deep into the text and find out the answer. Then we will infer the star rating (from 1 to 5 stars) of the movie from the perspective of an audience according to the emotional themes. The star rating reflects the overall satisfaction level of the audience with the movie.

# Project Aim & Scope:
After data exploration and necessary data cleaning, we will re-label a subset of this dataset, defining new categories that encapsulate more specific sentiments 
and themes found in movie reviews. Then we will use machine learning models to build the classifier and do text analysis. Due to the extensive size of the IMDB dataset, the process of relabeling requires significant manual oversight. This oversight includes understanding the context, identifying themes, and 
assigning accurate labels. Additionally, there's a subsequent task of data exploration, data cleaning, text analysis and performance analysis
