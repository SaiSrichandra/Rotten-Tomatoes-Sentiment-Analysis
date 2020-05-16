This is a project which identifies the sentiment of the movie reviews i.e. classifies reviews into 0 to 4 ratings (i.e. Negative to Positive).

0 - negative
1 - somewhat negative
2 - neutral
3 - somewhat positive
4 - positive

Requirements :
 1) Python 3 with following packages :
    1) Numpy
    2) Pandas
    3) Regex
    4) Scikit-learn

Format : .ipynb (Jupiter Notebook)

The files train.tsv and test.tsv contain Rotten Tomatoes movie reviews classified into train and test data taken from Kaggle

This model uses sklearn's Logistic Regression model to learn about the data.
The data is first preprocessed using Count Vectorizer from sklearn and a custom created Regex Tokenizer

This project also compares the accuracy of different solvers in the sklearn Logistic Regression model