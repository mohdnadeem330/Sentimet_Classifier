# Sentimet_Classifier
Sentiment_Classifier based on Logistic_Regression
Sentiment Analysis with Logistic Regression

Overview

This is the code for this video on Youtube by Siraj Raval.

This repository contains a jupyter notebook and the necessary data to implement sentiment analysis of tweets using Logistic Regression. Please open the notebook for more information.

The dataset

The dataset was obtained from a Kaggle competition. The dataset is divided into a train and a test dataset. Each record contains the following fields:

Field name	Meaning
ItemID	id of twit
Sentiment	sentiment (1-positive, 0-negative)
SentimentText	text of the twit
Web app

You can go straight ahead and try out the algorithm with a small web app I have included in this repository, just run:

cd site
python app.py
Then open a browser in the default address (http://127.0.0.1:5000/) and play around:

web

Requirements

This notebook will run in Python >= 3.5. The following packages are required:

bokeh
flask
nltk
numpy
pandas
scikit-learn
Limitations

Because the training set contains only English twits, this classifier will only work with English twits.

Credits

Credits for this code go to siraj raval I merely made a wraper
© 2018 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
