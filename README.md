# Hybrid Fuzzy Model for Interpretable Heart Disease Risk Prediction

## Project Goal

The primary goal of this project is to explore how hybrid computational intelligence approaches can balance predictive performance and interpretability in healthcare AI systems. The proposed framework highlights the potential of fuzzy logic as an explainable component within modern machine learning pipelines.

***

This project presents a hybrid computational intelligence framework for heart disease risk prediction by combining fuzzy logic with traditional machine learning models. The main objective is to improve interpretability in medical decision-making while maintaining competitive predictive performance. Unlike purely black-box approaches, the proposed system generates human-readable reasoning through fuzzy inference and interpretable risk scoring.

The project uses the UCI Heart Disease dataset and focuses on clinical features such as age, thalach (maximum heart rate), and oldpeak (ST-segment depression). A fuzzy inference system is designed using data-driven membership functions and IF–THEN rules derived from exploratory data analysis. The fuzzy component produces a continuous risk score that reflects the severity of heart disease risk in an explainable manner. This score is then integrated into machine learning models such as Logistic Regression and Random Forest to create a hybrid prediction framework.

Experimental results show that the fuzzy risk score captures meaningful clinical patterns and strongly correlates with disease presence. The hybrid models achieve performance comparable to strong baseline models while providing additional transparency and interpretability. The project demonstrates that explainable AI techniques can be integrated into predictive healthcare systems without significant loss in performance.

***

## Key Features
- Interpretable fuzzy inference system
- Continuous fuzzy risk scoring
- Hybrid fuzzy + machine learning framework
- Explainable IF–THEN rule-based reasoning
- Logistic Regression and Random Forest baselines
- Evaluation using Accuracy, F1-score, and ROC-AUC

***

## Technologies
- Python
- NumPy
- Pandas
- Scikit-learn
- scikit-fuzzy
- Matplotlib

## Setup Instructions: 

You can just download the notebook and open it in Jupyter Notebook or Google Colab environement. Or if you love fancy things, try these: 

1. Clone the repository: 

- `git clone https://github.com/mechaphantom/Hybrid-Fuzzy-Model-for-Interpretable-Heart-Disease-Risk-Prediction.git`
- `cd Hybrid-Fuzzy-Model-for-Interpretable-Heart-Disease-Risk-Prediction`

2. Create and activate a virtual environment (recommended):

- `python -m venv venv`

3. Install reqirements (we dont have it btw)

- `pip install -r requirements.txt`

## Dependencies

- `numpy`
- `pandas`
- `scikit-learn`
- `scikit-fuzzy`
- `matplotlib`
- `seaborn`
- `jupyter` 

You can install them by following this code: `pip install numpy pandas scikit-learn scikit-fuzzy matplotlib seaborn jupyter`

## Steps to Reproduce Results

1. Download or place the UCI Heart Disease dataset inside the data/ directory.
2. Open the Jupyter Notebook:
3. Run the notebook cells sequentially to:
  - preprocess the dataset
  - perform exploratory data analysis (EDA)
  - generate fuzzy membership functions
  - compute fuzzy risk scores
  - train baseline ML models
  - train hybrid fuzzy + ML models
  - evaluate results using Accuracy, F1-score, and ROC-AUC
    
4. Final evaluation metrics and visualizations will be generated automatically at the end of the notebook execution
