Hyperspectral Mycotoxin Prediction

📌 Project Overview

This project focuses on processing hyperspectral imaging data of corn samples to predict mycotoxin (DON concentration) levels. The pipeline includes:

Data preprocessing (handling missing values, normalization)

Spectral band visualization

Dimensionality reduction using PCA or t-SNE

Machine learning model training for regression

Model evaluation and insights

📂 Repository Structure

📦 Hyperspectral-Mycotoxin-Prediction
├── 📂 data                 # Dataset (if applicable)
├── 📂 notebooks            # Jupyter Notebooks for EDA, modeling, and evaluation
├── 📂 src                  # Python scripts for modularized workflow
├── 📜 report.pdf           # Short report summarizing findings
├── 📜 requirements.txt     # Required dependencies
├── 📜 README.md            # Project documentation (this file)

📊 Dataset Description

Features: Spectral reflectance values across multiple wavelength bands.

Rows: Individual corn samples.

Target Variable: DON concentration (continuous, for regression).

🚀 Installation & Usage

1️⃣ Clone the Repository

git clone https://github.com/yourusername/Hyperspectral-Mycotoxin-Prediction.git
cd Hyperspectral-Mycotoxin-Prediction

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook

jupyter notebook

🔬 Methodology

1. Data Preprocessing

Checked for missing values and outliers.

Applied normalization to spectral reflectance data.

Visualized spectral bands using line plots and heatmaps.

2. Dimensionality Reduction

Implemented PCA (Principal Component Analysis) to reduce feature dimensions.

Reported variance explained by top components.

Used t-SNE for visualization of clustering patterns.

3. Model Training

Chose a regression model (Random Forest, XGBoost, or Neural Network).

Split dataset into 80% training and 20% testing.

Optimized hyperparameters using Grid Search or Random Search.

4. Model Evaluation

Used Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.

Visualized performance using scatter plots.

📈 Results & Insights

Highlighted key findings from dimensionality reduction.

Compared model performance and identified strengths/limitations.

Suggested improvements for future work.

🤝 Contributing

Feel free to contribute by submitting issues or pull requests!

⚖️ License

This project is licensed under the MIT License.
