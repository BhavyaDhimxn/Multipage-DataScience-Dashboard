# 📊 Multi-Page Data Science Dashboard with Streamlit

![Dashboard Screenshot](https://user-images.githubusercontent.com/your-screenshot-link.png)

A comprehensive, modular dashboard for machine learning visualization, model interpretation, and data exploration built with Streamlit. Features SHAP analysis, interactive visualizations, and multi-page navigation.

---

## 🚀 Key Features

### 📂 Data Management
- Upload Excel/CSV files with automatic validation
- Interactive data preview with sorting/filtering
- Statistical summary with distribution visualizations

### 🤖 Machine Learning
- One-click model training (Random Forest, Decision Trees)
- Hyperparameter tuning interface
- Performance metrics visualization (ROC, Confusion Matrix)

### 🔍 Model Interpretation
- Interactive SHAP force plots
- Feature importance rankings
- Decision path visualization

### 🎨 Visualization
- Dynamic Plotly charts with hover tooltips
- Exportable high-resolution figures
- Theme customization (light/dark mode)

---

## 🏗️ Project Architecture

```bash

Multipage-Dashboard/
├── main.py                 # App entry point & navigation
├── pages/                  # Modular page components
│   ├── 1_📊_Data_Overview.py
│   ├── 2_🤖_Model_Training.py
│   └── 3_🔍_SHAP_Analysis.py
├── utils/                  # Shared utilities
│   ├── data_loader.py
│   └── visualization.py
├── data/                   # Sample datasets
├── assets/                 # Static resources
├── tests/                  # Unit tests
├── requirements.txt
└── README.md

```

---

## 🛠️ Installation & Setup

### Prerequisites

-   Python 3.8+

-   Pipenv (recommended) or pip

### Quick Start

```

# Clone repository
git clone https://github.com/yourusername/multipage-dashboard.git
cd multipage-dashboard

# Install dependencies
pip install -r requirements.txt  # or pipenv install

# Launch application
streamlit run main.py

```
---

## Cloud Deployment

- Push to GitHub repository
- Sign in to Streamlit Cloud
- Click "New App" → Select repo → Set main.py as entry point
- Deploy! (Typically completes in 1-2 minutes)

## 📚 Documentation

### Usage Guide

| 📄 Page           | 🔑 Key Functions                           |
|------------------|-------------------------------------------|
| **📊 Data Overview** | • 📤 File upload <br> • 📊 Data profiling <br> • ❓ Missing value analysis |
| **🤖 Model Training** | • 🧠 Algorithm selection <br> • 🎚️ Parameter tuning <br> • 📈 Model evaluation |
| **🔍 SHAP Analysis** | • 🌍 Global interpretation <br> • 🔎 Local interpretation <br> • 📉 Dependence plots |
