# Customer Service Analysis System

An end-to-end machine learning project that analyzes customer service data to:
- Predict CSAT (Customer Satisfaction) scores
- Perform sentiment analysis on customer reviews
- Display insights through visualizations and a web interface

This system includes:
- A Jupyter Notebook (`.ipynb`) for data preprocessing, training, and evaluation
- A Flask backend to serve predictions via REST API
- A React frontend to display insights and collect user input

---

## 🔍 Features

- 🧹 **Data Preprocessing:** Cleans and processes the raw dataset (null handling, text preprocessing, encoding).
- 🤖 **Model Training & Evaluation:** Trains a machine learning model to predict CSAT scores and analyze sentiment.
- 📊 **Confusion Matrix & Metrics:** Visualizes performance using confusion matrix, accuracy, precision, recall, and F1 score.
- 💬 **Sentiment Analysis:** Classifies reviews as Positive, Negative, or Neutral.
- 🧠 **CSAT Prediction:** Predicts customer satisfaction score from review text.
- 🌐 **Web Interface:** Interactive React frontend that sends review input to Flask backend and displays predictions and charts.

---

## 🛠️ Tech Stack

| Layer          | Technology       |
|----------------|------------------|
| Machine Learning | Python, scikit-learn, pandas, matplotlib, seaborn |
| Backend        | Flask, Flask-CORS |
| Frontend       | React, Axios, Tailwind CSS |
| Deployment     | (Optional) Render / Vercel / Heroku / Netlify |

---

## 📁 Project Structure
<pre> customer-service-analysis/ ├── analysis_model/ │ ├── analysis.ipynb # Jupyter notebook for preprocessing, training, evaluation │ └── model.pkl # Saved ML model │ ├── backend/ │ ├── app.py # Flask backend for predictions │ └── requirements.txt # Backend dependencies │ ├── frontend/ │ ├── src/ │ │ ├── App.jsx # Main React component │ │ ├── api.js # Axios API calls │ │ └── ... # Other React components │ └── package.json # Frontend dependencies │ └── README.md </pre>

