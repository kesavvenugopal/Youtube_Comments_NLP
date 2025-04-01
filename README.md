# Sentiment Analysis using Deep Learning 📊💻

## Overview 🌟  
This project focuses on sentiment analysis using deep learning models like LSTM and GRU. The goal is to classify text into three sentiment categories using advanced preprocessing techniques and hyperparameter tuning.  

## Features 🔧  
- Data preprocessing (contractions expansion, stopword removal, lemmatization, regex filtrations)  
- Translation and language filtering 🌐  
- Tokenization and padding  
- Model architectures: LSTM & GRU  
- Hyperparameter tuning with Keras Tuner 🛠️  
- Model evaluation using accuracy and classification reports 📈  

## Dataset 📚  
The dataset consists of Youtube comments  data labeled with three sentiment classes. Non-English comments were translated.  

## Model Architectures 🧠  
1. **LSTM Model**  
   - Embedding layer  
   - LSTM units  
   - Dropout and Dense layers  

2. **GRU Model**  
   - Embedding layer  
   - GRU units (single and stacked)  
   - Dropout, Dense, and Batch Normalization  

## Hyperparameter Tuning 🔍  
Keras Tuner was used to optimize key parameters like embedding size, number of units, dropout rate, and learning rate. The best models were selected based on validation accuracy.  

## Results 🏆  
The best model achieved an accuracy of **~70%**, highlighting challenges with dataset quality and class imbalance. Despite extensive tuning, improvements were limited, emphasizing the importance of high-quality data.  

## Conclusion 🎯  
This project demonstrates the power and limitations of deep learning in sentiment analysis. While tuning improved performance, dataset quality remains a crucial factor in achieving better results.  
