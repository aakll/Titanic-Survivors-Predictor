# Titanic Survivors Predictor

## 📌 Project Overview
This is a beginner-level machine learning project that predicts whether a passenger survived the Titanic disaster based on features such as **age, sex, passenger class, and fare**.  
The project is implemented in Python using **Jupyter Notebook** and is intended as a learning exercise to practice data preprocessing, feature engineering, model building, and evaluation.

## 🛠 Tools & Libraries Used
- **Python 3**
- **pandas** – for data loading and manipulation  
- **matplotlib / seaborn** – for data visualization  
- **scikit-learn** – for model building and evaluation  
- classification models

## 🚀 How It Works
1. Load the Titanic dataset (CSV file).  
2. Explore and clean the data (handle missing values, encode categorical variables).  
3. Perform **feature engineering**:
   - Extracted **titles** from passenger names  
   - Grouped **ages** into categories  
   - Extracted additional information from **ticket numbers**  
4. Train multiple machine learning models and compare their performance:  
   - **LogisticRegression**: 81.56% accuracy  
   - **RandomForestClassifier**: 82.68% accuracy  
   - **XGBClassifier**: 83.24% accuracy  

## 📂 Files in This Project
- `titanicSurvivorsPredictor.ipynb` – The Jupyter Notebook containing all the code and analysis.  
- `README.md` – This file.
- `xgb_model.joblib` - The model.
- `Data` - The data used

## 📊 Current Results
- **LogisticRegression**: 81.56% accuracy  
- **RandomForestClassifier**: 82.68% accuracy  
- **XGBClassifier**: 83.24% accuracy  

While the accuracy is already promising, this project focuses on learning the workflow — **further optimization will be done in future updates**.

## 📈 Future Improvements
- Perform additional feature engineering (e.g., family size grouping, cabin grouping).  
- Apply advanced hyperparameter tuning for all models.  
- Try more ensemble methods like **Gradient Boosting** or **Stacking**.  
- Improve data preprocessing steps.  

## ▶️ How to Run
1. Install the required libraries:  
   ```bash
   pip install pandas matplotlib seaborn scikit-learn xgboost
   ```
2. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook titanicSurvivorsPredictor.ipynb
   ```
3. Run the cells in order to see the analysis and predictions.
