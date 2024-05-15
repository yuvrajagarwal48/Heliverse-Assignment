# Employee Attrition and Performance Analysis

This repository contains Python code for analyzing employee attrition and performance using the provided HR dataset. The analysis includes data preprocessing, visualization, and building machine learning models to predict attrition and performance ratings.

## Dataset
The dataset used for analysis is `WA_Fn-UseC_-HR-Employee-Attrition.csv`. It contains various features related to employee attributes and performance.

## Steps

### 1. Data Preprocessing
- **Handling Missing Values**: The analysis starts with checking for missing values in the dataset using `isnull()` and `isna()` methods. Missing values were handled appropriately, ensuring data integrity.
- **Converting Categorical Features**: Categorical features with binary values ("Yes" and "No") were converted to numerical (1 and 0) to facilitate model training.
- **Exploring Feature Types**: Different types of features (numerical, categorical, discrete, continuous) were explored to understand their distributions and relationships with attrition and performance ratings.

### 2. Visualization
- **Yearly Features Analysis**: Visualizations were created to examine the relationship between yearly features and performance rating/attrition. Line plots were used to show trends over time, providing insights into how these metrics change across different years or periods.
- **Discrete and Categorical Features Analysis**: Bar plots were generated to analyze how performance rating and attrition vary across different categories of discrete and categorical features. These visualizations help identify factors influencing employee performance and attrition within the organization.
- **Continuous Features Analysis**: Histograms were used to visualize the distribution of continuous features, while scatter plots (with or without logarithmic transformation) were employed to explore their relationship with performance rating and attrition. These visualizations offer insights into feature distributions and potential correlations with target variables.

### 3. Model Building
- **Model Selection**: Three different types of models (Logistic Regression, Random Forest, Support Vector Machine) were trained to predict attrition and performance ratings.
- **Evaluation Metrics**: Models were evaluated using various metrics such as accuracy, precision, recall, and F1-score to assess their performance in predicting attrition and performance ratings.

### 4. Conclusion
Based on the analysis:
- **Model Performance**: For Attrition Support Vector Machine was giving the best results and for Performance Rating Random Forest Classifier was giving the best results

## Files
- `employee_attrition_analysis.ipynb`: Jupyter Notebook containing the complete analysis code.
- `README.md`: This file providing an overview of the analysis.

## Usage
1. git clone git@github.com:yuvrajagarwal48/Heliverse-Assignment.git
2. Install the required libraries (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`) if not already installed.
3. Run the Jupyter Notebook `analysis.ipynb` to reproduce the analysis.
