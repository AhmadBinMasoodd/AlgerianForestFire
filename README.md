# Algerian Forest Fire Prediction

This project is a web application for predicting the Fire Weather Index (FWI) in Algerian forests using machine learning. It utilizes a Ridge Regression model trained on meteorological data to provide predictions based on user input.

## Project Structure

- `application.py`: Main Flask application for serving the web interface and prediction API.
- `Models/`: Contains the trained Ridge Regression model (`ridge.pkl`) and scaler (`scaler.pkl`).
- `Notebook/`: Jupyter notebook for data analysis and model development.
- `templates/`: HTML templates for the web interface (`index.html`, `home.html`).
- `requirements.txt`: Python dependencies for the project.

## Features

- Predicts Fire Weather Index (FWI) based on meteorological inputs.
- User-friendly web interface for entering data and viewing predictions.
- Jupyter notebook for data exploration and model training.

## Setup Instructions

1. **Clone the repository:**
	```bash
	git clone <your-repo-url>
	cd Algerian Forest Fire
	```
2. **Install dependencies:**
	```bash
	pip install -r requirements.txt
	```
3. **Run the application:**
	```bash
	python application.py
	```
4. **Access the web app:**
	Open your browser and go to `http://127.0.0.1:5000/`

## Usage

1. Go to the home page and enter the required meteorological parameters:
	- Temperature
	- Relative Humidity (RH)
	- Wind Speed (Ws)
	- Rain
	- FFMC, DMC, ISI, Classes, Region
2. Click "Predict" to get the FWI prediction.

## Model Details

- The model is trained using Ridge Regression and standard scaling.
- Model files are stored in the `Models/` directory.

## License

This project is for educational purposes.