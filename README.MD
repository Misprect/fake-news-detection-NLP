---
## Fake News Detection using NLP & Machine Learning

### Project Overview

This project focuses on detecting **Fake**, **Real**, and **Misleading** news articles using Natural Language Processing (NLP) and classical Machine Learning techniques. The goal is to build a robust, explainable, and internship-ready system capable of analyzing news text and predicting its authenticity with confidence scores.
---

## Key Features

- Multi-class classification: **Fake | Misleading | Real**
- TF-IDF based text vectorization (unigrams + bigrams)
- Passive Aggressive Classifier for fast and scalable learning
- Confidence-based inference for real-world usability
- Confusion Matrix & detailed classification metrics
- Clean, readable, and interview-ready code

---

## Dataset

- Source: Public Fake News dataset
- Size: ~20,000 news articles
- Columns:

  - `text` → news content
  - `label` → fake / misleading / real

---

## Machine Learning Pipeline

1. Data Loading & Inspection
2. Train–Test Split (Stratified)
3. Text Vectorization using TF-IDF
4. Model Training (Passive Aggressive Classifier)
5. Model Evaluation (Accuracy, Precision, Recall, F1)
6. Visualization using Confusion Matrix
7. Confidence-based Prediction on new samples

---

## Model Performance

- **Accuracy:** ~90%
- Strong performance on Fake & Real classes
- Misleading class highlights real-world ambiguity in news classification

---

## Sample Inference Output

```
Prediction: 🟥 Fake News | Confidence: 59.35%
Prediction: 🟨 Misleading News | Confidence: 57.38%
Prediction: 🟩 Real News | Confidence: 56.07%
```

---

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- NLP (TF-IDF)

---

## Key Learnings

- How NLP converts text into numerical features
- Handling multi-class classification problems
- Importance of confidence scores in ML predictions
- Evaluating models beyond accuracy
- Understanding class imbalance and misleading content

---

## Future Improvements

- Handle class imbalance using resampling
- Try transformer models (BERT)
- Improve misleading news detection
- Deploy as REST API using FastAPI

---

## Author

**Aryaman Jain**
Data Science Intern

---
