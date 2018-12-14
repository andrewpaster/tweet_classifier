# tweet_classifier

Project is in progress as of December 14th, 2018. Currently contains a notebook that vectorizes text data for a machine learning model (Spacy and Gensim libraries) and then trains the model to predict whether or not tweets are related to disaster relief messages or not. 

TODOs:
* oversample the 'relevant' class to see if this improves relevant class recall
* study in more depth the biases of the dataset and people who originally tagged the tweet data via figure8's platform
* deploy the app using either Flask/Amazon Lambda, or Amazon SageMaker (or both)
* use Amazon S3 event notifications to automatically retrain the model when uploading new data to an S3 bucket
* create a front-end for the results
