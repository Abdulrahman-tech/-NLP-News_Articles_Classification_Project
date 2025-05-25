# [NLP] News Articles Classification (RNN + DistilBERT)

This project solves a news classification task with the aim of labeling news headlines and descriptions into one of 41 predefined categories.

## 🚀 Project Summary

We explore two NLP-based deep learning approaches:
- ✅ Simple RNN model
- ✅ Transformer-based model using **DistilBERT** from Hugging Face

### 📌 Problem Statement
> Build a robust news classification model using deep learning techniques and deploy it for reporters to classify and label news articles.

### 📦 Dataset
- Kaggle: [`news-category-dataset`](https://www.kaggle.com/datasets/rmisra/news-category-dataset)
- Contains news headlines and short descriptions from HuffPost, labeled into 41 unique categories.

### 🧠 Model Evaluation
```
Accuracy       : 62%
Macro F1-score : 0.51
Weighted F1    : 0.61
Test Samples   : 20,953
```

### 📚 Libraries Used
- Python, Pandas, NumPy
- PyTorch, Hugging Face Transformers
- Scikit-learn, Matplotlib, Seaborn

### 📁 Project Structure
```
/data          # Dataset folder or Kaggle link
/notebooks     # Jupyter Notebooks
/src           # Source code (models, preprocessing, utils)
/outputs       # Model checkpoints, logs
README.md
requirements.txt
project_report.pdf
```

### 📜 License
Distributed under the MIT License. See `LICENSE` for more information.
