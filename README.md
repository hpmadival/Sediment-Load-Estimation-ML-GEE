# Sediment Load Estimation using Python, Machine Learning and Google Earth Engine

## 📌 Project Overview
This project presents a simple sediment load estimation model developed using satellite-derived hydrological and terrain variables. Google Earth Engine (GEE) is used to extract rainfall, land use, slope, and runoff data, which are then used in a Random Forest machine learning model implemented in Python on Google Colab.

The project is intended for learning, academic, and research purposes in hydrology and water resources engineering.

---

## 🎯 Objectives
- To estimate sediment load using satellite-based inputs
- To integrate hydrology and erosion concepts with machine learning
- To develop a reproducible workflow using Google Earth Engine and Python
- To validate sediment predictions using sample-based analysis

---

## 🛠 Tools & Technologies
- Google Earth Engine (GEE)
- Python (Google Colab)
- Machine Learning (Random Forest Regressor)
- Libraries: geemap, earthengine-api, pandas, numpy, scikit-learn, matplotlib

---

## 📊 Data Used
- Rainfall: CHIRPS Daily Rainfall Dataset
- Elevation & Slope: SRTM DEM
- Land Use/Land Cover: ESA WorldCover
- Runoff: Conceptually derived from rainfall

---

## ⚙ Methodology
1. Selection of a study area using a buffer-based watershed
2. Extraction of rainfall, slope, land use, and elevation data from GEE
3. Estimation of runoff using a simple conceptual relation
4. Preparation of a machine learning-ready dataset
5. Development of a Random Forest regression model
6. Model validation using R² score, MAE, and sample comparison

---

## 📈 Model Validation
- Train-test split (80% training, 20% testing)
- Performance metrics: R² score and Mean Absolute Error (MAE)
- Visual validation using Actual vs Predicted scatter plot

---

## ⚠ Limitations
- Sediment load values are assumed for demonstration
- No observed sediment concentration or discharge data used
- Soil properties are not included
- Channel routing effects are ignored

---

## 🔮 Future Improvements
- Integration of MUSLE-based sediment yield estimation
- Inclusion of soil erodibility factors
- Time-series sediment modeling
- Validation using observed sediment data
- Sub-basin level sediment analysis

---

## 👤 Author
Harshit Madival  
Postgraduate Student – Water Resources Engineering and Management

---

## 📜 License
This project is developed for academic and educational purposes.
