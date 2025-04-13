# 📊 Multi-Page Data Science Dashboard with Streamlit

A beautiful, modular, and interactive **multi-page dashboard** built with [Streamlit](https://streamlit.io/) for visualizing and understanding machine learning models, data patterns, and SHAP-based interpretability --- all in one place!

![Streamlit App Screenshot](https://user-images.githubusercontent.com/your-screenshot-link.png)

---

## 🚀 Features

- 📁 **Multi-Page Navigation**: Seamlessly organized using `streamlit-multipage`.

- 📈 **Data Upload and Summary**: Upload Excel or CSV files and view insightful summaries.

- 🧠 **Model Training**: Train models like **Random Forest** and **Decision Trees** with just a few clicks.

- 🌌 **SHAP Analysis**: Understand feature importance with powerful SHAP visualizations.

- 📊 **Interactive Visuals**: Powered by Plotly for dynamic data exploration.

- 📂 **Download Results**: Export predictions or SHAP values as Excel files.

---

## 📚 Project Structure

```bash

Multipage/

├── main.py                 # Launches the Streamlit app and handles navigation

├── pages/

│   ├── 1_📊_Data_Overview.py

│   ├── 2_🧠_Model_Training.py

│   └── 3_🌌_SHAP_Analysis.py

├── data/                   # Sample data files

├── assets/                 # Logos, images

├── requirements.txt

└── README.md

🧑‍💻 How to Run Locally

🔧 Prerequisites

Python 3.7+

Pip

📦 Installation

# Clone the repository

git clone https://github.com/yourusername/your-repo-name.git

cd your-repo-name

# Install dependencies

pip install -r requirements.txt

# Run the Streamlit app

streamlit run main.py

🌐 Deployment (on Streamlit Cloud)

You can deploy this project on Streamlit Cloud in just a few clicks:

Push your project to a public GitHub repository

Visit streamlit.io/cloud and log in

Click "New app"

Select your repo and set the entry point as main.py

Hit Deploy

Your live app will be ready in a minute! 🚀

🧪 Example Use-Cases

📁 Visualizing uploaded datasets

🧠 Quickly training and interpreting ML models

🧬 Explaining model decisions with SHAP

🛠️ Prototyping Data Science dashboards for clients

📸 Screenshots

Data Overview  Model Training  SHAP Analysis

📦 Dependencies

streamlit

pandas, numpy

scikit-learn

matplotlib, plotly

shap

openpyxl

All are listed in requirements.txt.

👨‍💻 Author

Your Name

📧 your.email@example.com

🔗 LinkedIn | GitHub

📄 License

This project is licensed under the MIT License.

⭐️ Support

If you find this useful, leave a ⭐️ on the GitHub repo and share it!