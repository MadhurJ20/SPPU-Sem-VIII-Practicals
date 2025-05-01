# Deep Learning Laboratory

## List of Programs

### 1. Boston Housing Price Prediction using Deep Neural Network

Implementation of Linear Regression using Deep Neural Network for predicting house prices using the Boston Housing dataset.

- Dataset: Boston House Price Dataset
  - Download: Built into tensorflow.keras.datasets
  - [Dataset Description](https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html)
- Model: Deep Neural Network
- Type: Regression Problem

[View Implementation](boston_housing_dnn.py)

### 2. IMDB Movie Review Sentiment Classification

Implementation of Binary Classification using Deep Neural Networks to classify movie reviews as positive or negative based on text content.

- Dataset: IMDB Movie Reviews Dataset (50,000 reviews)
  - Download: Built into tensorflow.keras.datasets
  - [Dataset Description](https://ai.stanford.edu/~amaas/data/sentiment/)
- Model: Deep Neural Network with Embedding, Conv1D, and LSTM layers
- Type: Binary Classification Problem

[View Implementation](imdb_sentiment_classification.py)

### 3. Fashion MNIST Classification using CNN

Implementation of a Convolutional Neural Network to classify fashion items into 10 categories.

- Dataset: Fashion MNIST Dataset
  - Download: Built into tensorflow.keras.datasets
  - [Dataset Description](https://github.com/zalandoresearch/fashion-mnist)
- Model: Convolutional Neural Network
- Type: Multi-class Classification Problem

[View Implementation](fashion_mnist_cnn.py)

## Dataset Information

All datasets used in these implementations are conveniently available through TensorFlow's built-in datasets module (`tensorflow.keras.datasets`). They will be automatically downloaded when running the respective scripts for the first time. No manual download is required.

To manually download and explore these datasets:
```python
# Boston Housing Dataset
from tensorflow.keras.datasets import boston_housing
(X_train, y_train), (X_test, y_test) = boston_housing.load_data()

# IMDB Reviews Dataset
from tensorflow.keras.datasets import imdb
(X_train, y_train), (X_test, y_test) = imdb.load_data()

# Fashion MNIST Dataset
from tensorflow.keras.datasets import fashion_mnist
(X_train, y_train), (X_test, y_test) = fashion_mnist.load_data()
```
