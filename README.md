## Fake Job Posting Detection Using Different Supervised Learning Models

### Project Overview
- This is a group project from *Analyzing Unstructured Data*, one of the courses I took at Rady School of Management, UC San Diego. 
- The main goal of the project was to build a classification model that identifies fraudulent job positings. 
- There were two things that were explored in the project:  
  * (1) different techniques of text representation (CountVectorizer, TF-IDF, and GloVe) 
  * (2) different classification algorithms (Logistic Regression, K-Nearest Neighbor, Random Forest, and Gradient Boosted Trees. 

### Dataset Used
- A real-world dataset that was published by the Employment Scam Aegean Dataset (EMSCAD) was used. 
- It contains 17880 job postings, 17014 of which are legitimate and 866 are fraudulent. 

### Methods
- Exploratory Data Analysis 
- Data Cleaning
- Text Processing
  * Tokenization using Python nltk package  
  * Stemming using PorterStemmer
- Text Representation
  * CountVectorizer
  * TF-IDF
- Classification Models 
  * Logistic Regression
  * KNN
  * Random Forest
  * Gradient Boosted Trees

### Conclusion 
- Among all combinations of text representation and machine learning algorithms, we discovered that CountVectorizer and Logistic Regression model was the best model for the dataset explored. 
- The result was different from what we initially expected, since we assumed that the combination of GloVe and Random Forest to give the best performance. This led us to a lesson that machine learning algorithms may not always be the most effective one. 
- However, to further improve our study, the models developed could be hypertuned with a more comprehensive set of hyperparameters, and additional datasets could be used to evaluate the performance of each model. 

Please refer to our [Report](https://github.com/haorzeng1997/NLP-Fake-Job-Posting-Detection/blob/main/report.pdf) and code files for more details. 

Author: Seyoung Ahn 
Project Completion Date: March 2021
