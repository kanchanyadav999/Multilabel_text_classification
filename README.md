# Multilabel_text_classification
# Title: Multilabel text classification
#### Problem statement:
##### To Develop a multi-label text classification model that accurately predicts the probabilities of a given text belonging to multiple predefined classes. The task involves working with a dataset containing features extracted from text n-grams, including 145 features of numerical, boolean, and categorical types.
#### Features
##### For a given nGram several features have been extracted (145). These features have been saved in the train.csvand test.csv. They have parsing, spatial, content and relative information.
1) Content: The cryptographic hash of the raw text.
2) Parsing: nGram is a number, text, alphanumeric, etc.
3) Spatial: Position and size of the nGram
4) Relational: details of text nearby the nGram
The feature values can be:

1) Numbers. Continuous/discrete numerical values.
2) Boolean. The values include YES (true) or NO (false).
3) Categorical. Values within a finite set of possible values.

#### Labels
##### This are the labels corresponding to the probability that the current sample belongs to the given class. This is multilabel problem and hence a given sample can belong to more than one class.
#### File description
1) train.csv: This file contains the feature for training set
2) trainlabels.csv: This file contains the label for training set
3) test.csv: This file contains testing data
4) sampleSubmissions.csv: This file contains sample submission format
