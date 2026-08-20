# Bike Price Prediction - Machine Learning Project

## 📌 Project Overview
An end-to-end Machine Learning project that predicts the selling price of used bikes based on features like Brand, Age, KM Driven, Power, Mileage, and Owner.

The model achieves **85%+ accuracy** using `RandomForestRegressor` and includes complete EDA, data cleaning, and an interactive prediction system.

## 📊 Dataset
- **Source**: Used Bikes Dataset
- **Total Records**: 10,000+
- **Target Variable**: `price`

## 🛠 Features Used
| Feature | Description |
| --- | --- |
| Brand | Bike Brand: Bajaj, Hero, Honda, RE, KTM etc |
| Bike_Age | 2026 - Manufacturing Year |
| kms_driven | Total KM driven |
| power | Engine Power in bhp |
| mileage | Mileage in kmpl |
| owner | First Owner, Second Owner etc |

## 📈 Key Insights from EDA
1. **Brand Impact**: Royal Enfield and KTM have the highest resale value
2. **Age Factor**: Bike Age is the most important feature affecting price
3. **KM Driven**: Price drops sharply after 40,000 KM
4. **Correlation**: Strong negative correlation between Age and Price

## 🤖 Machine Learning Model
- **Algorithm**: RandomForestRegressor
- **Accuracy**: R2 Score = 0.85
- **Average Error**: ~ Rs 12,000
- **Train-Test Split**: 80% Train, 20% Test

## 🚀 How to Run This Project

1.  Clone the repository
    ```bash
    git clone https://github.com/your-username/Bike-Price-Prediction.git