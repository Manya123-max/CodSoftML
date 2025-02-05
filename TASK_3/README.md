# SMS Spam Classifier

## 📌 Project Overview
This project implements an **SMS Spam Classifier** using **TF-IDF** for feature extraction and **Naïve Bayes (MultinomialNB)** as the classification model. The goal is to automatically classify SMS messages as **Spam** or **Ham (Legitimate)**.

## 📂 Dataset
The dataset used for training and evaluation is a publicly available **SMS Spam Collection Dataset**, which consists of labeled SMS messages.

- **Columns in the dataset:**
  - `label`: Spam or Ham (0 for Ham, 1 for Spam)
  - `message`: The SMS text

## 🔧 Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/sms-spam-classifier.git
   cd sms-spam-classifier
   ```
2. Install required dependencies:
   ```sh
   pip install pandas numpy scikit-learn nltk seaborn matplotlib
   ```
3. Download NLTK stopwords:
   ```python
   import nltk
   nltk.download("stopwords")
   ```

## 🛠️ How It Works
1. **Data Preprocessing:**
   - Convert text to lowercase
   - Remove special characters and extra spaces
   - Remove stopwords
2. **Feature Extraction:**
   - Convert text into numerical format using **TF-IDF** (Term Frequency-Inverse Document Frequency)
3. **Model Training:**
   - Split data into **train (80%) and test (20%)** sets
   - Train a **Multinomial Naïve Bayes (MultinomialNB)** classifier
4. **Model Evaluation:**
   - Measure **accuracy, precision, recall, F1-score**
   - Visualize the **Confusion Matrix**

## 📊 Results
- **Accuracy:** ~97.5%
- **Precision & Recall:** High performance in detecting spam messages

### Sample Predictions:
| SMS Message | Predicted Label |
|-------------|----------------|
| WINNER!! You have won a prize of £900. Call now! | Spam |
| Hey, how are you doing? | Ham |
| FreeMsg: Claim your free holiday trip now! | Spam |

## 📈 Visualizations
- **Spam vs. Ham Distribution** 📊
- **Confusion Matrix** 🟦

## 🚀 Future Improvements
- Implement **Deep Learning (LSTM/BERT)** for better performance
- Deploy as a **Web App (Flask/Django)**

## 💻 Running the Code
To execute the script, run:
```sh
python spam_classifier.py
```

## 🔗 References
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [SMS Spam Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

---
Feel free to contribute and improve this project! 🎯


