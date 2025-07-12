<h1 align="center">🔍 ML-Stat-House-Price-Predictor</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python" />
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License" />
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-red" alt="Love" />
</p>

---

## 📌 Table of Contents
- [Why This Project Matters](#why-this-project-matters)
- [Highlights](#highlights)
- [Data Overview](#data-overview)
- [Key Achievements](#key-achievements)
- [Tech Stack](#tech-stack)
- [Methodology](#methodology)
- [Contributing](#contributing)
- [License](#license)

---

## 🧠 Why This Project Matters
Accurate house price prediction guides investment strategy, city planning, and public policy.  
This project explores how traditional statistical approaches perform compared to modern machine learning techniques—uncovering which model delivers higher accuracy and better generalizability across diverse datasets.

---

## ✨ Highlights
- 📈 Achieved **90%+ R²** on the Boston dataset with tuned **XGBoost**, reducing RMSE by **40%** compared to linear baselines.  
- 🧪 Built a complete pipeline: **data cleaning → feature engineering → model training → evaluation → visualization**.  
- 🛠️ Benchmarked five models: `Linear`, `Ridge`, `KNN`, `Random Forest`, and `XGBoost`—with and without hyperparameter tuning.

---

## 🗃️ Data Overview
- **California Housing:** `20,640` rows · `10` features  
- **Boston Housing:** `506` rows · `13` features  
- 🔍 Features include geographic coordinates, median income, total rooms, proximity to ocean, etc.

---

## 🏆 Key Achievements
- 📓 Organized reusable Python scripts & Jupyter notebooks for **reproducibility**.  
- 🧹 Performed missing-value imputation, outlier detection, one-hot encoding, and log transformation.  
- ⚙️ Tuned `Random Forest` & `XGBoost` using `GridSearchCV` for optimal performance.  
- 📊 Created compelling visualizations: heatmaps, Q-Q plots, residual analysis, and model comparison charts.

---

## 🧰 Tech Stack

| Tool         | Role                    |
|--------------|-------------------------|
| 🐍 Python 3.8+ | Programming Language   |
| 📦 pandas, NumPy | Data Manipulation     |
| 🎯 scikit-learn | ML & Statistical Models |
| ⚡ XGBoost      | Gradient Boosting      |
| 📈 matplotlib, seaborn | Visualization   |
| 📓 Jupyter Notebook | Interactive Analysis |

---

## 🔬 Methodology

### 1️⃣ 📊 Data Preprocessing
- Imputed missing bedroom values with mean  
- Detected outliers using IQR & visual inspection  
- Log-transformed skewed features (Boston dataset)  
- One-hot encoded categorical data (e.g., ocean proximity)  
- Split dataset into `80% training / 20% testing`

### 2️⃣ 🧠 Model Building
- **Statistical Models:**  
  - Linear Regression (OLS & Gradient Descent)  
  - Ridge Regression  
- **Machine Learning Models:**  
  - K-Nearest Neighbors  
  - Random Forest  
  - XGBoost  
- Applied `GridSearchCV` for hyperparameter tuning

### 3️⃣ 🧪 Evaluation
- **Metrics:**  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  
- **Visualization:**  
  - Q-Q & residual plots  
  - Predicted vs actual scatter plots  
  - Bar charts for model comparison

---

## 🤝 Contributing

Contributions are welcome!  

🚀 To get started:
1. Fork the repo  
2. Create a new branch: `git checkout -b feature/YourFeature`  
3. Make your changes  
4. Commit: `git commit -m "Add YourFeature"`  
5. Push: `git push origin feature/YourFeature`  
6. Open a Pull Request

Please follow [PEP8](https://peps.python.org/pep-0008/) and document new features clearly.

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <b>📊 Built with data, models & a passion for insights 📊</b>
</p>
