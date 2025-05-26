
# 📧 Email Spam Detection Using Machine Learning

## 📝 Introduction

This project aims to detect spam emails using a machine learning approach, specifically using the Naive Bayes algorithm. It processes raw text messages from a dataset, converts them into numerical features using NLP techniques, and classifies them as "spam" or "ham" (not spam). The project is implemented in Python using Google Colab and relies on open-source libraries such as `scikit-learn`, `pandas`, and `nltk`.

---

## ⚙️ How to Run the Code

You can run this project using **Google Colab** by following these steps:

1. **Open the notebook**:  
   Upload or open `email_spam_detection.ipynb` on [Google Colab](https://colab.research.google.com/)

2. **Run cells step-by-step**:
   - Upload the dataset (CSV file, e.g., `spam.csv`)
   - Execute all the code cells from top to bottom

3. **Check outputs**:
   - The notebook will display accuracy, confusion matrix, and classification results

---

## 🔧 Pre-installation

If you are running the project **locally (not in Colab)**, ensure the following libraries are installed:

```bash
pip install pandas scikit-learn nltk
```

Also, download required NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

## 📌 Pre-requisites

Make sure you have:

- Python 3.7 or above
- Basic knowledge of Jupyter Notebook or Google Colab
- Dataset: SMS Spam Collection Dataset (`spam.csv`)
  - [Download from Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## 📁 Project Structure

```
📦 Email-Spam-Detection/
├── email_spam_detection.ipynb      # Colab notebook
├── spam.csv                        # Dataset
├── README.md                       # Project readme
├── Email_Spam_Detection_PPT.pptx  # Presentation
└── report.pdf                      # Detailed project report
```

---

## 📊 Output Example

```
Accuracy: 98.2%
Confusion Matrix:
[[961   4]
 [ 14 136]]
```

---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [NLTK Documentation](https://www.nltk.org/)
- [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---
