# ☢️ Nuclear Contamination Prediction — Fukushima Dataset

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-GNN-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-enabled-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 📌 Overview

This project predicts **Cesium-137 (Cs-137) contamination levels** 
across geographic zones using advanced Machine Learning models 
trained on environmental data collected after the 
**2011 Fukushima Daiichi Nuclear Accident**, Japan.

The goal is to classify contamination risk zones and predict 
radioactive spread patterns to support environmental safety 
and disaster response planning.

---

## 🎯 Objectives

- Preprocess and clean real-world nuclear contamination data
- Engineer features from environmental and geographic variables
- Train and compare multiple ML models including deep learning
- Predict Cesium contamination levels and classify risk zones
- Visualise geographic risk maps for actionable insights

---

## 🧠 Models Used


|
 Model 
|
 Type 
|
 Notes 
|
|
---
|
---
|
---
|
|
 Graph Neural Network (GNN) 
|
 Deep Learning 
|
 Spatial relationships between zones 
|
|
 PyTorch Neural Network 
|
 Deep Learning 
|
 Custom architecture 
|
|
 XGBoost 
|
 Gradient Boosting 
|
 Best tabular performance 
|
|
 Random Forest 
|
 Ensemble 
|
 Baseline comparison 
|
|
 Linear Regression 
|
 Statistical 
|
 Baseline 
|

---

## 🗂 Project Structure

 #
 Nuclear_contamination_Predictions/
#
├── clean_impute.py          # Data cleaning and imputation //
#
├── clean_numeric.py         # Numeric preprocessing
#
├── encode_categorical.py    # Categorical encoding
#
├── drop_columns.py          # Feature selection
#
├── prepare_data.py          # Data pipeline
#
├── gnn_updated.py           # Graph Neural Network model
#
├── pytorch updated.py       # PyTorch deep learning model
#
├── random forest.py         # Random Forest model
#
├── RISK_CLASSIFICATION.py   # Risk zone classification
#
├── classify risk zone.py    # Zone mapping
#
├── risk map updated.py      # Geographic risk visualisation
#
├── app.py                   # Application entry point
#
├── requirements.txt         # Dependencies
#
└── README.md
---

## 📊 Dataset

- **Source:** Fukushima Nuclear Accident environmental monitoring data
- **Target variable:** Cesium-137 (Cs-137) activity levels
- **Features:** Geographic coordinates, soil type, 
  distance from plant, environmental measurements
- **Size:** ~370,000 samples (train + test split)

---

## ⚙️ Installation

```bash
git clone https://github.com/ujjwal-pathak-ml/Nuclear_contamination_Predictions.git
cd Nuclear_contamination_Predictions
pip install -r requirements.txt
```

---

## 🚀 Usage

```bash
# Run risk classification
python RISK_CLASSIFICATION.py

# Generate risk map
python "risk map updated.py"

# Run the application
python app.py
```

---

## 📈 Results

| Model | Performance |
|---|---|
| GNN | Best spatial prediction |
| XGBoost | Best tabular accuracy |
| PyTorch NN | Strong generalisation |
| Random Forest | Solid baseline |

*(Add your actual accuracy/F1 scores here)*

---

## 🗺 Risk Zone Visualisation

The project generates geographic risk maps classifying 
contamination zones into risk levels based on Cs-137 
activity concentration — supporting environmental 
safety decision making.

---

## 🛠 Tech Stack

- **Python** 3.8+
- **PyTorch** — Deep learning and GNN
- **XGBoost** — Gradient boosting
- **scikit-learn** — ML pipeline and evaluation
- **pandas / numpy** — Data processing
- **matplotlib** — Visualisation
- **Streamlit / Flask** — Application (app.py)

---

## 👤 Author

**Ujjwal Pathak**  
MSc Advanced Data Science (Merit) — Bangor University, 2025  
📍 London, UK  
🔗 [LinkedIn](https://www.linkedin.com/in/ujjwal-pathak-ml) | 
[GitHub](https://github.com/ujjwal-pathak-ml)

---

## 📄 License

This project is open source and available under the 
[MIT License](LICENSE).
