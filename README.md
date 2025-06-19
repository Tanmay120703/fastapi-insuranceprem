# 💼 Insurance Premium Category Prediction API

This FastAPI-based project predicts the **insurance premium category** of a user based on demographic and lifestyle details such as age, BMI, income, occupation, smoking habits, and city tier.

The API uses a pre-trained machine learning model (`model.pkl`) to return the predicted insurance premium **category**.

---

## 🚀 Features

- `/predict` endpoint for insurance premium category prediction
- Auto-computed fields: `bmi`, `lifestyle_risk`, `age_group`, `city_tier`
- Built with FastAPI + Pydantic + scikit-learn (pickle model)
- Validated input using Pydantic models
- JSON-based response for easy integration with web/mobile apps

---

## 📦 Tech Stack

- **FastAPI** – high-performance API framework
- **Pydantic** – data validation and parsing
- **Pandas** – data handling for model input
- **scikit-learn** – machine learning model (via pickle)
- **Uvicorn** – ASGI server
