# Naive Bayes

## Definition

Naive Bayes is a set of <strong>Supervised Learning</strong> algorithms based on Bayes’ theorem that derives the probability of the given feature being associated with a label. NB is used as a <strong>classification</strong> method. 

## What's Naive about Naive Bayes?

Naive Bayes is 'naive' because it makes the assumption that features of a measurement are independent of each other.


## Types of Naive Bayes Classifier

* Gaussian NB – use when you have continuous feature values.  This classifier assumes each class is normally distributed.
* MultiNomial NB – good for text classification.  This classifier treats each occurrence of a word as an event.
* Bernoulli NB – use when you have multiple features that are assumed to be binary.  This classifier can be used for text classification but the features must be binary.  For text classification, the features can be set as a word is in the document or not in the document.

## Advantages

* Can successfully train on small data set
* Good for text classification, good for multiclass classification
* Quick and simple calculation since it is naive

## Disadvantages

* Can’t learn the relationship among the features because assumes feature independence
* Continous feature data is assumed to be normally distributed

## Reference

https://machinelearningspecialist.com/machine-learning-interview-questions-q7-why-is-naive-bayes-naive/



