# 🏠 REALVALUE - House Price Prediction Platform

A full-stack machine learning application that predicts house prices using XGBoost.

## Features

- 🤖 **ML-Powered Predictions** - XGBoost model for accurate price estimates
- 📊 **Feature Importance** - Understand what drives property values
- 🎨 **Modern UI** - Beautiful, responsive frontend
- 🚀 **RESTful API** - Easy integration with other services

## Quick Start

### Run Locally

```bash
# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

Visit `http://localhost:5000` in your browser.

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/` | GET | Main application UI |
| `/api/v1/predict` | POST | Get house price prediction |
| `/api/v1/market/<neighborhood>` | GET | Get market statistics |
| `/api/v1/health` | GET | Health check |

## Tech Stack

- **Backend**: Python, Flask, XGBoost, scikit-learn
- **Frontend**: HTML, CSS, JavaScript
- **ML Model**: XGBoost Regressor

## Deploy on Render

1. Push to GitHub
2. Connect repo to [Render](https://render.com)
3. Deploy as a Web Service

## License

MIT License
