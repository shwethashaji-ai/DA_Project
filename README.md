💼 Data Science Salary Analysis and Modeling

This project analyzes a large dataset of salaries in the data science industry and builds a machine learning model to predict company size based on job and salary-related features.

📂 Project Structure

Data Source:
salaries.csv (original dataset with ~94,434 rows)
Notebook Steps:
Importing necessary libraries
Loading the dataset
Exploratory Data Analysis (EDA)
Handling missing values
Removing duplicates
Encoding categorical variables
Data visualization
Outlier detection
Scaling numerical features
Dimensionality Reduction using PCA
Splitting the data for model training
Model training with Random Forest
Model evaluation
Saving cleaned data
📊 Exploratory Data Analysis

Checked basic dataset info
Verified missing values (none found initially)
Examined summary statistics
Visualized feature correlations using a heatmap
Plotted boxplots for outlier detection
🧹 Data Cleaning

Filled missing values (although none were present)
Dropped duplicate records:
Original rows: 94,434
Duplicates removed: 47,339
Final rows: 47,095
🔧 Feature Engineering

Label encoding applied to categorical features:
experience_level
employment_type
job_title
salary_currency
employee_residence
company_location
company_size
Features scaled using StandardScaler
Dimensionality reduced to 2 components using PCA for visualization
🤖 Model Training

Model Used: Random Forest Classifier
Target Variable: company_size
Data split: 80% train, 20% test
Achieved model accuracy: 1.0 (perfect)
⚠️ Note: Perfect accuracy might indicate data leakage or overly simple patterns. Further validation is recommended.
🗂️ Output

Cleaned dataset saved as:
cleaned_data.csv
PCA visualization and multiple plots created during analysis
🚀 How to Run This Notebook

Upload salaries.csv to your Colab environment.
Run the notebook cells in order.
Check model performance and visualizations.
Use cleaned_data.csv for further analysis.
✅ Requirements

Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
💡 Future Improvements

Tune hyperparameters for Random Forest
Try other models (e.g. XGBoost, LightGBM)
Handle potential class imbalance
Deeper feature engineering
Implement model explainability tools (SHAP, LIME)
