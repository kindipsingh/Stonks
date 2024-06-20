# Project: Stock Price Prediction Using LSTM

## Overview
This project utilizes Long Short-Term Memory (LSTM) neural networks to predict monthly stock prices. It includes a comprehensive stock information website with real-time data, portfolio management, and a simulated investment feature for risk-free practice.

## Technologies Used
- **Backend**: Python, Flask, TensorFlow/Keras
- **Frontend**: JavaScript, EJS, Express.js
- **Database**: MongoDB
- **Other Tools**: yfinance, pandas, scikit-learn, numpy, StandardScaler

## Features
- **LSTM Model**: Developed a neural network model to predict monthly stock prices.
- **Stock Information Website**: Designed and launched a website with real-time stock data.
- **Simulated Investment**: Implemented a feature for users to simulate investments using virtual currency.
- **Technologies**: Utilized Python for backend logic, TensorFlow/Keras for machine learning, and JavaScript frameworks for frontend development.

## Directory Structure

```plaintext
Stonks/
├── index.js
├── package-lock.json
├── package.json
├── public/
├── src/
│   ├── importflaskk.py
│   └── mongodb.js
└── templates/
```

## Installation Guide

### Prerequisites
- Python 3.7+
- Node.js
- MongoDB

### Step-by-Step Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
2. **Install Python Dependencies:**
   ```sh
   pip install -r requirements.txt
3. **Install Node.js Dependencies:**
   ```sh
   cd frontend
   npm install
4. **Set Up MongoDB:**
   Update the MongoDB connection string in mongodb.js:
   ```javascript
   const connectionstring = "your_mongo_db_connection_string";

## Usage

### Running the Backend (Flask) and Frontend (Express.js)

#### Backend (Flask)
Start the Flask server:
```sh
python app.py
```

#### Frontend
Start the Node.js server:
```sh
node index.js
```

  

