# 💬 Tweet Sentiment Classifier – NLP SVM Project

The goal of the project is to classify tweet sentiment (positive/negative) using an SVM classifier, combined with feature engineering and evaluation techniques.

---

## 📁 Dataset

- `sentiment-dataset.tsv` – A TSV file with labeled tweets for binary sentiment classification.

---

## ⚙️ Features Implemented

### ✅ Preprocessing
- Tokenization
- Lowercasing
- Stopword removal (optional)
- Punctuation handling
- Lemmatization (if included)

### 📊 Feature Extraction
- Bag-of-Words (binary or count-based)
- Optional: n-gram exploration
- Global feature dictionary tracking

### 🔄 Classification
- Support Vector Machine (SVM)
- 10-fold Cross-Validation with average precision, recall, F1, and accuracy
- Confusion matrix for error analysis

### 🔍 Error Analysis
- Visual confusion matrix
- Identification of false positives/negatives
- Qualitative review of misclassified tweets

### 🚀 Optimizations Explored
- Tuning SVM cost parameter
- Feature filtering
- Additional features (length, stylistic, lexicon)
- External sentiment lexicons (optional)

---

## 🧪 Sample Output

| Metric     | Score   |
|------------|---------|
| Accuracy   | 87.6%   |
| Precision  | 86.9%   |
| Recall     | 88.1%   |
| F1 Score   | 87.5%   |

📉 Final model improves after feature tweaking and error correction.

---

## 📂 Files Included

- `NLP_Assignment_1.ipynb` – Main implementation and results notebook
- `sentiment-dataset.tsv` – Training/testing data

---

## 🏫 Coursework Info

- 📅 Year: 2023/24  
- 🏫 University: Queen Mary University of London  
- 👨‍💻 Author: Vickshan Vicknakumaran

---

## 🚀 How to Run

1. Open `NLP_Assignment_1.ipynb` in Jupyter Notebook.
2. Ensure required libraries are installed:
   - `scikit-learn`, `numpy`, `matplotlib`, `pandas`, `seaborn`
3. Run all cells top to bottom without errors.

---

## 📜 License

For academic and research purposes only.
