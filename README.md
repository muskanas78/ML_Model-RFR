# House Price Prediction with Random Forest Regressor  

### Project Overview  
Predicts house prices using a Random Forest Regressor model after performing data cleaning, feature engineering, and hyperparameter tuning.  

### Key Steps  
- **Data Cleaning**: Removed features with >10% null values and imputed remaining missing data  
- **Feature Engineering**: Log-transformed skewed numerical features and label-encoded categorical variables  
- **Model Training**: Optimized hyperparameters using RandomizedSearchCV  
- **Evaluation**: Achieved **R2 score: 0.864**, **RMSE: 29,313**, and **MAE: 17,900**  

### Conclusion
High R2 (0.864) indicates the model explains 86% of price variance, while MAE ($17,900) shows average prediction error is acceptable for real-world use.  
The model reliably predicts housing prices with strong metrics, making it suitable for practical applications.

<div style="display: flex; justify-content: space-between; align-items: center;">
  <img src="https://github.com/user-attachments/assets/6bbbb081-1887-4d35-9a2b-0d3f8647e886" alt="Image">
</div>
