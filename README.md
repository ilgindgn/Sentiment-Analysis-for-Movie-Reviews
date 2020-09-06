# Sentiment-Analysis-for-Movie-Reviews

This project is designed to analyze the movie reviews and develop a classifier to determine whether a movie is good or bad. The used dataset includes a large number of movie reviews from the [Rotten Tomatoes](http://www.rottentomatoes.com) which is available in the file "reviews.csv". In addition, the file "movies.dat" contains metadata for ~65,000 different movies.

This project is composed of four main parts: 

* Exploratory Data Analysis (EDA) 
* Feature extraction using the [Bag-of-words](https://en.wikipedia.org/wiki/Bag-of-words_model) representation approach
* Predictive modeling using the Multinomial [Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier) (MNB) algorithm
* Model evaluation and error analysis

Overall observations:

* Since the Naive Bayes classifiers assume that every word affects the prediction independently of other words, it ignores the meaning of the phrases, i.e. combinations of words that might completely change the meaning of the individual words themselves, which is very common in English language. 

* In addition, the Bag-of-words approach ignores the order of the words in a sentence and performs poorly in dealing with the negated phrases. 

To get started, download the files "reviews.csv" and "movies.dat".
