# Movie-review-classification
A classification of Rotten Tomatoes movie reviews found on Kaggle, compiled by Bo Pang and Lillian Lee in 2005.
While found on Kaggle, the Rotten Tomatoes movie review dataset is a corpus of movie reviews used for sentiment analysis that was originally collected by Bo Pang and Lillian Lee in 2005. The data consists of comments left by Rotten Tomatoes users that have been broken down as follows: each comment (phrase) gets assigned a SentenceId number and is then parsed word by word, receiving a different PhraseId with each parsing. The initial phrase is the most complete one and is therefore used in our analysis. The training dataset also contains a sentiment rating indicating the strength and polarity of each phrase. Those ratings are as follows:

0 - negative
1 - somewhat negative 
2 - neutral
3 - somewhat positive
4 - positive

Goals:

The purpose of this project is to accurately classify movie reviews based on the sentiment ratings for each review. Achieving this goal requires building multiple classification algorithms, applying those to text processed in a variety of ways, and comparing the results to find the best algorithm and preprocessing technique. The outcome results from this analysis will include the best document grouping, the best featureset, and the best model type to accurately classify the movie reviews.

To achieve these goals, the movie review corpus went through three primary steps:
1.	Text Processing
2.	Feature Engineering
3.	Experiments
