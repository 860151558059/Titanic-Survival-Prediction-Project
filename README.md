# Titanic-Survival-Prediction-Project
This project is based on the Titanic dataset, a popular beginner-friendly dataset in data science and machine learning. The goal is to analyze the data, clean it, and predict which passengers were likely to survive using machine learning models.

Objective

To explore the Titanic dataset, clean the data, perform exploratory data analysis (EDA), and build a predictive model for passenger survival.

Technologies and Libraries Used

- Python
- Pandas – for data manipulation
- NumPy – for numerical operations
- Matplotlib & Seaborn – for data visualization
- Scikit-learn – for model building and evaluation

Project Workflow

1. Loading the dataset
2. Data cleaning
   - Handling missing values in 'Age', 'Embarked', etc.
   - Dropping irrelevant columns
3. Feature Engineering
   - Encoding categorical columns using `pd.get_dummies`
   - Mapping binary values
4. Exploratory Data Analysis (EDA)
   - Box plots, histograms, correlation heatmaps
5. Splitting the dataset
   - Using `StratifiedKFold` instead of `train_test_split` for balanced class distribution
6. Model Building
   - Applying machine learning algorithms
   - Evaluating model accuracy and confusion matrix


What I Learned

Throughout this project, I learned:

- How to clean and preprocess real-world datasets
- Handling null values and encoding categorical features
- Using visualization tools to explore and understand data
- The importance of stratified sampling when working with imbalanced datasets
- How to split data without using `train_test_split` by applying `StratifiedKFold`
- How to save cleaned datasets and export results
- How to document and share a project effectively on GitHub

Future Improvements

- Try advanced models like Random Forest, XGBoost, or SVM
- Use hyperparameter tuning (GridSearchCV)
- Deploy the model using Flask or Streamlit
- Create an interactive dashboard to show predictions
