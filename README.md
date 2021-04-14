# Sentiment-Analysis-On-Restaurant-Customers
The business problem here which we are trying to solve is to find out about the sentiments of the customers who visit a restaurant.

Data Understanding:
After importing the dataset for training, I removed all the unnecessary columns which were not important for applying sentiment analysis. 
Hence, the id column was removed.Then in review column all the special characters were removed. So in the end we had characters ranging from A-Z 
in both cases.Then all the “stop words” were removed. These are words which are like ‘the’ & ’a’ which do not add meaning to our analysis.Then came 
the next step of stemming and lemmatization. All the words were converted to its original form. Like ‘eating’ and ‘eaten’ would convert into ‘eat’.
The we added TF/ID vectorizer which transforms text into a meaningful representation of numbers which is used to fit machine algorithm for prediction. 


Then we divided the data into test and train data. Since both sets were given separately, I kept the test size, which was separated from training data,
very low (i.e 0.000001). After this applied these machine learning models:
Naive bayes
SVM
Random Forest
Decision tree 
Gradient boost
Logistic regression
