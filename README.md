# Income-Qualifications-Python-
Identify the level of income qualification needed for the families in Latin America using ML Algorithms.

Problem statement -- 
Many social programs have a hard time ensuring that the right people are given enough aid. It’s tricky when a program focuses on the poorest segment of the population. This segment of the population can’t provide the necessary income and expense records to prove that they qualify.

In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. With PMT, agencies use a model that considers a family’s observable household attributes like the material of their walls and ceiling or the assets found in their homes to
classify them and predict their level of need.

While this is an improvement, accuracy remains a problem as the region’s population grows and poverty declines.

The Inter-American Development Bank (IDB)believes that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.

## Tasks performed in the code :

Preprocessing the data
Identifying the output variable.
Understanding the type of data.
Checking if there are any biases in your dataset.
Checking whether all members of the house have the same poverty level.
Checking if there is a house without a family head.
Setting poverty level of the members and the head of the house within a family.
Counting how many null values are existing in columns.
Removing null value rows of the target variable.
Predicting the accuracy using random forest classifier.
Checking the accuracy using random forest with cross validation.
