# Overview

The goal of this project is to develop a model to be used in fraud detection. This task presents special challenges as the class of interest - cases of fraud - are a small minority. Caution should also be exercised in the handling of outliers as these may be important in the determination of fraudulent cases.

After some exploratory data analysis, SMOTE is applied to augment the minority class. An SVM model is selected, fit, and evaluated. Then an XGBoost model is trained and evaluated. Finally, a Random Forest model is tried.
