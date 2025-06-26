# RealEstatePricePred

A web app that predicts Bangalore home prices using a trained machine-learning model, Flask for the API, and a static HTML/JS frontend served by Nginx.

---

## 📋 Table of Contents

1. [Demo](#demo)  
2. [Features](#features)  
3. [Tech Stack](#tech-stack)  
4. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
   - [Running Locally](#running-locally)  
5. [Project Structure](#project-structure)  
6. [Usage](#usage)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## 🔍 Demo

Live at:  
👉 [http://ec2-65-0-98-69.ap-south-1.compute.amazonaws.com/app.html](http://ec2-65-0-98-69.ap-south-1.compute.amazonaws.com/app.html)

*(You can add a screenshot or GIF demo here)*

---

## 🚀 Features

- Predict home prices based on:
  - Location  
  - Total square footage  
  - Number of bathrooms  
  - Number of bedrooms (BHK)  
- API endpoints:
  - `GET /api/get_location_names` – returns a list of available areas  
  - `POST /api/predict_home_price` – accepts JSON and returns a price estimate  

---

## 🛠 Tech Stack

- **Backend**: Python 3.12, Flask, scikit-learn  
- **Frontend**: HTML, CSS, Vanilla JavaScript  
- **Server**: Nginx reverse-proxy on Ubuntu EC2  
- **Model**: LinearRegression trained on Bangalore housing data  

---

## 🏁 Getting Started

### ✅ Prerequisites

- Ubuntu 20.04+ or Linux  
- Python 3.12  
- Git & GitHub  
- (Optional) AWS EC2 for deployment  

---

### 🔧 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/mangalaworks/RealEstatePricePred.git
cd RealEstatePricePred
