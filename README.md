# Fake-news
Fake news detection using ML
1)The first step includes importing the train file.
2)Removing null values from all the columns in the dataset.
3)Creating a new column named content which contains the concatenation of author and title.
4)Assigning the independent variable X with the table exlcuding the label column.
5)Assigning the dependent varibale Y with the label column.
6)Stemmimg- which means bringing down the words to its root word and also removing stop words.
7)Trimming X to only 'content' column.
8)Converting textual data to numercial data using TF-IDF vectorizer.
9)Split the train set into train and test set.
10)Trained the train set using logistic classification model.
11)Checking accuracy of the test set.
12)Finding the confusion matrix of the predicted test label with the original test set.
DATASET-https://www.kaggle.com/c/fake-news/data?select=train.csv
LOGISTIC REGRESSION-https://medium.com/swlh/the-math-behind-logistic-regression-1f6eef7ea940
How to execute the code- a)Download jupyter notebook b)download ipynb file c)In jupyter notebook add the downloaded ipynb file as a folder and run the code
