<h1 align="center">🔍 Machine Learning for House Price Prediction: A Comparative Study</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python" />
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green" alt="License" /></a>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" alt="Status" />
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-red" alt="Love" />
</p>

---

## 📖 Project Summary

This project delivers a rigorous, data-driven comparison of statistical and machine learning models for predicting house prices. Leveraging the California and Boston housing datasets, the analysis moves beyond simple prediction to investigate which models offer the best performance, generalizability, and interpretability.

The core of this work is an end-to-end machine learning pipeline that includes data cleaning, advanced feature engineering, and robust model evaluation. The project's findings, supported by a full academic dissertation, demonstrate that **XGBoost, optimized with GridSearchCV, is the most effective model**, achieving a **0.84 R² score** on the California dataset.

---

## ✨ Key Features & Technical Highlights

- **Comprehensive Benchmarking**: Implemented and evaluated five distinct models: `Linear Regression`, `Ridge`, `K-Nearest Neighbors`, `Random Forest`, and `XGBoost`.
- **End-to-End Pipeline**: Built a complete and reproducible workflow, from initial data exploration and preprocessing to model training, hyperparameter tuning, and final evaluation.
- **Advanced Preprocessing**: Executed key data cleaning tasks including missing value imputation, outlier detection, one-hot encoding for categorical variables, and log transformation to handle skewed data.
- **Rigorous Optimization**: Utilized `GridSearchCV` to systematically tune `Random Forest` and `XGBoost` models, significantly boosting their predictive accuracy.
- **In-Depth Analysis**: Created compelling visualizations for EDA and results interpretation, including feature correlation heatmaps, Q-Q plots for assumption checking, residual analysis, and model performance comparison charts.

---

## 🏆 Results & Key Findings

After training and tuning all models on the California Housing dataset, the results clearly identified a top performer:

* **Best Performing Model**: The **XGBoost Regressor** delivered the highest accuracy.
* **Performance Metrics**:
    * **R² Score**: **0.838** (meaning the model explains ~84% of the variance in house prices).
    * **Root Mean Squared Error (RMSE)**: **0.459**
* **Conclusion**: The findings confirm that modern ensemble methods like XGBoost provide a significant performance advantage over traditional linear models for complex, high-dimensional datasets.

---

## 🧰 Tech Stack

| Tool              | Role                    |
| ----------------- | ----------------------- |
| 🐍 Python 3.8+    | Programming Language    |
| 📦 pandas, NumPy  | Data Manipulation       |
| 🎯 scikit-learn  | ML & Statistical Models |
| ⚡ XGBoost         | Gradient Boosting       |
| 📈 matplotlib, seaborn | Data Visualization      |
| 📓 Jupyter Notebook | Interactive Analysis    |

---

## 🚀 How to Run This Project

To replicate the analysis on your local machine, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required libraries:**
    ```bash
    pip install pandas numpy scikit-learn xgboost matplotlib seaborn jupyter
    ```

4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Then, open the `.ipynb` file and execute the cells sequentially.

---

## 🔬 Methodology

The project was executed in three main phases:

### 1️⃣ Data Preprocessing
* **Cleaning**: Imputed missing bedroom values using the mean and detected outliers using the Interquartile Range (IQR) method and visual inspection.
* **Transformation**: Applied log transformation to skewed features (primarily in the Boston dataset) and used one-hot encoding for the `ocean_proximity` categorical feature.
* **Splitting**: Partitioned the dataset into an `80% training set` and a `20% testing set` to ensure unbiased evaluation.

### 2️⃣ Model Building & Tuning
* **Baselines**: Established performance baselines using **Linear** and **Ridge Regression**.
* **ML Models**: Trained **K-Nearest Neighbors**, **Random Forest**, and **XGBoost** models.
* **Optimization**: Applied `GridSearchCV` with cross-validation to find the optimal hyperparameters for the ensemble models, maximizing their predictive power.

### 3️⃣ Evaluation
* **Quantitative Metrics**: Measured model performance using **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, and the **R² Score**.
* **Qualitative Analysis**: Used **Q-Q plots**, **residual plots**, and **predicted vs. actual value plots** to visually assess model fit and diagnose issues like heteroscedasticity.

---

## 💡 Future Work

* **Advanced Feature Engineering**: Create interaction terms and polynomial features to capture more complex relationships in the data.
* **Model Deployment**: Package the final XGBoost model into a REST API using Flask or FastAPI to serve real-time predictions.
* **Explore Deep Learning**: Investigate the performance of neural network architectures for this regression task.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/your-repository-name/issues).

1.  Fork the repository
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

<p align="center">
  <b>📊 Built with data, models, and a passion for insights 📊</b>
</p>
