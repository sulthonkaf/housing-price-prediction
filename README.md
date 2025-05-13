
# 🧠 Housing Price Prediction with Deep Learning and Classical Models

This repository contains a complete notebook for predicting housing prices using both deep learning (MLP) and classical regression models. It demonstrates a structured approach for preprocessing, model training, evaluation, and comparison.

---

## 📁 Dataset
The dataset used is `housing.csv`, which includes features such as:
- `longitude`, `latitude`, `housing_median_age`, `total_rooms`, etc.
- Target: `median_house_value` (numerical)

---

## 📌 Project Structure

### ✅ Preprocessing
- Handle missing values with median imputation
- One-hot encoding of `ocean_proximity`
- Standard scaling of numerical features

### ✅ Models Trained
1. **Linear Regression**
2. **Random Forest Regressor**
3. **XGBoost Regressor**
4. **Multi-Layer Perceptron (MLP)** using TensorFlow/Keras

### ✅ Evaluation Metrics
- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)
- **R² Score**

### ✅ Visualization
- Performance comparison bar chart (`model_comparison_chart.png`)

---

## 📊 Results Output
- `model_comparison_results.csv`: Table of metrics
- `model_comparison_chart.png`: Visualization of model performance

---

## 🧠 Key Takeaways
- MLP may perform well if tuned correctly, but classical models like XGBoost and Random Forest provide strong baselines.
- Combining both deep learning and classical models provides better insight into performance trade-offs.

---

## 🛠️ Requirements
- `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`, `tensorflow`

Install with:
```bash
pip install -r requirements.txt
```

---

## 📂 File
- `housing_model_comparison.ipynb` — Main notebook
