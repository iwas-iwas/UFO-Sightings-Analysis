# View Project: 

https://nbviewer.jupyter.org/github/iwasscience/UFO-Sightings-Analysis/blob/master/UFO-Project.ipynb

# UFO Sightings Project

![ufo](Data/ufo_pic.jpg)

## Tools: 

pandas, numpy, scikit-learn (logistic regression, k-neighbors-classifier, multinomial naive bayes), tfidf-vectorizer

### Introduction

In most UFO sightings, what people believe are UFOs are actually just common objects like planes and clouds, or celestial events like meteors and planets that seem unusually bright.

Some cases remain unidentified even after they’ve been investigated, but scientists believe many of these to also be sightings of more common objects that people simply didn’t recognize.

Many reported UFO sightings actually turn out to be something as simple as a balloon.

### Motivation

Predicting the type (e.g. circle, triangle, oval) and the country of a UFO sighting.

### Structure

**Exploratory data analysis & data preprocessing**

  - Exploring basic data statistics (e.g. df.head/info/describe, variance, distribution plots)
  - Feature Engineering (e.g. handling time data, missing values)
  - Tfidf-Vectorizing ufo-sighting descriptions 
  
**Classifying the country of a UFO sighting**
- Comparing KNeighborsClassifier & LogisticRegression

**Classifying the type of a UFO sighting**

- fitting tfidf-vectors to multinomial naive bayes

**Conclusion**

The score to predict the country of the sighting (us or not us) is pretty good on both KNN and Logistic Regression!

Sadly, the model performance in predicting the type of the UFO-Sighting is really bad. Further investigating the text or finding other features that are useful in predicting the type would be the next step.
