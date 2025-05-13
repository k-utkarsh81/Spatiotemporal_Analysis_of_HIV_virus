# Spatiotemporal Analysis of HIV Virus

## 🧠 Motivation

This project aims to bridge global health disparities by predicting life expectancy using machine learning and geospatial tools. It focuses on how socio-economic and environmental factors influence life expectancy, especially concerning HIV spread. The end goal is to support better public health policy-making using data-driven visual tools.

---

## 🧪 Type of Project

A hybrid **Development + Research** project analyzing life expectancy and the spatial spread of HIV using:
- Machine Learning (ML)
- Deep Learning (DL)
- Geospatial Mapping (GIS)

---

## 📚 Critical Literature Review

1. **COVID-19 in Germany**
   - County-level analysis using GAMs and Bayesian ML
   - AUC-ROC & RMSE used for model validation

2. **Tuberculosis in Shanghai**
   - ESDA, LISA, GIS tools for spatiotemporal pattern detection

3. **COVID-19 in Bangladesh**
   - Vulnerability maps correlating disease risk with socio-economic data

4. **Mobility-based Disease Modeling**
   - Developed indices (CFI, CTI) to forecast infectious spread using ML

---

## 🛠️ Technologies Used

**Languages & Libraries**
- Python
- Pandas, NumPy, Scikit-learn, TensorFlow/Keras
- Geopandas, Folium, Plotly, Shapely, Matplotlib, Seaborn

**Tools**
- Jupyter Notebook
- Leaflet

---

## 📈 Methodology

### ➤ Data Preprocessing
- Imputation of missing values
- Label Encoding for categorical data
- Feature Scaling using MinMaxScaler
- Data Splitting (80% train, 20% test)

### ➤ Model Development
- **ANN**
  - ReLU activation, Dropout layers
  - Loss: MSE | Optimizer: Adam | Metric: R²

- **LSTM**
  - Sequential model for time-series
  - Emphasis on temporal pattern recognition

### ➤ Exploratory Data Analysis
- Visualization using Matplotlib, Seaborn, Plotly
- Focus on adult mortality, alcohol use, socio-economic indicators

### ➤ Evaluation & Insights
- R² metric
- Plot: Actual vs Predicted
- Identified key predictors and their influence
- Compared ANN vs LSTM for temporal prediction accuracy


## 🔮 Future Scope

- Expand to advanced models and larger datasets
- Develop a public health tool for targeted interventions
- Enhance robustness and interpretability

---

## ✅ Conclusion

The project successfully integrates ML and DL techniques, especially ANN and LSTM, for predicting life expectancy with a focus on HIV. The results reveal key health and socio-economic determinants and demonstrate how geospatial data can be leveraged for smarter, data-driven healthcare policy decisions.
