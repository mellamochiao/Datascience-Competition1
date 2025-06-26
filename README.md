# Data Science CP1 Competition Project

##  Task Overview
This is the course competition project for "Introduction to Data Science".  
The goal is to perform **binary classification** on 49 different datasets using various machine learning models.

##  Project Structure

- `model/`:  
  Contains all the `.ipynb` notebooks for model training and experimentation.  
  - `logistic_regression.ipynb`
  - `random_forest.ipynb`
  - `xgboost.ipynb`
  - `LightGBM.ipynb`
  - `stacking.ipynb`  
  etc.

- `CP1report.pdf`:  
  Final report containing:
  - Data insights and analysis
  - Model comparisons
  - Hyperparameter tuning
  - Leaderboard performance

## Selected Best Models (Based on Performance)

In our final report, we focus on the three best-performing models:
- **Random Forest**: A powerful ensemble of decision trees with good generalization.
- **XGBoost**: A gradient boosting framework that yielded the best accuracy.
- **Logistic Regression**: Served as both a baseline and a surprisingly competitive model.

These models were selected based on their private leaderboard performance and stability across datasets.

> ⚠️ Note: The competition dataset is **not included** in this repository due to course policy.

##  Methods Used
- Scikit-learn: Logistic Regression, KNN, Random Forest, etc.
- Advanced models: XGBoost, LightGBM
- Ensemble: Stacking

##  Evaluation
- Public leaderboard used half of the test data
- Private leaderboard (revealed after competition) determined the final grade


##  References
- XGBoost: https://arxiv.org/abs/1603.02754  
- LightGBM: https://papers.nips.cc/paper_files/paper/2017/hash/6449f44a102fde848669bdd9eb6b76fa-Abstract.html  
