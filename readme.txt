1.Data Cleaning​
- Exploratory Data Analysis & Visualization​
- Dealt with missing values​
- Log target variables for better distribution​
- Normalized data using skew and Box Cox transformations​
- Applied RobustScaler on number columns​
- Shifted outliers of prime attributes closer to the linear regression and used ZScore to drop outliers of other attributes.​
​
2. Hyperparameter tuning using Random Search​
​
3. Model building, stacking regression methods.​
- experimented with: xgBoost, Lasso, Ridge, SVR, LGBM, Gradient Boosting Regressor, Keras, Tensor Flow, ENet, KRR.​
​
4. Testing & validating the model​
​
5. Final prediction: -> Ridge, Lasso as meta regressors + SVR, LGBM and Gradient Boosting Regressor.​