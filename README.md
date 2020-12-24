# Titanic Machine Learning from Disaster

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

The notebook `Titanic.ipynb` build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

## Data

The data we're using is from Kaggle : https://www.kaggle.com/c/titanic/data

The data has been split into two groups:

* training set (`train.csv`)
* test set (`test.csv`)

## Content

This file contains in detail the visualization aspect of the data analysis and building a machine learning project.

Before modeling, we'll parse all input data.

We're using to models for describing classification problem:

1. LogisticRegression
2. KNeighborsClassifier
3. RandomForestClassifier

