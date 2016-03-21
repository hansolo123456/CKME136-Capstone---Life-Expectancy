# CKME136-Capstone---Twitter-Gender-Classifier
Using Machine Learning to Classify tweets into one of 3 genders (male, female, brand) based on the text of the tweet.

This Repository is part of my Capstone Project for the Big Data and Predictive Analytics certificate program at Ryerson Unviersity.

General Description:
Twitter is ubiquitous.  It is everywhere.  Millions of people use it to express themselves, comment on happenings in their personal lives, their public life, international issues, etc.  But often people hide behind their User ID.  Is it possible to use Machine Learning to “train” an Artificial Intelligence to predict if the user is male or female, simply by looking exclusively at the text of thier tweet?

The application could be limitless for Marketers looking to identify comments from thier target audience.  For my training source, I am using curated data in which the gender field (identifed as 3 general categories - male, female and brand)  The same process however, could be used for any field to compare against text, as long as the training data is curated and verified.

This is essentially a Supervised Classification problem for Machine Learning

The training process invovles breaking the data into into a training and testing group, cleaning the data, removing stopwords, tokenizing, training the model (Regression? Naive Bays? TBC), then testing the model against the test ata created earlier.

