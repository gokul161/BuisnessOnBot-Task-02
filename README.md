# BuisnessOnBot-Task-02
Sentiment analysis on tweets data.
1)Imported libraries such as pandas to deal with data frames/datasets, re for regular expression, nltk is a natural language tool kit and from that, we have imported module – stopwords which are nothing but ‘dictionary’.
2)And have checked for the top 5 values in the dataset using head()
3)Further, I have performed some data visualizations using matplotlib and seaborn libraries which are really the best visualization libraries in Python. I have plotted only one graph, you can plot more graphs to see how your data is!
4)Performed a regular expression function to remove any symbols and special characters, etc to get pure data.
5)Converted text into the matrix of tokens, we have to import the following library and perform code
6)LabelEncoder is used here for transforming categorical values into numerical values.
7)By using vectorization, we have performed normalization of test data and stored it into x_test & y_test. We have also predicted actual and predicted values.
8)Performed the accuracy of our model in the form of an AUC curve plotted using the matplotlib library.
9)Got a score of AUC – 0.64 for the classifier (Naive Byes).

