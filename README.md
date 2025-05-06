# tweet-analysis

The code reads in a CSV file containing reviews and their corresponding feedback ratings, cleans and preprocesses the data by removing punctuation and stop words, and converts text into numerical vectors using CountVectorizer. It then trains a Multinomial Naive Bayes classifier on these vectors to predict the rating of new reviews based on their content, and evaluates its performance using classification metrics. Finally, it saves the trained classifier model as a pickle file for future use in making predictions.
