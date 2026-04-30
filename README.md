📌 Parkinson's Disease Prediction System
🚀 Overview

This project is a Machine Learning-based web application that predicts whether a person has Parkinson’s Disease based on clinical voice measurements.

It uses a Support Vector Machine (SVM) model and provides a user-friendly web interface where users can input parameters and get predictions instantly.

🧠 Features
Predicts Parkinson’s Disease using clinical data
Machine Learning model (SVM)
Data preprocessing with StandardScaler
Simple and interactive web interface
Real-time prediction results
🛠️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
Flask (Backend)
HTML, CSS (Frontend)
📂 Project Structure
project/
│
├── static/
│   ├── style.css
│   └── images/
│       └── 1.png
│
├── templates/
│   └── index.html
│
├── parkinsons.csv
├── model.pkl
├── app.py
└── README.md
⚙️ How It Works
User enters medical voice parameters in the form.
Data is sent to the Flask backend.
Input is standardized using the trained scaler.
The SVM model predicts the result.
Output is displayed to the user.
▶️ How to Run the Project
Clone the repository
git clone https://github.com/your-username/parkinsons-predictor.git
cd parkinsons-predictor
Install dependencies
pip install -r requirements.txt
Run the application
python app.py
Open in browser:
http://127.0.0.1:5000/
📊 Model Details
Algorithm: Support Vector Machine (SVM)
Kernel: Linear
Accuracy:
Training Accuracy: ~95%+
Testing Accuracy: ~90%+
📌 Input Parameters

The model uses 22+ biomedical voice features like:

MDVP:Fo(Hz)
MDVP:Fhi(Hz)
MDVP:Flo(Hz)
Jitter, Shimmer
NHR, HNR
RPDE, DFA
PPE and more
