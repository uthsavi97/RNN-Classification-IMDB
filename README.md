# Sentiment Analysis on IMDB Reviews using RNN

## Project Overview
This project focuses on building a deep learning model using a Recurrent Neural Network (RNN) to classify IMDB movie reviews as either positive or negative. The model is trained using word embeddings and deployed as a web application using Streamlit.

## Dataset
- **IMDB Reviews Dataset**
- The dataset contains 50,000 movie reviews labeled as either positive (1) or negative (0).
- Preprocessed using tokenization, padding, and word embeddings.

## Features & Workflow
1. **Data Preprocessing**
   - Tokenization and sequence padding.
   - Word embedding using Keras Embedding layer.
   
2. **Model Architecture**
   - Simple RNN with embedding layer.
   - Dense layers for binary classification.
   
3. **Training & Evaluation**
   - Model trained using binary cross-entropy loss.
   - Performance evaluated using accuracy and loss metrics.
   
4. **Deployment**
   - Built a Streamlit web app for user interaction.
   - User inputs a movie review, and the model predicts sentiment.
   
5. **Technologies Used**
   - Python, TensorFlow/Keras, NumPy, Pandas
   - Streamlit for web app deployment


