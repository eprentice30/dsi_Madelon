For this project we worked with the Madelon dataset. Madelon is an artificial dataset with many noisy features.
Our main goal was to significantly reduce the number of features while maintaining a high accuracy score. In
order to reduce non-contributing features, "leave one out regression" effectively identifies features within data
set with the most impact. By removing a single category and cross referencing the R-squared value, we are able
to identify the largest contributing features. We then removed more features based on high correlations. For
the UCI dataset, we were able to reduce down to 8 features with an accuracy score of 89.6%. For the instructors
dataset, we were able to reduce down to 11 features with an accuracy score of 85.63%. Ideally this method
would be eective on any data set composed of a large number of features of unknown importance, helping to
eliminate bias in feature reduction.

