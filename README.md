# Naive Bayes Assignment

Part 1: Exploratory Naive Bayes
In this section, you will build a Naïve Bayes classifier on the convention speeches, using the words of the speech text to predict the party (either Republican or Democratic). Your starting notebook walks you through the steps of fitting and using a Naïve Bayes model from the NLTK package. This repo includes some code that would help you limit the number of words you consider in your model, which might improve run-time. We have asked you to fill in some observations from the fitted model.

Part 2: Classifying Tweets
We have a pretty gigantic database of tweets (and other data) from everyone running for congress in 2018. As an exercise, we'll try to use this convention model to classify those tweets.

The notebook walks you through the steps in broad terms:

Pull data from the congressional DB.
Clean, tokenize, and build your feature dictionary for a tweet.
Use the classifier from Part 1 to estimate the party of the tweeter.
Compare this estimate to their actual party.
