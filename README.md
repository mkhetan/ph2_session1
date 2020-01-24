# Sentiment Prediction Using GloVe
 Sentiment Prediction from Movie Reviews Using Glove Word Embeddings.

* [GloVe - Global Vector for Word Representation | Word Embeddings](<https://nlp.stanford.edu/projects/glove/>)

* Dataset : [Raw Imdb Reviews can be downloaded from here.](http://mng.bz/0tIo)
* Results :
  * Pretrained Embedding
    * Script: [SentimentUsingGlove.ipynb](./SentimentUsingGlove.ipynb)
    * Training Samples: 8000
    * Validation Accuracy: 67.49%
    * Test Data Accuracy: 67%

Notes / Observations:
max words kept : 10,000
Used 300 dimensions file from Globe Embedding database
The max text length was kept to 100.
When model.layers[0].trainable set to True, validation and test accuracies were slightly better (~ 76%)

