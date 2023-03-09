# Heterogenous-Ensemble
I demonstrate the Heterogenous ensemble method using a health insurance data set in this repository. The various libraries used include pandas to read the file
and sklearn. The dataset is first loaded and checked for missing values. The dataset is preprocessed by encoding categorical values and removing unwanted columns,
in this case, ‘children’ and ‘region’ in the insurance dataset, because they play no significant role in the analysis of the data. Data is split into test and training
sets under the 0.3 test fraction. Then the various classifiers are created. In this case: DecisionTree classifier, LogisticRegression, and RandomForestClassifier.
These three are used to obtain 3 trained-based models which can be used to make individual predictions.

Feel free to star this repo, if you find it insightful and I am looking forward to your contribution.
