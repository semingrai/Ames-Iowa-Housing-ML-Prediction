# 🏠 Ames Housing Price Prediction
 
Machine learning model to predict residential home sale prices in Ames, Iowa using Gradient Boosting regression with optimized feature engineering.

## 📊 Results
 
| Metric | Value |
|--------|-------|
| **R² Score** | **88.0%** |
| **Model** | Gradient Boosting Regressor |
| **Learning Rate** | 0.05 |
| **Dataset** | 1,460 properties, 80 features |

## 🚀 Key Features

- Feature selection using Mutual Information
- Hyperparameter tuning (learning rate optimization)
- 5-fold cross-validation
- Missing data handling with SimpleImputer

## 🛠️ Tech Stack

- Python 3.x 
- pandas
- scikit-learn (GradientBoostingRegressor, cross_val_score)

## 🔧 Approach

1. **Data Preprocessing** - Handle missing values, encode categorical features
2. **Feature Engineering** - Remove low-importance features using MI scores
3. **Model Optimization** - Test learning rates (0.3 → 0.05 optimal) and estimators
4. **Evaluation** - Cross-validation with consistent 84-90% R² across folds

## 🎯 Key Insights

- Lower learning rate (0.05) significantly improved performance (+1.7%)
- Feature quality > quantity - removing noise improved accuracy
- Model converged at ~200 estimators

## 👨‍💻 Author

**Seming Rai**