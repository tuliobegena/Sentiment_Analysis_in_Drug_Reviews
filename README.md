### Sentiment Analysis in Drug Reviews using Machine Learning and Deep Learning Techniques

A analysis to detect sentiment from drug reviews and compare the results obtained by using different algorithms.

![image](https://github.com/tuliobegena/Sentiment_Analysis_in_Drug_Reviews/blob/main/process_flow.jpg)

### Why we made this project ?

The goal was to provide valuable insights on user perceptions regarding medication outcomes.

### Final results

The full article is available at my medium page here: [Sentiment Analysis in Drug Reviews using Machine Learning and Deep Learning Techniques](https://medium.com/@tuliobegena/sentiment-analysis-in-drug-reviews-using-machine-learning-and-deep-learning-techniques-5b66d92247b0)


### How to use?

To start, you can run the main.py script from the command-line.
After a word in German and its translation appears, if you knew it, click the check button. If you did not knew, click the wrong button.
If you have checked a word, it will get removed from the pool of words to learn.
The reset button returns the known words to the initial pool of words to learn.


### Setup

This script was created using `python 3.10`.

The project depends on many libraries, install and load them at the beggining of code

`import pandas as pd # data preprocessing
import itertools # confusion matrix
import string
import numpy as np
import seaborn as sns
from sklearn.feature_extraction.text import CountVectorizer, TfidfVectorizer
from sklearn.model_selection import train_test_split
from sklearn.linear_model import PassiveAggressiveClassifier
from sklearn.naive_bayes import MultinomialNB
from sklearn import metrics
import matplotlib.pyplot as plt`



### Logs

V1.0
    Project created.


### Contributing

You are welcome to contribute sending feedbacks about the code. For that, reach me at [LinkedIn](https://www.linkedin.com/in/tuliobegena).

You are also welcome to contribute to the code via pull requests, of course.