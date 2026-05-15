# Insurance Premium Prediction

Machine learning project focused on predicting insurance premiums using regression techniques, feature engineering, and scalable model pipelines.

---

## Overview

This project analyzes insurance-related attributes such as:

- Age
- BMI
- Smoking habits
- Occupation
- Income level
- Lifestyle risk
- City tier

to estimate insurance premium categories accurately using supervised machine learning models.

The project includes:

- Data preprocessing
- Feature engineering
- Model training
- API development using FastAPI
- Health monitoring endpoint
- Swagger documentation support

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Regression/classification pipeline
- FastAPI backend
- Health monitoring endpoint
- Prediction endpoint
- Swagger UI documentation
- Deployment-ready structure

---

## Tech Stack

- Python
- FastAPI
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Uvicorn

---

## Project Structure

```bash
insurance-premium-prediction/
│
├── Model/
├── config/
├── schema/
├── app.py
├── requirements.txt
├── Dockerfile
├── README.md
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/devsutharsystems/insurance-premium-prediction.git
cd insurance-premium-prediction
```

Create virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the server:

```bash
uvicorn app:app --reload
```

---

## API Preview

### Swagger Documentation

<img width="1003" height="834" alt="Swagger Docs" src="https://github.com/user-attachments/assets/afc5bcfa-5277-4dfc-b521-793e166c1eef" />

---

### Health Endpoint

<img width="959" height="731" alt="Health Endpoint" src="https://github.com/user-attachments/assets/8321b0e3-606c-4293-a908-e5dae4afc637" />

---

### Prediction Endpoint

<img width="485" height="744" alt="Prediction Endpoint" src="https://github.com/user-attachments/assets/61c3254a-4e5b-483a-9dc9-3df29cfa480f" />

---

## Example API Endpoints

### Health Check

```http
GET /health
```

### Predict Insurance Premium

```http
POST /predict
```

---

## Future Improvements

- Model optimization
- Cloud deployment
- CI/CD integration
- Docker container deployment
- Frontend dashboard integration

---

## Author

Developed by Dev Suthar
