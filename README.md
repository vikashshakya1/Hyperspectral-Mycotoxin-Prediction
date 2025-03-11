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
📦 Hyperspectral-Mycotoxin-Prediction  
├── 📁 **Dataset**                   # Raw hyperspectral data (Excel format)  
├── 📁 **Model_Implementation**      # Jupyter Notebook with CNN model  
├── 📄 **Project Details.docx**      # Summary of project goals and findings  
├── 📄 **Spectral Data Analysis Report.docx** # Full model report with evaluation  
├── 📄 **README.md**                 # Project overview and instructions  
├── 📄 **requirements.txt**          # List of dependencies  
├── 📄 **.gitignore**                # Files to ignore in Git  


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
### 1. Data Exploration & Preprocessing  
✅ Loaded and inspected the dataset for missing values & outliers.  
✅ Normalized spectral reflectance data.  
✅ Visualized spectral bands (line plots, heatmaps).  

---

### 2. Dimensionality Reduction  
✅ Applied **PCA** (Principal Component Analysis) to reduce dimensions.  
✅ Explored variance explained by principal components.  
✅ Visualized reduced data (2D/3D scatter plots).  

---

### 3. Model Training  
✅ Implemented **CNN model** for prediction.  
✅ Split data into **80% training, 20% testing**.  
✅ Performed hyperparameter tuning (**Grid Search / Random Search**).  

---

### 4. Model Evaluation  
✅ Evaluated using **MAE, RMSE, R² Score**.  
✅ Visualized results with **scatter plots of actual vs. predicted values**.  
✅ **Performance:**  
- 📌 **Mean Absolute Error (MAE):** 4542.53  
- 📌 **Root Mean Squared Error (RMSE):** 14203.61  
- 📌 **R² Score:** 0.7266  

---

## 📑 Results & Insights  
📌 **PCA** reduced the feature dimensions while retaining most of the variance.  
📌 Model performance was evaluated using multiple regression metrics.  
📌 Implementing **CNN** led to improved accuracy and lower error rates.  


## 🎯 Future Work  
✔ Implement transformers for spectral feature extraction.  
✔ Build a **Streamlit-based interactive app** for predictions.  
✔ Experiment with **GNNs, CNNs, and LSTMs** for hyperspectral data processing.  
