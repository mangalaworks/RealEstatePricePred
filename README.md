🏠 Real Estate Price Predictor

A simple web app that predicts Bangalore house prices based on location, square footage, BHK, and bathrooms. Built with Flask, scikit-learn, and served using Nginx on an AWS EC2 instance.

🔧 Tech Stack

Backend: Python, Flask, scikit-learn

Frontend: HTML, CSS, JavaScript

Deployment: Nginx on Ubuntu (EC2)

🚀 Features

Predicts house prices using a trained Linear Regression model

REST API with:

GET /api/get_location_names

POST /api/predict_home_price

Responsive frontend to input values and view predicted price

🛠 Setup Instructions

Clone this repo

git clone https://github.com/mangalaworks/RealEstatePricePred.git
cd RealEstatePricePred

Set up Python environment

cd server
python3 -m venv venv --system-site-packages
source venv/bin/activate
pip install -r requirements.txt

Run the server

python server.py

Access the app

Go to: http://<your-EC2-public-IP>/app.html

Example: http://ec2-65-0-98-69.ap-south-1.compute.amazonaws.com/app.html

📁 Folder Structure

bhp_app/
├── client/      # Frontend files (HTML/CSS/JS)
├── model/       # Trained ML model and Jupyter notebook
├── server/      # Flask API code and requirements

