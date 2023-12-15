# Simple-text-based-sentiment-analysis
This is part of homework for CSCI 5527 Deep Learning

The requirement is 85% on test set

I follow the tutorial to bulid Bi-LSTM model: https://github.com/bentrevett/pytorch-sentiment-analysis

Dataset could be found here https://www.kaggle.com/datasets/kazanova/sentiment140

PS: Pre-processing is important. I tried a lot to improve the performance of model by changing it to bidirection, increasing layers, using pre-trained embeddings-Word2vec/GloVe but all fails.
Finally, I went back to do more data cleanning. As a result, I worked well. It achieved 85% accuracy on test set after only two epoch trainning.
