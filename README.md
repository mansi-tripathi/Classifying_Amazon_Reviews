The project involved classifying Amazon reviews using a Naive Bayes Classifier

The comments were obtained by scraping the data from Amazon website using Beautiful Soup package and Selenium web driver.

# Naive_Bayes_Classifier
The steps involved in classification of the comments are as follows:
1. Data pre-processing: I cleaned the data and removed any stopwords, emojis and special characters that do not add meaning to the classifications. I further lemmatized the data.

2. 80-20 split: I used the 80-20 split technique to divide the datanto train and test (80/20). 

3. NBC Model: I built an NBC model and to then evaluate the result.

4. Checking accuracy and quality of predictions: I used the confusion matrix and cross vaidation to check the accuracy and quality of the data. We also using SMOTE or Synthetic Minority Oversampling Technique to increase the accuracy of the data. We can further improve the accuracy by adding customized stopwords for removal or hyperparameter tuning.
