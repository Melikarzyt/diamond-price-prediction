## 📝 Project Overview

This project focuses on predicting the prices of diamonds using a **Linear Regression** model. The dataset contains various features related to each diamond such as:

- Weight (`carat`)
- Quality (`cut`, `color`, `clarity`)
- Dimensions (`x`, `y`, `z`)

The main goal is to apply key data preprocessing techniques such as:

- Encoding categorical variables
- Scaling numerical features
- Combining all processed data into a final dataset

Then, a regression model is trained to predict diamond prices on unseen test data.

This project is a great practice for applying fundamental machine learning steps such as:

- Data cleaning
- Data preprocessing
- Model training
- Model evaluation
- Generating final predictions

---

## ✅ Tasks Completed

- 📥 Loaded training and test data using **pandas**
- 🧮 Separated the target variable (`price`) from the features
- 🔤 Handled categorical features (`cut`, `color`, `clarity`) using **One-Hot Encoding**
- 📏 Scaled numerical features (`carat`, `depth`, `table`, `x`, `y`, `z`) using **StandardScaler**
- 🧩 Combined the processed categorical and numerical features into final datasets
- 🤖 Trained a **Linear Regression** model on the processed training data
- 📈 Evaluated model performance using **R² score**
- 💎 Predicted prices for **3940** diamonds in the test set
- 💾 Saved predictions to a file named `submission.csv`
 
