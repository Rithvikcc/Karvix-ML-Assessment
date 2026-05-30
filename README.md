# Karvix-ML-Assessment
Ml assignment on Buildling a Machine Learning classification project capable of predicting whether a candidate will be hired
based on features such as age, salary, and years of experience. The assessment is designed to
evaluate your understanding of data preprocessing, exploratory data analysis, machine learning
workflows, model evaluation, and project structuring.

# Kravix Tech - ML Internship Assessment

## Problem Statement
Predict whether a job candidate will be hired based on features 
like age, experience, interview score, and skill score.
Binary Classification: 0 = Not Hired, 1 = Hired

## Dataset
- Source: Kaggle
- Link: https://www.kaggle.com/datasets/rabieelkharoua/predicting-hiring-decisions-in-recruitment-data
- Rows: 1500 | Features: 10 | Target: HiringDecision

## Models Used
| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | 85.67% | 0.8911 |
| Random Forest | 94.00% | 0.9287 |

**Best Model: Random Forest**

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/Rithvikcc/Karvix-ML-Assessment.git
cd Karvix-ML-Assessment
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
Open `kravix_assessment.ipynb` in Jupyter or Google Colab and run all cells.

## Project Structure

## Requirements
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, scikit-learn
