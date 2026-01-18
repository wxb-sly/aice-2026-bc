# 🏗️ AI in Civil Engineering (AICE) - Training Log

![Status](https://img.shields.io/badge/Status-Completed-success)
![Focus](https://img.shields.io/badge/Focus-Structural_Health_Monitoring-blue)
![Tech](https://img.shields.io/badge/Stack-Python_|_Scikit--Learn-yellow)

### 🚨 Mission Objective
To transition from traditional deterministic engineering to **Data-Driven Infrastructure Intelligence**. This repository documents a 15-day intensive training regimen focusing on three core competencies: Structural Health Monitoring (SHM), Geospatial Classification, and Material Property Prediction.

---
### 🛠️ Tech Stack
*   **Engine:** Python 3.xx
*   **Data Processing:** Pandas (Time-series manipulation)
*   **Visualization:** Matplotlib/Seaborn (Sensor data trends)
*   **Domain:** Predictive Maintenance (PedM)

---

## 💎 Project 1: Structural Health Monitoring (The Vänersborg Bridge)
*A module focusing on Time-Series Anomaly Detection.*

### 📉 The "Pulse" of the Structure
*Analysis of real-world sensor data to detect structural deviation.*

### ⚙️ Engineering Logic
1.  **Ingestion:** Parsed complex sensor log data (Temperature, Strain, Acceleration) from the **Vänersborg Railway Bridge**.
2.  **Cleaning:** Handled missing values and synchronized timestamps to align sensor readings with physical events.
3.  **Analysis:** Visualized the correlation between temperature fluctuations and structural strain to separate environmental noise from actual structural loading.
4.  **Anomaly Detection:** Identified specific timeframes where sensor readings deviated from the baseline, indicating potential stress events.

---

## 🛰️ Project 2: Automated Land Use Classification (LULC)
*Applying Unsupervised Machine Learning to Remote Sensing.*

### 🚨 Objective
To automate the classification of terrain features (Water, Vegetation, Urban) without manual surveying.

### ⚙️ Engineering Logic
1.  **Data Acquisition:** Utilized satellite imagery datasets (pixel-based feature data).
2.  **Clustering:** Deployed **K-Means Clustering** (Unsupervised Learning) to group pixels based on spectral signatures.
3.  **Segmentation:** Automatically segmented the map into distinct zones (Land Use Classes) based on cluster centroids.

---

## 🏗️ Project 3: Material Strength Prediction
*Optimizing Concrete Mix Designs using Regression.*

### 🚨 Objective
To predict the Compressive Strength of concrete based on ingredient proportions, reducing the need for destructive lab testing.

### ⚙️ Engineering Logic
1.  **Correlation Matrix:** Analyzed the relationship between inputs (Cement, Water, Superplasticizer, Age) and Target (Strength).
2.  **Modeling:** Trained a **Linear Regression** model to map mix ratios to final MPa output.
3.  **Validation:** Evaluated model accuracy using RMSE to ensure predictions fall within acceptable safety margins.

---

## 📂 Data Provenance
*   Sources mentioned in the notebooks.
*   If not, synthetically generated.

