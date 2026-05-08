# 📰 Real-Time News Classification & Summarization

## Overview
This repository contains the research work and implementation for **Real-Time News Classification and Summarization Using Machine Learning, Deep Learning, and Large Language Models (LLMs)**.  
The project addresses the challenge of organizing and consuming massive streams of online news by building an **end-to-end intelligent system** that classifies articles into categories and generates concise summaries in real time.

---

## ✨ Key Contributions
- **Integrated Pipeline**: Unified framework for news classification and summarization.  
- **Model Comparison**: Evaluation of classical ML models (Logistic Regression, Naïve Bayes, SVM, Random Forest) vs. Deep Learning models (LSTM, GRU, Bi-LSTM with Attention).  
- **Real-Time News Fetching**: Automated ingestion of live articles via external APIs.  
- **LLM Summarization**: Transformer-based models (GPT, LLaMA, Gemini) for abstractive summarization of lengthy articles.  
- **Deployment-Oriented Design**: Bridging theoretical research with practical real-world applications.

---

## 📊 Dataset
- **Source**: BBC News Dataset (BBC Website, Kaggle)  
- **Samples**: ~2,225 labeled articles  
- **Classes**: Business, Sports, Technology, Entertainment, Politics  
- **Type**: Text (Categorical labels)

---

## 🛠 Methodology
1. **Data Preprocessing**  
   - Lowercasing, stop-word removal, lemmatization, tokenization  
   - Feature extraction using **Bag of Words (BoW)** and **TF-IDF**

2. **Model Development**  
   - Classical ML: Logistic Regression, Naïve Bayes, SVM, Random Forest  
   - Deep Learning: LSTM, GRU, Bi-LSTM, Attention-based models  
   - LLMs: GPT, LLaMA for abstractive summarization

3. **Real-Time Pipeline**  
   - Fetching articles via APIs  
   - Preprocessing and classification into categories  
   - Summarization using transformer-based LLMs

---

## 📈 Results & Insights
- Classical ML models (especially **SVM**) achieved strong accuracy on structured datasets.  
- Deep Learning models captured contextual nuances but required more computational resources.  
- LLMs significantly improved **readability and accessibility** by generating human-like summaries.  
- The unified system demonstrates how ML, DL, and LLMs can complement each other in solving real-world NLP challenges.

---

## 🖼 System Architecture
Below is the **IntelliNews Processing Framework** flowchart that illustrates the complete pipeline from training to real-time deployment:

![IntelliNews Processing Framework](AouXSGMnRJv7RUsPMSx9X.jpeg)

---

## 📚 Research Paper
The full research paper is included in this repository:  
**`Research_Paper_RealTime_News_Classification.docx`**

---

## 🚀 Future Work
- Explore advanced transformer architectures (e.g., BERT, RoBERTa) for classification.  
- Optimize real-time performance for large-scale deployment.  
- Extend categories and datasets beyond BBC News for broader applicability.  

---

## 👨‍💻 Authors
- Sarthak Sharma (SCSET, Bennett University)  
- Aditya Bhadauria (SCSET, Bennett University)  
- Aryan Pandey (SCSET, Bennett University)  
- Mentor: Dr. Purushottam (SCSET, Bennett University)

---

## 📌 Keywords
**News Classification**, **Text Summarization**, **Machine Learning**, **Deep Learning**, **Natural Language Processing (NLP)**, **LSTM Networks**, **Transformer Models**, **Large Language Models (LLMs)**
