# Transformer-Based Bangla Sentiment Analysis

## 📌 Overview

This project presents a comprehensive sentiment analysis system for Bangla text using machine learning, deep learning, and transformer-based Natural Language Processing (NLP) models. The study focuses on analyzing Bangla and Romanized Bangla text collected from social media, e-learning platforms, and e-commerce sources.

The system integrates traditional models, deep learning architectures, and state-of-the-art transformer models to compare performance and improve sentiment classification accuracy.

---

## 🎯 Objectives

* Perform sentiment analysis on Bangla text data
* Compare traditional ML, deep learning, and transformer-based models
* Handle noisy, code-mixed, and real-world Bangla text
* Improve interpretability using Explainable AI (XAI) techniques

---

## 🧠 Models Used

* Support Vector Machine (SVM)
* Bidirectional LSTM (BiLSTM)
* BanglaBERT (Transformer)
* XLM-RoBERTa (Transformer)

---

## 📊 Dataset

* Collected from:

  * Social Media
  * E-learning Platforms
  * E-commerce Reviews

* Data Types:

  * Bangla text
  * Romanized Bangla text

* Sentiment Classes:

  * Funny (0)
  * Toxic (1)
  * Sad (2) 

---

## ⚙️ Methodology

### 🔹 Data Preprocessing

* Data Cleaning (remove noise, duplicates)
* Normalization (lowercase, punctuation removal)
* Tokenization
* TF-IDF Feature Extraction (for ML models)
* Train/Validation/Test split

### 🔹 Model Training

* SVM trained on TF-IDF features
* BiLSTM for sequence learning
* Transformer models fine-tuned using pretrained weights
* K-Fold Cross Validation (K=5) for robust evaluation 

---

## 📈 Results

| Model       | Accuracy |   |
| ----------- | -------- | - |
| SVM         | 62%      |   |
| BiLSTM      | 63%      |   |
| BanglaBERT  | **75%**  |   |
| XLM-RoBERTa | 65%      |   |

👉 Transformer-based models outperform traditional approaches significantly.

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix 

---

## 🔍 Explainable AI (XAI)

To improve model interpretability:

* LIME (Local explanations)
* SHAP (Feature contribution analysis)

These methods provide word-level explanations for model predictions, increasing transparency and trust. 

---

## 🖼️ Figures

Figures included in this project:

* Dataset distribution graphs
* Confusion matrices
* ROC curves
* Training & validation curves
* XAI visualizations (LIME & SHAP)

---

## 💻 Project Structure

```
📦 bangla-sentiment-analysis
 ┣ 📜 README.md
 ┣ 📄 paper.pdf
 ┣ 📂 code/
 ┣ 📂 dataset/
 ┣ 📂 figures/
 ┗ 📄 requirements.txt
```

---

## 🚀 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run training
python train.py
```

---

## 🏁 Conclusion

This research demonstrates that transformer-based models significantly improve sentiment analysis performance for Bangla text. Among all models, BanglaBERT achieved the highest accuracy and best contextual understanding.

Explainable AI techniques further enhance model interpretability, making the system suitable for real-world applications.

---

## 🔮 Future Work

* Use larger Bangla datasets
* Improve cross-domain generalization
* Explore advanced transformer architectures
* Enhance multilingual capability

---

## 👨‍💻 Authors

* Sheikh Wasib Al Islam
* Md. Eshan Munshi

---

## 📄 Paper

📥 Full paper available in this repository (`paper.pdf`)
