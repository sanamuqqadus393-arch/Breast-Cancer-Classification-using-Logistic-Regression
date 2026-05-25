# 🔬 Breast Cancer Classification using Logistic Regression

A machine learning project that classifies breast tumors as **malignant** or **benign** using logistic regression. Achieves 94–97% accuracy on the scikit-learn breast cancer dataset.

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview

Breast cancer is one of the most common cancers worldwide. Early and accurate classification can significantly improve treatment outcomes. This project demonstrates a basic but complete ML workflow — from data loading to model evaluation — using logistic regression as the classifier.

## Results

| Metric | Score |
|---|---|
| Accuracy | 94–97% |
| Model | Logistic Regression |
| Dataset size | 569 samples, 30 features |
| Classes | Malignant (0), Benign (1) |

## ML Workflow

1. **Load data** — scikit-learn's built-in breast cancer dataset
2. **Explore data** — check shape, feature names, class distribution
3. **Preprocess** — standardize features with `StandardScaler`
4. **Split** — 80/20 train-test split
5. **Train** — fit `LogisticRegression` model
6. **Evaluate** — accuracy score, confusion matrix, classification report
7. **Visualize** — confusion matrix heatmap

## Getting Started

### Prerequisites

- Python 3.10+
- pip

### Installation

```bash
git clone https://github.com/sanamuqqadus393-arch/Breast-Cancer-Classification-using-Logistic-Regression.git
cd Breast-Cancer-Classification-using-Logistic-Regression
pip install -r requirements.txt
```

### Run in Jupyter

```bash
jupyter notebook project1_Breast_cancer_classification.ipynb
```

### Run in Google Colab

Click the badge or upload the `.ipynb` file to [Google Colab](https://colab.research.google.com/).

## Project Structure

```
Breast-Cancer-Classification/
├── project1_Breast_cancer_classification.ipynb   # Main notebook
├── breast_cancer_dataset.csv                      # Dataset (from scikit-learn)
├── requirements.txt                               # Python dependencies
├── .gitignore
├── LICENSE
└── README.md
```

## Technologies Used

- Python 3.10+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

## What I Learned

- Complete ML pipeline from raw data to evaluation
- Feature standardization and why it matters for logistic regression
- Reading confusion matrices and classification reports
- Visualizing model performance with seaborn

## Future Improvements

- [ ] Try other classifiers (SVM, Random Forest, KNN) and compare
- [ ] Add cross-validation for more reliable accuracy estimates
- [ ] Build a simple prediction form with user-entered values
- [ ] Deploy as a web app using Streamlit

## License

MIT License — see [LICENSE](LICENSE) for details.

## Author

**Sana Muqqadus** — [LinkedIn](https://www.linkedin.com/in/sana-muqqadus-9b5a35348) · [Fiverr](https://www.fiverr.com/s/KeKgrpV)
