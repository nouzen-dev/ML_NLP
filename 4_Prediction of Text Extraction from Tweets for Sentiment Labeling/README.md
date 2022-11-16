# About this project:

This project is my 1st try on transformer. It examined a Kaggle competition tweet datasets. Tweets are commonly used for sentiment analysis, but the goal of this competition was to predict words/ phrases that
actually led to the sentiment labeling (positive, negative, or neutral):
- My motivation was the application of transformer, which is used primarily in the fields of natural language processing (NLP). 
- For prediction of the words/ phrases, I framed the task as a question-answering task. The output was a set of 3 predictions for each tweet, and ultimately the 
submission file with the best prediction extracted. 
- I got to apply tokenization, lemmatization, bag-of-words, etc., followed by the training & prediction using a Hugging Face model based on BERT architecture. 
- A challenge I faced was the extent of data cleaning required & the determination of useful arguments for training of the transformer model, which is 
computationally expensive. 

A future improvement is to devise more specific regular expressions for different use cases in data cleaning for performance improvement & efficiency.

## Visualizations:


