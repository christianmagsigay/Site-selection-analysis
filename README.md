# 🍗 Jollibee Site Selection Using Machine Learning & Geospatial Analysis

## 📌 Overview
This project develops a data-driven site selection model to identify optimal locations for new Jollibee stores. By combining geospatial analysis, demographic data, and machine learning, the model evaluates candidate locations based on accessibility, competition, and population influence.

---

## 🎯 Objectives
- Identify high-potential locations for new Jollibee branches
- Analyze spatial relationships between existing stores and points of interest
- Use machine learning to rank candidate sites
- Provide interpretable insights to support business decisions

---

## 🧠 Methodology

### 1. Data Collection
- Administrative boundaries (Metro Manila / NCR)
- Existing Jollibee store locations
- Points of Interest (POIs):
  - Malls
  - Gas stations
  - Major roads / highways
- Population data

---

### 2. Feature Engineering
Key features include:
- Distance to nearest POIs
- Density of establishments within a radius
- Population influence per location
- Proximity to existing Jollibee stores

---

### 3. Spatial Analysis
- GeoDataFrames used to manage spatial datasets
- KDTree / nearest-neighbor methods for distance computation
- Radius-based counting for density estimation

---

### 4. Machine Learning Model
- Training and testing split applied
- Multiple models tested and refined
- Predictions used to score and rank candidate locations

---

### 5. Model Explainability
- SHAP (SHapley Additive exPlanations) used to interpret feature importance
- Helps identify key drivers of site suitability

---

### 6. Visualization
- Static maps using Matplotlib
- Interactive maps using Folium
- Final output: ranked candidate locations plotted geographically

---

## 📊 Results
- Ranked list of optimal locations for expansion
- Interactive map showing high-potential sites
- Insights into factors influencing successful store placement

---

## 🛠️ Tools & Technologies
- Python
- Pandas & NumPy
- GeoPandas
- Scikit-learn
- SHAP
- Matplotlib
- Folium

---


## 📌 Key Insights
- High population density strongly correlates with ideal locations
- Proximity to commercial centers (e.g., malls) improves site ranking
- Over-saturation near existing stores reduces suitability

---

## 🔮 Future Improvements
- Incorporate real-time traffic data
- Add rental cost / land price analysis
- Use more advanced models (e.g., XGBoost, spatial regression)
- Expand analysis beyond Metro Manila

---

## 👤 Author
Christian Jay P. Magsigay

---

## 📄 License
This project is for academic and research purposes only.
