# Multiclass Text Classification for Identifying TV Show Characters

# Link to Project Report/Notebooks
- [The project report in this link ](https://github.com/shamafarabi/NLP-Predict-Cast-Member-of-the-TV-Show-Friends/blob/master/Project%20Report.ipynb)contains elaborate explanations of the steps followed and accomplishments from this project.
- [The notebook in this link ](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP/blob/master/1_Webscraping.ipynb)contains contains code to scrape data from transcripts available online
- [The notebook in this link ](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP/blob/master/2_Data%20Wrangling%20%26%20Exploratory%20Data%20Analysis.ipynb)contains data preprocessing and exploratory data analysis
- [This notebook ](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP/blob/master/3_Preliminary%20ML%20Modeling_Class_Specific_ROC_AUC.ipynb)incorporated NLP to process the dialogues into features and utilized ML modeling with Naive Bayes, Logistic Regression and Support Vector Machine to predict the cast member
- [This notebook ](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP/blob/master/4_Oversampling_vs_Undersampling.ipynb) utilized oversampling and undersampling techniques to address imbalance in the dataset
- [This notebook ](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP/blob/master/5_Deep_Learning_with_Keras.ipynb) implemented deep learning ML model with Keras

# Introduction

- The goal of this project is to investigate if NLP can be used to predict movie/TV show characters from any line they have said in the show. The popular TV show 'Friends' was used as the test case in this project, and dataset for modeling was created by web-scraping the transcripts for all the 9 seasons available online.
- The project is inspired from several threads/discussions on reddit/ quora when everyone was trying to predict the ending of  and the future of different characters in the  popular TV show 'Game of Thornes'. Being a part of the rare group of people who are yet to watch GoT, I chose 'Friends' for this NLP based capstone project. 
- To the best of my knowledge this is the first demonstration of using ML models for multiclass text classification using a movie\TV show transcripts. 
Therefore, efforts were mainly geared towards developing an understanding the challenges of ML modeling using these kind of datasets and have future directions for improvement.

# Key Development Goals

- Understand how exploratory data analysis can be utilized to have meaningful insights from the transcripts of a tv/movie show
- Identify the correct word embedding technqiues to use for this kind of dataset
- Evaluate the prediction capabilites of different linear classifiers while developing an understanding of the performance metric to use for this application
- Investigate how different resampling techniques can be utilized to address imbalance in the dataset
- Explore application of Deep Learning Models and provide directions for further development

# Notebooks to Explore

- *Webscraping.ipynb* contains code to scrape data from the transcripts of Friends: https://fangj.github.io/friends/
- *Data Wrangling & Exploratory Data Analysis.ipynb* for Data Cleaning and Implementation of Interactive EDA 
- *Preliminary ML Modeling_Class_Specific_ROC_AUC.ipynb* for evaluation of ML modeling with different word embedding techniques and linear ML classifiers
- *Oversampling_vs_Undersampling.ipynb* for ML modeling with different sampling techniques 
- *Deep_Learning_with_Keras.ipynb* for implementing a deep learning model with Keras 

# Extension of the Project (in progress)
- Feature Engineering to Improve Modeling Accuracy ([notebook](https://github.com/shamafarabi/NLP-Predict-Cast-Member-of-the-TV-Show-Friends/blob/master/Extension%20of%20the%20project/Extension%20_Feature_Engineering_Resampling.ipynb))
- Transfer Learning with Fastai ([notebook](https://github.com/shamafarabi/NLP-Predict-Cast-Member-of-the-TV-Show-Friends/blob/master/Extension%20of%20the%20project/Friends_Fastai.ipynb))

# ML Modeling Snapshot:
<img src="Figures/Modeling Summary.png">
