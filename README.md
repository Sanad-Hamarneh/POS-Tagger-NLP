# 📝 NLP POS Tagging with Deep Learning  

This project focuses on **Natural Language Processing (NLP)** for **Part-of-Speech (POS) tagging** using **Deep Learning** techniques. The goal is to process textual data, tokenize it, and train models to accurately predict POS tags.  

## 📌 Project Overview  
- Develop an **automated POS tagger** using **LSTM, GRU, and Attention mechanisms**.  
- Use **word embeddings** and sequence models to understand linguistic structure.  
- Train, validate, and test the model on **processed text data**.  

## 🛠️ Techniques Used  

### 🔹 Data Preprocessing  
- Loaded and processed **Parquet files** with Pandas.  
- Applied **tokenization and padding** for uniform sequence input.  
- Added **start and end tags** to sentences for better learning.  

### 🔹 Deep Learning Model  
- **LSTM & GRU**: Captures **contextual dependencies** in sequences.  
- **Bidirectional LSTM**: Enhances understanding of both **past and future words**.  
- **Attention Mechanism**: Focuses on **important words** in a sequence.  
- **Embedding Layer**: Converts words into dense vector representations.  

### 🔹 Model Training & Validation  
- Split dataset into **training, validation, and test sets**.  
- Used **cross-entropy loss** and **accuracy metrics** for evaluation.  

## ⚠️ Issues in Testing  
- **Small Dataset**: Limited training data reduced **generalization ability**.  
- **Limited Vocabulary**: Some **unseen words** in the test set affected performance.  
- **Data Sparsity**: Few examples per **POS tag**, leading to **biased learning**.  
