# Name-Entity_Recognition

## Data Source

[OntoNotes Dataset](https://catalog.ldc.upenn.edu/LDC2013T19). 

The version I dealt with in this task is downloaded from UBC Library and processed by my instructor (see Credits below).

## Description

In this task, I processed the data files into standard IOB (Inside-Outside-Beginning) tags and perform classifiction through:

-  Multinomial Naive Bayes Classifier
-  CRF model

to recognize named-entities spans and their categories (e.g. Location, Event, Organization).

This project is submitted to [Kaggle Competition](https://www.kaggle.com/c/ubc-mdscl-colx563-ner/overview)

## Results

Validation Set:

| Model | Macro f1-score | Micro f1-score | 
|-------|----------------|----------------|
| Naive Bayes | 0.3368 | 0.9259 |
| CRF | 0.7087 | 0.9690 |

Kaggle Competition:

| Public Score | Private Score |
|--------------|---------------|
| 0.97153 (5th) | 0.97030 (7th)|

## Credits

This task is designed and mentored by my isntructor [Julian Brooke](https://linguistics.ubc.ca/person/julian-brooke/) in my Advanced Semantics class in UBC.
