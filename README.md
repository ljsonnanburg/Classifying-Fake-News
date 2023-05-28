Project classifying roughly ~45,000 news articles as "real" or "fake" based on pre-labeled training set, and extracting some other useful insights in the process.

Approach involved TF-IDF vectorization to abstract individual words into scores indicating how likely they were to appear with either label. 
Achieved >99% scores in all metrics with a random forest classifier. Results may not generalize well as the original method of collecting the training data is unexplained; it appears that whoever labeled the data based their labels solely on the news source.
