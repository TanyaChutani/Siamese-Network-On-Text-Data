# SiameseNetworkOnTextData
Siamese Network On Quora Question Pairs Similarity Data Keras 


## Dataset 
Quora Question Pair Similarity</br>
[Download Dataset](https://www.kaggle.com/c/quora-question-pairs)</br>

## Model
This is a natural language processing problem wherein we classify the question pairs as having similar intent or not.
- Developed a Siamese network, in this let the embeddings of two questions be passed through the same model. 
- check the distance measure using cosine similarity. 
- For embeddings, Word2Vec embeddings have been used.

## Result<br />

#### GRU Model Prediction<br />
![](https://github.com/TanyaChutani/Siamese-Network-On-Text-Data/blob/master/result/gru.PNG)<br />

#### Conv1D (CNN) Model Prediction<br />
![](https://github.com/TanyaChutani/Siamese-Network-On-Text-Data/blob/master/result/cnn.PNG)
