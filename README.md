# Multiclass Text Classification for Identifying TV Show Characters

# Introduction

- The goal of this project is to investigate if NLP can be used to identify movie/TV show characters from any line they have said in the show. The popular TV show 'Friends' was used as the test case in this project, and dataset for modeling was created by web-scraping the transcripts for all the 9 seasons available online.
- The project is inspired from several threads/discussions on reddit/ quora when everyone was trying to predict the ending of  and the future of different characters in the  popular TV show 'Game of Thornes'. Being a part of the rare group of people who are yet to watch GoT, I chose 'Friends' for this NLP based capstone project. 
- To the best of my knowledge this is the first demonstration of using ML models for multiclass text classification using a movie\TV show transcripts. 
Therefore, efforts were mainly geared towards developing an understanding the challenges of ML modeling using these kind of datasets and have future directions for improvement.

# Key Development Goals

- Understand how exploratory data analysis can be utilized to have meaningful insights from the transcripts of a tv/movie show
- Identify the correct word embedding technqiues to use for this kind of dataset
- Evaluate the prediction capabilites of different linear classifiers while developing an understanding of the performance metric to use for this application
- Investigate how different resampling techniques can be utilized to address imbalance in the dataset
- Explore application of Deep Learning Models and provide directions for further development

# Link to Project Report
The project report [in this link]contains elaborate explanations of the steps followed and accomplishments from this project.


# Notebooks to Explore

- *Webscraping.ipynb* contains code to scrape data from the transcripts of Friends: https://fangj.github.io/friends/
- *Data Wrangling & Exploratory Data Analysis.ipynb* for Data Cleaning and Implementation of Interactive EDA 
- *Preliminary ML Modeling_Class_Specific_ROC_AUC.ipynb* for evaluation of ML modeling with different word embedding techniques and linear ML classifiers
- *Oversampling_vs_Undersampling.ipynb* for ML modeling with different sampling techniques 
- *Deep_Learning_with_Keras.ipynb* for implementing a deep learning model with Keras 
