# Stockify - Stock Market Prediction Application

Stockify is a web application that combines a React frontend, Python Flask backend, and machine-learning models to provide stock-related features.

## Features

- Stock price prediction
- Stock comparison
- Portfolio management
- About page

## Technologies Used

### Frontend
- React.js
- JavaScript
- HTML
- CSS
- Tailwind CSS

### Backend
- Python
- Flask
- Flask-CORS
- Flask-SQLAlchemy
- Flask-JWT-Extended
- Flask-Bcrypt

### Machine Learning
- TensorFlow / Keras
- NumPy
- pandas
- scikit-learn

## Project Structure

```text
Stockify/
├── backend/
│   ├── app.py
│   ├── auth.py
│   ├── data.py
│   ├── model.py
│   ├── predict.py
│   ├── train.py
│   └── models/
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
├── .gitignore
└── README.md
```

## How to Run the Application

### Backend

```bash
cd backend
python app.py
```

Backend URL: `http://127.0.0.1:5000`

### Frontend

Open a separate terminal:

```bash
cd frontend
npm install
npm start
```

Frontend URL: `http://localhost:3000`

## Author

Mounika

GitHub: [Mounika0953](https://github.com/Mounika0953)

## Disclaimer

This project is for educational purposes. Stock predictions are estimates and are not financial advice.
