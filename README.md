### 📋 Overview
This project implements an **End-to-End Machine Learning Pipeline** to predict student final grades (G3) based on demographic, social, and academic features. 

Unlike simple regression tasks, this repository performs a rigorous **Benchmarking Study** comparing classical algorithms (Random Forest, SVR) against modern Gradient Boosting frameworks (XGBoost, CatBoost) to maximize predictive accuracy.

### 🧠 Key Objectives
1.  **Factor Analysis:** Identify which features (e.g., study time, parental education, alcohol consumption) correlate most strongly with academic success.
2.  **Model Optimization:** Compare ensemble methods to reduce Mean Squared Error (MSE).
3.  **Data Integration:** Merging Mathematics and Portuguese course datasets to create a robust training corpus.

### 📂 Project Structure
* **`Ensemble_Model_Comparison_Student_Grades.ipynb`**: The core analysis notebook. It trains and evaluates four distinct models:
    * Random Forest Regressor
    * XGBoost (Extreme Gradient Boosting)
    * CatBoost (Categorical Boosting)
    * SVR (Support Vector Regression)
* **`RandomForest_Grade_Predictor.ipynb`**: A focused implementation of the Random Forest pipeline with detailed feature engineering.
* **`data/`**: Contains the UCI Student Performance datasets.

### 📊 Model Performance
| Model | R² Score | Performance Verdict |
| :--- | :--- | :--- |
| **Random Forest** | ~0.85 | Strong baseline, handles non-linearities well. |
| **XGBoost** | ~0.88 | Best performance on numerical features. |
| **CatBoost** | ~0.87 | Excellent handling of categorical variables without pre-encoding. |
| **SVR** | ~0.75 | Effective but requires extensive feature scaling. |

### 💻 Tech Stack
* **Languages:** Python 3.10+
* **ML Libraries:** `xgboost`, `catboost`, `scikit-learn`
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `seaborn`, `matplotlib`

### 🚀 How to Run
1. Install the required boosting libraries:
   ```bash
   pip install xgboost catboost scikit-learn pandas seaborn# Student-Performance-Prediction---Machine-Learning
