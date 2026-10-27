# AI-Based House Price Prediction and Property Recommendation System

A Flask web application that estimates Bengaluru house prices from property details such as total area, BHK, bathrooms, balcony, area type, and location. The project includes data preparation and exploratory-analysis notebooks, trained model artifacts, and project documentation.

## Features
- Property-price prediction through a web form
- Location suggestions based on the trained feature columns
- Preprocessing with a saved scaler
- Trained neural-network model loaded at application startup
- Notebooks and project files for reviewing the workflow

## Technology
- Python, Flask, pandas
- TensorFlow/Keras
- scikit-learn preprocessing
- HTML and CSS
- Render deployment

## Run locally
Use Python 3.11 in a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

Open http://127.0.0.1:5000 in your browser.

## Deploy on Render
Create a new Web Service from this GitHub repository. The included `render.yaml` uses `pip install -r requirements.txt` as the build command and `gunicorn app:app` as the start command.

## Project structure
- `app.py`: Flask routes and prediction logic
- `templates/`: HTML templates
- `static/`: CSS styles
- `Models/`: trained model and preprocessing artifacts
- `Dataset/`: project datasets
- `Python_Files/`: analysis, feature engineering, and modeling notebooks
- `images/`: project screenshots and figures
- `PR/`, `Presentation/`: academic progress reports and presentations

## Note
This is an academic project. Predicted values are estimates and should not be treated as professional property valuations.
