# Crisis-Language-Detection
# Suicide Detection Analysis 

This project focuses on identifying at-risk social media posts using Natural Language Processing (NLP). We compare Machine Learning models to prioritize **Recall**, ensuring that fewer potential "at-risk" cases are missed.

## Performance Summary
Our analysis compares Logistic Regression and Naive Bayes. The **Naive Bayes** model performed best for our primary goal (Recall).

| Model | Recall | Precision | F1-Score | AUC-ROC |
| :--- | :---: | :---: | :---: | :---: |
| **Naive Bayes** | **0.9466** | 0.8840 | 0.9142 | 0.9730 |
| Logistic Regression | 0.9398 | 0.7899 | 0.8584 | 0.9409 |

> **Note:** We prioritized **Recall** because, in suicide detection, missing a true positive (a person at risk) has much higher consequences than a false alarm.

---

##  Dataset
The dataset used in this project is `clean_data.csv`. Due to its large size (exceeding GitHub's 100MB limit), it is hosted on Google Drive.

### How to access the data:
The Google Colab notebook is configured to **automatically download** the dataset using `gdown`. You do not need to manually upload or mount a drive to run the analysis.

---

##  How to Run the Project
1. Open the `.ipynb` file in **Google Colab**.
2. Run the first cell to install `gdown` and download the dataset from the remote source.
3. Select **Runtime > Run all** from the top menu.

### Prerequisites
- Python 3.x
- Pandas
- Scikit-learn
- Gdown (for data fetching)

---

##  Methodology
1. **Data Cleaning**: Preprocessing text, removing noise, and handling missing values.
2. **Vectorization**: Converting text data into numerical format suitable for ML models.
3. **Model Training**: Implementing Logistic Regression and Naive Bayes.
4. **Evaluation**: Focusing on the confusion matrix, specifically minimizing False Negatives.



##  License
This project is for educational purposes as part of the PAML Final Project.
