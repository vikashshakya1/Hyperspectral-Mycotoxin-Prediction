# Hyperspectral Mycotoxin Prediction  

## 📌 Project Overview  
This project focuses on processing hyperspectral imaging data, performing dimensionality reduction, and training machine learning models to predict **mycotoxin levels (DON concentration)** in corn samples.  
## 🚀 **Motivation**  
Mycotoxins pose a serious threat to food safety and agriculture. Traditional methods for detecting mycotoxins are often slow and expensive. Hyperspectral data, which provides detailed spectral information, can improve accuracy and efficiency in detecting mycotoxins.  

This project aims to:  
✅ Develop a deep learning model capable of handling high-dimensional hyperspectral data.  
✅ Improve prediction accuracy through dimensionality reduction and feature engineering.  
✅ Explore advanced architectures like CNN and attention mechanisms to enhance performance.  


## 📂 Repository Structure  
```
📦 Hyperspectral-Mycotoxin-Prediction
│── 📂 data                # Dataset (if allowed) or link to download
│── 📂 notebooks           # Jupyter Notebooks for exploration & modeling
│── 📂 models              # Trained models and saved checkpoints
│── 📜 requirements.txt    # Required dependencies
│── 📜 README.md           # Project documentation
│── 📜 report.pdf          # Short project report
│── 📜 app.py              # Streamlit app (optional)
│── 📜 train.py            # Training script
│── 📜 inference.py        # Script for making predictions
```

## 🛠 Installation & Setup  
### 1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/Hyperspectral-Mycotoxin-Prediction.git
cd Hyperspectral-Mycotoxin-Prediction
```

### 2️⃣ Create a virtual environment (Optional but recommended)  
```bash
python -m venv env
source env/bin/activate  # On Mac/Linux
env\Scripts\activate     # On Windows
```

### 3️⃣ Install dependencies  
```bash
pip install -r requirements.txt
```

## 📊 Dataset  
The dataset contains spectral reflectance data of corn samples with multiple wavelength bands.  
- **Features**: Spectral reflectance values across various bands.  
- **Target Variable**: DON concentration (continuous value for regression).  

## 🔍 Tasks & Methodology  
### **1. Data Exploration & Preprocessing**  
✅ Load and inspect the dataset for missing values & outliers.  
✅ Normalize spectral reflectance data.  
✅ Visualize spectral bands (line plots, heatmaps).  

### **2. Dimensionality Reduction**  
✅ Apply **PCA** (Principal Component Analysis) to reduce dimensions.  
✅ Explore variance explained by principal components.  
✅ Visualize reduced data (2D/3D scatter plots).  

### **3. Model Training**  
✅ Implement **Random Forest, XGBoost, or a Neural Network**.  
✅ Split data into **80% training, 20% testing**.  
✅ Perform hyperparameter tuning (Grid Search / Random Search).  

### **4. Model Evaluation**  
✅ Evaluate using **MAE, RMSE, R² Score**.  
✅ Visualize results with **scatter plots of actual vs. predicted values**.  

## 🚀 How to Run  
Run the training script:  
```bash
python train.py
```

Run inference on new data:  
```bash
python inference.py --input sample_data.csv
```

(Optional) Run the Streamlit app (if implemented):  
```bash
streamlit run app.py
```

## 📑 Results & Insights  
📌 PCA reduced the feature dimensions while retaining most of the variance.  
📌 Model performance was evaluated using multiple regression metrics.  
📌 Possible improvements include **transformers, attention mechanisms, or ensemble learning**.  

## 🎯 Future Work  
✔ Implement transformers for spectral feature extraction.  
✔ Build a **Streamlit-based interactive app** for predictions.  
✔ Experiment with **GNNs, CNNs, and LSTMs** for hyperspectral data processing.  
