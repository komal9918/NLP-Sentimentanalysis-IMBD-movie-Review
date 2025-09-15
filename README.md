# 🎬 Sentiment Analysis on IMDB Movie Reviews

This project focuses on **sentiment analysis** of IMDB movie reviews using **Deep Learning (LSTM)**.  
The model classifies reviews as **positive** or **negative**, providing insights into public opinion about movies.

---

## 📌 Project Overview
- **Dataset**: IMDB 50K Movie Reviews (sourced from Kaggle).  
- **Objective**: Build a predictive model that can classify the sentiment of a given movie review.  
- **Approach**:
  1. Data collection via Kaggle API.  
  2. Preprocessing reviews (tokenization, padding).  
  3. Building an **LSTM model** with Embedding layers.  
  4. Training & evaluation on test data.  
  5. Deploying a simple prediction function for new reviews.  

---

## 🛠️ Tech Stack
- **Programming Language**: Python  
- **Libraries**:  
  - Pandas, NumPy  
  - Scikit-learn  
  - TensorFlow / Keras  
  - Kaggle API  

---

## 📂 Project Workflow
1. **Data Collection**  
   - Download IMDB dataset from Kaggle.  
   - Unzip and load into a Pandas DataFrame.  

2. **Data Preprocessing**  
   - Tokenize and pad sequences (max length = 200).  
   - Encode labels (`positive` → 1, `negative` → 0).  

3. **Model Building**  
   - Embedding Layer (5000 words, vector size 128).  
   - LSTM Layer with dropout.  
   - Dense output layer with **sigmoid** activation.  

4. **Training**  
   - Loss: `binary_crossentropy`  
   - Optimizer: `adam`  
   - Metrics: `accuracy`  
   - Trained for 5 epochs with batch size = 64.  

5. **Evaluation**  
   - Achieved accuracy on test set.  
   - Tested with custom reviews for prediction.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/komal9918/NLP-Sentimentanalysis-IMBD-movie-Review/blob/main/sentiment_analysis_on_imdb_movie_reviewproject.py
