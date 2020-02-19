# NLP_Writing_Style
This project is to train a model that, given a sentence, predicts the correct author of the sentence (either Austen or Bronte). A NLP-based classifier can be trained to distinguish the two classes.

## Data preprocessing
This procedure includes tokenization, lowercase converting, removing stopping words, and verb lemmatization.

## Data exploration
There are two authors in the provided dataset: Austen with 16k sentences in 3 documents and Bronte with 13K sentences in 2 documents.

## Evaluation metrics
The evaluation methods include accuracy, AUC and F1 score.

## Encoding methods
Three embedding methods including label encoder, Bag of Word and TF-IDF are deployed.

## Methodologies

(1) Naive Bayes: a traditional machine learning classifier.

(2) Bidirectional LSTM: This neural network model is able to almost seamlessly model problems with multiple input variables and provides benefits in sequence data classification comparing to classical Naive Bayes model which can be difficult to include the sequential feature of the input sentence.

(3) Convolution Bi-LSTM: CNNs excel at learning the spatial structure of the input data. The learned spatial features may then be learned as sequences by the LSTM layers. A convoluation layer and a pooling layer are added between the embedding and LSTM layers.

## Reference

Ding et al. (2019) "Learning Stylometric Representations for Authorship Analysis", IEEE Transactions on Cybernetics, 49(1), 107-121.

Kim et al. (2011) "Literary Style Classification with Deep Linguistic Analysis Features", https://pdfs.semanticscholar.org/19f2/63c908b6b087c9ae30241de7a3209fabe649.pdf.

Brownlee. (2016) "Sequence Classification with LSTM Recurrent Neural Networks in Python with Keras", https://machinelearningmastery.com/sequence-classification-lstm-recurrent-neural-networks-python-keras/
