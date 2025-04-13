# 📊 Multi-Page Data Science Dashboard with Streamlit

![Dashboard Screenshot](https://user-images.githubusercontent.com//Users/bhavyadhiman/Desktop/Screenshot 2025-04-13 at 6.42.37 PM.png)
![Dashboard Screenshot](https://user-images.githubusercontent.com//Users/bhavyadhiman/Desktop/Screenshot 2025-04-13 at 6.42.49 PM.png)
![Dashboard Screenshot](https://user-images.githubusercontent.com//Users/bhavyadhiman/Desktop/Screenshot 2025-04-13 at 6.43.05 PM.png)
![Dashboard Screenshot](https://user-images.githubusercontent.com//Users/bhavyadhiman/Desktop/Screenshot 2025-04-13 at 6.43.18 PM.png)

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

---

## 📦 Dependencies

| 🗂️ Category      | 📦 Packages                           | ⚙️ Version       |
|-----------------|---------------------------------------|-----------------|
| **⚙️ Core**      | `streamlit`<br>`pandas`               | ≥1.12<br>≥1.4   |
| **🧠 ML**        | `scikit-learn`<br>`xgboost`           | ≥1.0<br>≥1.6    |
| **📊 Viz**       | `plotly`<br>`matplotlib`              | ≥5.8<br>≥3.5    |
| **🔍 Interpretation** | `shap`<br>`lime`                  | ≥0.41<br>≥0.2   |

📝 *Complete list in [requirements.txt](requirements.txt)*

---

## ✉️ Contact

**Your Name**  
📧 [bhavyadhiman2428@gmail.com](mailto:bhavyadhiman2428@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/bhavyadhiman24/)  
🐙 [GitHub Profile](https://github.com/BhavyaDhimxn)  

---

## 🎯 Roadmap

- [ ] **AutoML Integration**  
  Add support for automated machine learning pipelines
- [ ] **Time-Series Models**  
  Implement ARIMA, Prophet, and LSTM support
- [ ] **User Authentication**  
  Secure login system with role-based access
- [ ] **Docker Deployment**  
  Containerized deployment solution
- [ ] **Enhanced Monitoring**  
  Model performance tracking dashboard

[![Star on GitHub](https://img.shields.io/github/stars/BhavyaDhimxn/repo.svg?style=social&label=Star)](https://github.com/BhavyaDhimxn/Multipage-DataScience-Dashboard)  
⭐ *Support this project by starring the repository!*