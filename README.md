# Greedy-RF-SoilMapper
# 🌱 Soil Fertility Prediction Using Ensemble Random Forest  
### Greedy Feature Selection + Batch Training + Confidence Scoring

---

## 📌 Project Overview

This project implements a **high-performance machine learning pipeline** to predict soil fertility levels using an **Ensemble Random Forest classifier** enhanced with:

- Advanced Feature Engineering
- Greedy Feature Selection
- Batch-wise Training & Testing
- Multi-class ROC Analysis
- Confidence Score (0–1 scale)
- Professional Visualizations
- Model Export using Pickle
- PDF Report Generation

The model predicts soil fertility into four categories:

- Low  
- Moderate  
- High  
- Very High  

Additionally, a **fertility confidence score (0–1)** is generated using model probability outputs.

---

## 📂 Dataset Used

**Dataset Name:**  
`Sakri_Soil_Fertility_Version_2.csv`

**Description:**  
The dataset contains soil samples collected from the Sakri region. It includes chemical and physical soil parameters used to determine fertility levels.

### Key Features:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- pH
- Electrical Conductivity (EC)
- Organic Carbon
- Micronutrients
- Other soil health indicators

**Target Variable:**  
Soil Fertility Level

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing

- Missing value handling
- Label encoding for categorical features
- Feature scaling using `StandardScaler`
- Train-test split
- Class balancing (if required)

---

### 2️⃣ Feature Engineering

- Random Forest feature importance extraction
- Greedy forward feature selection
- Removal of low-importance features
- Probability-based fertility confidence scoring

---

### 3️⃣ Model Architecture

**Primary Model:**  
Ensemble Random Forest Classifier  

**Why Random Forest?**
- Handles non-linearity
- Robust to noise
- Reduces overfitting
- Provides feature importance

---

### 4️⃣ Batch-wise Training

Training is performed in batches to simulate scalable training pipelines:

- Data divided into mini-batches
- Incremental evaluation
- Performance tracking

---

### 5️⃣ Confidence Score (0–1 Scale)

Instead of only categorical output, the model provides:

This gives a continuous value between:

- 0 → Low confidence
- 1 → High confidence

---
## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---
## 🎯 Key Contributions

✔ Ensemble Random Forest with greedy feature selection  
✔ Fertility scoring on continuous 0–1 scale  
✔ Batch-wise training pipeline  
✔ Multi-class ROC evaluation  
✔ Professional visualization suite  
✔ Exportable trained model  
✔ Automated PDF reporting 

---
## 📜 License

This project is for academic and research purposes.
