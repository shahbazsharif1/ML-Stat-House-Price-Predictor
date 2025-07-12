# 🔍 ML-Stat-House-Price-Predictor

**A comparative analysis of machine learning and statistical models to predict house prices across Boston and California datasets.**

---

## 🧠 Why This Project Matters

Accurate house price prediction guides investment strategy, city planning, and public policy. This project explores how traditional statistical approaches perform compared to modern machine learning techniques—uncovering which model delivers higher accuracy and better generalizability across diverse datasets.

---

## ✨ Highlights

- 📈 Achieved **90%+ R²** on the Boston dataset with tuned **XGBoost**, reducing RMSE by **40%** compared to linear baselines  
- 🧪 Built a complete pipeline: **data cleaning → feature engineering → model training → evaluation → visualization**  
- 🛠️ Benchmarked five models: `Linear`, `Ridge`, `KNN`, `Random Forest`, and `XGBoost`—with and without hyperparameter tuning  

---

## 🗃️ Data Overview

- **California Housing**: 20,640 rows · 10 features  
- **Boston Housing**: 506 rows · 13 features  
- 🔍 Features include: geographic coordinates, median income, total rooms, proximity to ocean, etc.

---

## 🏆 Key Achievements

- 📓 Organized reusable Python scripts & Jupyter notebooks for reproducibility  
- 🧹 Performed missing-value imputation, outlier detection, one-hot encoding, and log transformation  
- ⚙️ Tuned `Random Forest` & `XGBoost` using `GridSearchCV` for optimal performance  
- 📊 Created compelling visualizations: heatmaps, Q-Q plots, residual analysis, model comparison charts  

---

## 🧰 Tech Stack

| Tool         | Role                  |
|--------------|------------------------|
| 🐍 Python 3.8+ | Programming Language  |
| 📦 pandas, NumPy | Data Manipulation    |
| 🎯 scikit-learn | ML & Statistical Models |
| ⚡ XGBoost      | Gradient Boosting     |
| 📈 matplotlib, seaborn | Visualization  |
| 📓 Jupyter Notebook | Interactive Analysis |

---

## 🔬 Methodology

### 1. 📊 Data Preprocessing
- Imputed missing bedroom values with mean  
- Detected outliers using IQR and visual inspection  
- Log-transformed skewed features (Boston dataset)  
- One-hot encoded categorical data (e.g., ocean proximity)  
- Split dataset into 80% training and 20% testing  

### 2. 🧠 Model Building
- **Statistical Models**  
  - Linear Regression (OLS & Gradient Descent)  
  - Ridge Regression  

- **Machine Learning Models**  
  - K-Nearest Neighbors  
  - Random Forest  
  - XGBoost  

- Applied `GridSearchCV` for hyperparameter tuning

### 3. 🧪 Evaluation
- Metrics:  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  

- Visualization:  
  - Q-Q and residual plots  
  - Scatter plots (predicted vs actual)  
  - Bar charts for metric comparison  

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo  
2. Create a new branch: `git checkout -b feature/YourFeature`  
3. Make your changes  
4. Commit: `git commit -m "Add YourFeature"`  
5. Push: `git push origin feature/YourFeature`  
6. Open a Pull Request

Please follow [PEP8](https://peps.python.org/pep-0008/) and document new features clearly.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
