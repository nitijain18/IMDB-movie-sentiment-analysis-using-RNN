# IMDb Movie Sentiment Analysis using Bidirectional LSTM

## Overview
This project implements a Deep Learning-based Sentiment Analysis model using a Bidirectional LSTM network to classify IMDb movie reviews as positive or negative. The model processes textual review data, learns contextual patterns from sequences of words, and predicts the sentiment of unseen reviews.

## Dataset
The project uses the IMDb Movie Review Dataset available through TensorFlow/Keras.

- Total Reviews: 50,000
- Training Samples: 25,000
- Testing Samples: 25,000
- Classes:
  - Positive (1)
  - Negative (0)

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Model Architecture
1. Embedding Layer
2. Bidirectional LSTM Layer
3. Dense Layer (ReLU)
4. Dropout Layer
5. Output Layer (Sigmoid)

## Workflow
- Load IMDb dataset
- Preprocess text data
- Pad review sequences to fixed length
- Train Bidirectional LSTM model
- Evaluate performance on test data
- Visualize training and validation metrics

## Results
- Test Accuracy: **83%**
- Binary Sentiment Classification
- Successfully captures contextual information from movie reviews using Bidirectional LSTM

## Features
- Text preprocessing and sequence padding
- Word embeddings for text representation
- Bidirectional sequence learning
- Sentiment prediction
- Model evaluation and performance visualization

## Future Improvements
- Hyperparameter tuning
- GRU-based architecture
- Attention mechanisms
- Transformer-based models (BERT)
- Web application deployment

## Conclusion
This project demonstrates the application of Recurrent Neural Networks for Natural Language Processing tasks. The Bidirectional LSTM model achieved **83% accuracy** on the IMDb dataset and effectively classified movie reviews into positive and negative sentiments.
