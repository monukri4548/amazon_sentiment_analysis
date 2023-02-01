# Amazon_sentiment_analysis

Sentiment Analysis on mobile phone reviews

Sentiment Analysis by Monu Kumari

# Overview

This repository contains code for sentiment analysis on a dataset of mobile reviews. The dataset is downloaded from Kaggle. The code is developed using Scikit learn. It uses following algorithms:

    Bag of Words
    Multinomial Naive Bayes
    Logistic Regression
    Support Vector Machine
    Decision Tree
    Random Forest

Also, it has visualisation of data and the knowledge obtained from it.
# Dependencies

    python2.7
    virtualenv
    jupyter notebook
    pandas
    numpy
    nltk
    matplotlib
    sklearn
    beautifulsoup4
    re
    future

# Data

Download the required data from this kaggle page.

# Installation

You may run this code in a virtual environment. I preferred to do so.
Assuming that you have installed pip and virtualenv,
Create a virtualenv and activate it. eg. let's call it senti
cd senti
git clone https://github.com/hiteshvaidya/sentiment_analysis.git
cd sentiment_analysis
pip -r install requirements.txt
In order to run jupyter notebook in a virtualenv, you need to create a new kernel. Follow this blog or this stackoverflow page to create one.

# Usage

 Open jupter notebook. Now go in settings and change kernel to the new kernel that you just created.
 Now run the code in jupyter notebook.

# Acknowledgement

Credits for part of this code to Hitesh Vaidya.


