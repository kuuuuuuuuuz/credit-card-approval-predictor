# Credit Card Approval Prediction / Прогнозирование одобрения кредитных карт

## 🇺🇸 English Version

### Dataset
**Name:** Credit Card Approval Dataset  
**Source:** [[Credit_card.csv](https://www.kaggle.com/datasets/vishwas199728/credit-card)]

### Project Overview
Machine learning model to automate credit card approval decisions based on socio-demographic data.

### Metrics
* **Model:** Random Forest
* **Precision (Class 1):** **0.71**
* **Accuracy:** **91%**

### Implementation
* **Data Handling:** Fixed `Employed_days` anomalies and handled missing values in `Annual_income`.
* **Features:** Engineered **Age** and **Years of Experience** from raw data.
* **Analysis:** Random Forest provides a stable precision of 0.71, significantly outperforming the 0.16 precision baseline of Logistic Regression.

---

## 🇷🇺 Русская версия

### Датасет
**Название:** Credit Card Approval Dataset  
**Источник:** [[Credit_card.csv](https://www.kaggle.com/datasets/vishwas199728/credit-card)]

### Описание проекта
Модель машинного обучения для автоматизации принятия решений о выдаче кредитных карт на основе данных клиентов.

### Метрики
* **Модель:** Random Forest
* **Precision (Class 1):** **0.71**
* **Accuracy:** **91%**

### Реализация
* **Обработка данных:** Исправлены аномалии в стаже (`Employed_days`) и заполнены пропуски в доходах (`Annual_income`).
* **Признаки:** Сформированы переменные **Age** (возраст) и **Years_Experience** (стаж) в годах.
* **Анализ:** Random Forest обеспечивает точность 0.71, что на порядок выше базового результата логистической регрессии (0.16).
