#  Wine Dataset Analysis

This project performs an end-to-end exploratory and predictive analysis on a wine dataset, aiming to understand chemical composition patterns across wine classes and apply classification models to predict wine categories.

##  Project Structure

- **Exploratory Data Analysis (EDA)**  
  - Visualized feature distributions using histograms and KDE plots.  
  - Checked for outliers and skewness.  
  - Examined feature correlations via heatmaps and pair plots.

- **Data Preprocessing**  
  - Identified skewed features and applied PowerTransformer for normalization.  

- **Modeling**  
  - Implemented two classification models: Logistic Regression and Random Forest.  
  - Built pipelines with preprocessing and modeling steps .  
  - Evaluated models using classification_report.

## Key Insights

- Features such as Malic acid and Magnesium were noticeably skewed and benefited from transformation.
- Correlation analysis revealed strong negative relationships between Flavanoids and the target class.
- Random Forest and Logistic Regression classifier both achieved perfect classification on the test set.

##  Tools and Libraries Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (Pipeline, PowerTransformer, RandomForest, LogisticRegression, Metrics)
