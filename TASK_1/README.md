# Genre Classification using Machine Learning

## Overview
This repository contains a Machine Learning project that classifies movie genres based on plot descriptions. The model is trained using the **Naive Bayes algorithm** with **TF-IDF vectorization**. The dataset is provided in text files, and the project is implemented in **Python** using **Scikit-Learn** and **Pandas**.

## Dataset
The dataset consists of:
- **train_data.txt**: Training data containing movie IDs, titles, genres, and descriptions.
- **test_data.txt**: Test data containing movie IDs, titles, and descriptions.
- **train_data_solution.txt**: Ground truth labels for evaluation.

## Features & Technologies Used
- **Natural Language Processing (NLP)**: Preprocessing text data using regular expressions.
- **TF-IDF Vectorization**: Converting text data into numerical form.
- **Naive Bayes Classifier**: Training a Multinomial Naive Bayes model for classification.
- **Scikit-Learn**: Machine Learning library for model training and evaluation.
- **Google Colab Integration**: Using Google Drive to access dataset files.

## Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/genre-classification.git
   ```
2. Install the required dependencies:
   ```sh
   pip install pandas scikit-learn
   ```
3. Upload the dataset files to your Google Drive.
4. Run the script in **Google Colab**.

## Usage
1. The script reads the dataset from Google Drive.
2. It preprocesses the text data by removing special characters and converting to lowercase.
3. It vectorizes the text using **TF-IDF**.
4. It trains a **Naive Bayes classifier** and makes predictions on the test set.
5. It evaluates the model using **accuracy score** and **classification report**.
6. The predictions are saved to a CSV file in the dataset directory.

## Model Evaluation
- The dataset is split into **80% training** and **20% validation**.
- The validation accuracy is calculated using **Scikit-Learn's accuracy_score**.
- A classification report is generated to evaluate precision, recall, and F1-score.
- The report is saved to `classification_report.txt`.

## Output
- The predicted genres are displayed in the console.
- A CSV file (`test_predictions.csv`) is generated containing the predictions.
- The classification report is saved for further analysis.

## Future Improvements
- Experiment with **other ML models** like Logistic Regression or SVM.
- Use **Word Embeddings** (Word2Vec, GloVe) instead of TF-IDF.
- Fine-tune **hyperparameters** to improve accuracy.
- Integrate a **web interface** for user interaction.

## Author
**Manya Vishwakarma** - Machine Learning Intern at **CodSoft**


