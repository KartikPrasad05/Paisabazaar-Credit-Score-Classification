# Paisabazaar Credit Score Classification

## About the Project
This project uses machine learning to classify customers into three credit score categories: Good, Standard, and Poor. It analyzes customer financial information and credit-related features to understand patterns and predict credit score categories.

## Project Objectives
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Train a Random Forest classification model.
- Evaluate model performance.
- Compare standard and class-weighted Random Forest models.
- Identify important features influencing predictions.

## Dataset
- **File:** `bank_customers.csv`
- **Records:** 100,000
- **Features:** 28 columns
- **Target variable:** `Credit_Score`
- **Classes:** Good, Standard, Poor

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Workflow
1. Load and inspect the dataset.
2. Perform data quality checks.
3. Explore data using charts and visualizations.
4. Preprocess numerical and categorical features.
5. Train Random Forest classification models.
6. Evaluate models using accuracy, Macro F1-score, classification reports, and a confusion matrix.
7. Analyze feature importance.
8. Compare model performance and summarize findings.

## Model Results

| Model | Accuracy | Macro F1-score |
| Standard Random Forest | 68.91% | 0.6700 |
| Class-Weighted Random Forest | 68.25% | 0.6583 |

*These are the existing notebook results. Rerun the notebook to verify them before final submission.*

## How to Run
1. Download or clone this repository.
2. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Upload `bank_customers.csv` if it is not already available.
4. Update the dataset path if needed.
5. Run all notebook cells in order.

## Key Learnings
- Data analysis and visualization
- Data preprocessing
- Classification using Random Forest
- Model evaluation and comparison
- Feature importance analysis

## Author
**Kartik Prasad**

Computer Engineering Student | Data Scientist

## Disclaimer
This project is for educational purposes. Its predictions should not be used as the sole basis for real-world credit approval decisions.
