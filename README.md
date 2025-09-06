# Bonus-assignment-MAIM
# Tweet Sentiment Classification (NLP Assignment)

## 📌 Objective
The goal of this project is to practice:
- Text preprocessing  
- Word representations (Bag of Words & Word2Vec embeddings)  
- Sequence models (LSTM/GRU)  
- Model evaluation (accuracy, confusion matrix, ROC)  

We build a **tweet sentiment classifier** to compare traditional ML models with deep learning approaches.

---

## 📊 Dataset
We use the **Sentiment140 dataset**, which contains **1.6 million tweets** labeled as positive or negative.  

- **0 = Negative sentiment**  
- **4 = Positive sentiment**  

🔗 Dataset link: [Sentiment140 on Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)

---

## 📂 Project Structure
- `nlp_twitter.ipynb` → Main Jupyter/Colab notebook with code  
- `README.md` → Project documentation  

The notebook covers:
1. Data Acquisition & Cleaning  
2. Feature Representations (BoW + Word2Vec)  
3. Modeling (Logistic Regression, Naive Bayes, LSTM)  
4. Evaluation (Accuracy, Confusion Matrix, ROC Curves)  
5. Reflection  

---

## ⚙️ Requirements
Install dependencies locally, or run on **Google Colab** where most are preinstalled.

```bash
pip install numpy pandas scikit-learn matplotlib seaborn nltk tensorflow
