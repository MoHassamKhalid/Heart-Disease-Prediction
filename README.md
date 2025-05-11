
# Heart Disease Prediction Web App

This is a Flask-based web application that predicts the likelihood of heart disease in a user based on their health metrics. The prediction is powered by a machine learning model trained on the [UCI Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease).

## 🧠 Features

- Predict heart disease risk using machine learning
- Interactive web interface built with HTML, CSS, and JavaScript
- Visual assets (images and GIFs) to enhance user engagement
- Trained model (`Heart_Model.pkl`) using Scikit-learn
- Can be deployed to platforms like Heroku

## 📁 Project Structure

```
Heart_Disease_Prediction_Flask_ML-main/
│
├── app.py                         # Main Flask application
├── Heart_Model.pkl                # Trained ML model
├── Heart_Model_Full.ipynb         # Jupyter notebook for training the model
├── heart.csv                      # Dataset used for training
├── requirements.txt               # Python dependencies
├── Procfile                       # For Heroku deployment
│
├── templates/
│   └── index.html                 # HTML template for the web interface
│
├── static/
│   ├── css/style.css              # Custom styles
│   ├── JS/type.js                 # Optional JavaScript for UI effects
│   └── picture/                   # Images and GIFs used in the UI
```

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- pip (Python package installer)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/Heart_Disease_Prediction_Flask_ML.git
cd Heart_Disease_Prediction_Flask_ML
```

2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python app.py
```

4. Open your browser and go to `http://127.0.0.1:5000/`.

## 🧪 Model Training

You can inspect and retrain the model using `Heart_Model_Full.ipynb`. The dataset used is `heart.csv`, which contains features like age, sex, chest pain type, resting blood pressure, cholesterol, etc.



## 📜 License

This project is open-source and available under the MIT License.


