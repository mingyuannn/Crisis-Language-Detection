# Crisis-Language-Detection

This project identifies at-risk social media posts using NLP. We prioritize **Recall** to minimize the risk of missing critical "at-risk" indicators.

## Performance Summary
| Model | Recall | Precision | F1-Score | AUC-ROC |
| :--- | :---: | :---: | :---: | :---: |
| **Naive Bayes** | **0.9466** | 0.8840 | 0.9142 | 0.9730 |
| Logistic Regression | 0.9398 | 0.7899 | 0.8584 | 0.9409 |

---

## How to Run

Since the dataset is too large for GitHub, it is hosted on Google Drive. The notebook is pre-configured to download it automatically.

1.  **Open the Notebook**: Click the badge below to open the notebook directly in Google Colab:
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/你的GitHub用户名/你的仓库名/blob/main/Crisis_Language_Detection.ipynb)

2.  **Run All**: In Colab, go to **Runtime > Run all**.

> **Note**: If you are viewing the `.ipynb` file directly on GitHub, you can see the pre-rendered results and charts without running any code.

---

##  Project Assets
- `Crisis_Language_Detection.ipynb`: Main analysis and model training.
- [External Data Link](https://drive.google.com/drive/folders/19-W7V1vS1zTFE18xpWKBjsr2BUlHW3g-): Access the raw CSV files on Google Drive.

##  Methodology
1. **Data Preprocessing**: Large-scale text cleaning and normalization.
2. **Modeling**: Comparison of Naive Bayes and Logistic Regression.
3. **Evaluation**: Optimized for Recall to ensure safety-first detection.


##  License
This project is for educational purposes as part of the PAML Final Project.
