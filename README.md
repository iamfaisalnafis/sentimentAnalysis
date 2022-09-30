# Sentiment Analysis of Tweets from the Sentiment140 Dataset containing approximately 1,600,000 tweets from different users. 
Sentiment Analysis for the Twitter tweet Dataset [Sentiment140]

## Content
It contains the following 6 fields:

* target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)

* ids: The id of the tweet ( 2087)

* date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)

* flag: The query (lyx). If there is no query, then this value is NO_QUERY.

* user: the user that tweeted (robotickilldozr)

* text: the text of the tweet (Lyx is cool)

## Acknowledgements
The official link regarding the dataset with resources about how it was generated is here
The official paper detailing the approach is here

## Citation: Go, A., Bhayani, R. and Huang, L., 2009. Twitter sentiment classification using distant supervision. CS224N Project Report, Stanford, 1(2009), p.12.

The project was initiated as a beginner project in the field of Machine Learning. Incase you're interested in replicating the project you can download the botebook and run it on your local machine.
The code has been commented to a certain degree and some modifications were made that do not reflect in the original work. 

The Datset was evaluated using 3 Different Models and the results are available in PNG format in form if images. Bernoulli Naive Bayes, Support Vector Classifier & Logistic regression were used to predict the outcomes. Confusion Matrix was used to evaluate all the three models along with ROC-Curve.

The code here will be updated to easily integrate Google Collab and launch the project on Google Servers. 

In the end Logistic Regression proved to be the most accurate for this dataset in particular. 
