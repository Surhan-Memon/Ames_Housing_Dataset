# Ames_Housing_Dataset
Built a regression pipeline to predict house sale prices using the Ames Housing dataset. The workflow included exploratory data analysis, outlier removal, missing value imputation, and feature engineering with one-hot encoding for categorical variables.
Features were scaled using StandardScaler to handle varying units and magnitudes. An ElasticNet regression model was tuned using GridSearchCV with 5-fold cross-validation, searching over alpha and L1 ratio parameters to find the optimal regularization balance between Lasso and Ridge.
The final model achieved an R² score of 0.918 on the held-out test set, meaning it explains approximately 91.8% of the variance in house sale prices.
