# Eluvio_DS_Challenge
Analyze the data, find a pattern and predict sentiment/popularity

On a close look at the dataset, it seems to be title of posts from subreddit worldnews with upvote, downvote, username and time information. I plan to do the following things:
* Understand the data and find popular titles
* Find the popular titles based on sentiment
* Create word2vec embeddings and visualize the embeddings of most popular titles
* Predict the sentiment of a title based of sentiment values obtained using VADER
* Predict the popularity of a title based on up_vote information

# Contents:
1. Analyzing_Eluvio_data.ipynb: Python notebook that has all the work. Used kaggle as it has free GPU
2. Eluvio_DS_Challenge.csv: Dataset
3. embedding_word2vec.txt: word2vec embeddings of the tokenized title in the data
4. similar_words.png: t-SNE embeddings of similar words to popular topics
