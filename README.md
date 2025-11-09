# Car Price Analysis Project

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![GitHub Repo](https://img.shields.io/badge/GitHub-Project-lightgrey)
![License](https://img.shields.io/badge/license-MIT-green)

## Project by Sharad Singh and Gaurav Pal

## Description
This project provides a comprehensive analysis of car pricing data for predicting market trends and estimating car prices. It includes exploratory data analysis (EDA), preprocessing, machine learning modeling, and evaluation. A formal academic report is included for submission purposes.

## Dataset
The included synthetic dataset contains 300 records with the following attributes:
- `make`: Brand of the car (e.g., Toyota, BMW)
- `model`: Specific car model
- `year`: Manufacturing year (2005–2024)
- `engine_hp`: Engine horsepower
- `engine_torque`: Engine torque (Nm)
- `transmission`: Transmission type
- `driven_wheels`: Drivetrain type
- `number_of_doors`: Number of doors
- `vehicle_size`: Vehicle size category
- `vehicle_style`: Body style (Sedan, SUV, etc.)
- `city_mpg`, `highway_mpg`: Fuel efficiency
- `popularity`: Brand popularity score
- `price`: Target variable (USD)

## Contents
```
car_price_analysis_project/
├── README.md
├── requirements.txt
├── LICENSE
├── Car_Price_Analysis_Project_Report.pdf
├── data/
│   └── car_price_sample.csv
├── notebooks/
│   └── Car_Price_Analysis.ipynb
└── scripts/
    └── train_model.py
```

## How to Run
1. Clone the repository.
2. Create a Python environment (Python 3.8+ recommended).
3. Install dependencies: `pip install -r requirements.txt`
4. Run the Jupyter notebook for analysis: `notebooks/Car_Price_Analysis.ipynb`.
5. Optionally, train the model using: `python scripts/train_model.py`

## Methodology
1. **Data Preprocessing:** Encoding categorical variables and scaling numeric features.
2. **Exploratory Data Analysis:** Statistical summaries and visualizations.
3. **Modeling:** Linear Regression and Random Forest Regressor.
4. **Evaluation:** Mean Absolute Error (MAE) and R² score.
5. **Market Trend Analysis:** Average price trends by make, model year, and vehicle style.

## Results Summary
- Random Forest Regressor outperformed Linear Regression.
- Luxury brands (BMW, Audi, Mercedes-Benz) have higher prices.
- SUVs and newer cars tend to cost more.

## Academic Report
A formal PDF report is included as `Car_Price_Analysis_Project_Report.pdf`.

## License
This project is licensed under the MIT License.

---
*Generated for academic submission purposes.*