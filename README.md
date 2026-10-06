# mental_health_score
# Student Social Media and Mental Health Analysis

## Project Overview

This project explores the relationship between social media usage and mental health among students. Using machine learning and exploratory data analysis (EDA), we aim to identify patterns, trends, and factors that influence mental well-being.

## Dataset

Dataset: Student Social Media And Mental Health Impact.csv

The dataset contains information about:
- Student demographics
- Social media usage patterns
- Screen time
- Platform usage
- Mental health indicators
- Academic and lifestyle factors

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Identify correlations between social media usage and mental health
- Handle missing values and outliers
- Engineer useful features
- Train and evaluate machine learning models
- Generate actionable insights through visualizations

## Project Structure

```
├── data/
│   └── Student Social Media And Mental Health Impact.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_model_building.ipynb
│
├── images/
│   └── visualizations
│
├── models/
│   └── saved_models
│
├── requirements.txt
├── README.md
└── main.py
```

## Exploratory Data Analysis

Key analyses performed:

- Distribution of social media usage
- Mental health score analysis
- Correlation heatmap
- Gender-wise comparisons
- Platform-wise usage patterns
- Screen time impact on mental health
- Feature distributions and outlier analysis

## Machine Learning Pipeline

### Data Preprocessing
- Missing value treatment
- Encoding categorical variables
- Feature scaling
- Train-test split

### Models
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (if used)

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Results

The analysis highlights how different social media usage behaviors may influence student mental health outcomes. Model performance and key insights are discussed in the notebooks.

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/student-social-media-mental-health.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

## Future Improvements

- Hyperparameter tuning
- Advanced feature engineering
- Deep learning approaches
- Interactive dashboard using Streamlit
- Real-time prediction system

## Author

Utsav

## License

This project is licensed under the MIT License.
