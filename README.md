# 🌾 Crop Yield Prediction using Machine Learning

A self-driven machine learning project to predict agricultural crop yield based on real-world historical data of Indian states from **1997 to 2019**. The project uses robust data preprocessing, pipeline automation, and regression modeling to deliver high-accuracy predictions.

---

## 📌 Objective

To build an efficient regression model capable of predicting **crop yield** (in kg/hectare) using historical agriculture-related parameters such as crop type, state, area, and production data.

---

## 🗃️ Dataset

- 📍 **Source**: [Kaggle - Agricultural Crop Yield of Indian States (1997–2019)]
- 🧾 **Columns**: State, District, Crop, Season, Area, Production
- 📅 **Period**: 1997 – 2019
- 🔢 **Target Variable**: Yield (calculated as `Production / Area`)

---

## 🔍 EDA Highlights

- Visualized crop trends over time for major states
- Handled missing values and inconsistent formats
- Encoded categorical variables using Label Encoding
- Created a derived `Yield` column as the prediction target

---

## 🧠 Modeling Approach

- Created preprocessing + training pipeline using `Pipeline` from `sklearn`
- Used:
  - **Random Forest Regressor** – Best performer
  - Compared with **Linear Regression** (baseline)
- Performed hyperparameter tuning using GridSearchCV

---

## 📊 Model Performance

| Metric   | Random Forest |
|----------|----------------|
| R² Score | **0.9345**     |
| MAE      | ~18.3 kg/ha    |
| RMSE     | ~25.1 kg/ha    |

🎯 **93.45% R² score** demonstrates strong prediction capability across multiple states and crop types.

---

## 🛠️ Tools & Libraries

- **Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Jupyter Notebook**: For all analysis and model building
- **Pipeline**: For clean preprocessing and reproducibility

---


