# SiameseNetworkOnTextData
Siamese Network On Quora Question Pairs Similarity Data Keras 


## Dataset 
Quora Question Pair Similarity</br>
[Dataset](https://www.kaggle.com/c/quora-question-pairs)</br>

## Model
This is a natural language processing problem wherein we classify the question pairs as having similar intent or not.
- Developed a Siamese network, in this let the embeddings of two questions be passed through the same model. 
- check the distance measure using cosine similarity and apply sigmoid at the end to get an output. 
- For embeddings, Word2Vec embeddings have been used.

