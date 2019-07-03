# BBC_News_text_Analytics

# Introduction 
My goal is to learn basic concepts of Natural Language Processing and Data mining, the role that probability plays in language modelling. All code, images, and data for this project can be checked in Python notebook attached.

# Project Description
 This project involves five steps:
 1. Data Pre-Processing
 2. Language Modelling 
3. Classification 
4. Visualization 
5. Evaluation of Results 

# Data Pre-Processing 

# Downloading Data 
I use the open-source BBC Dataset. The dataset contains 2,225 articles from the BBC news. Each article is labelled with one of the following five classes: business, entertainment, politics, sport, and tech. I downloaded the dataset and wrote the script import-data. Python to output the data as a two-column data frame, with one row per article. The first column contained the document text, while the second column contained the class labels.
# Splitting into Training and Testing 
Next, I split the data frame into training and testing sets, randomly assigning 70% of the data to a “training” set and leaving the remaining 30% for “testing”. The purpose of this step is for classification. Classification models are fit to training data, which represents past observations, in order to predict the testing data, which would represent new observations. It is important to perform this step before creating a language model in order to avoid the mistake of training our model on data that is supposed to be unseen. Thus, I create two copies for each language model: one with 70% of the dataset, and another with only 30%.
