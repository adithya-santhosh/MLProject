# Student Performance Prediction using Machine Learning

## 📌 About
This project predicts student academic performance based on various factors such as demographics, parental education, and study habits. It leverages machine learning techniques for accurate predictions and provides an easy-to-use web interface for real-time predictions.

---

## ✅ Features
- Exploratory Data Analysis (EDA) with visual insights
- Data Preprocessing & Feature Engineering
- Machine Learning Model Training (CatBoost, etc.)
- Model persistence using pickle
- Web application for predictions
- Deployment ready (AWS Elastic Beanstalk configuration)

---

## 🛠 Tech Stack
- **Python** (Flask)
- **Pandas, NumPy**
- **Scikit-learn, CatBoost**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**
- **AWS Elastic Beanstalk**

---

## 📂 Project Structure
MLProject-main/

├── application.py # Main Flask app

├── requirements.txt # Dependencies

├── setup.py # Packaging setup

├── artifacts/ # Trained model, datasets

├── notebook/ # EDA & Model Training Notebooks

├── .ebextensions/ # AWS deployment config


---

## ⚙️ Installation
1. Clone this repository:
   ```bash
   git clone <your-repo-link>
   cd MLProject-main

2.Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate    # For Linux/Mac
venv\Scripts\activate       # For Windows

3.Install dependencies:
pip install -r requirements.txt

▶️ Usage
1. Run the Flask app:
   python application.py
2.Open your browser and navigate to:
  http://127.0.0.1:5000/
3. Enter student details and get performance predictions.


📊 Dataset
The dataset contains demographic and academic information about students.
Example features: gender, parental education, lunch type, test preparation course, and scores.
