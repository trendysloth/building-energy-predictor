## Definition
In this project, I developed machine learning models to predict building energy usage in the following areas: chilled water, electric, hot water and steam meters. The dataset used for training comes from over 1000 buildings over a three-year timeframe.
[download data](https://www.kaggle.com/c/ashrae-energy-prediction/data)

## Project Overview
Buildings consume about 40% of the total energy use in the United States. In recent years, significant investments have been made to improve building energy consumption to lower operational cost and reduce environmental footprint. Predicting energy used by heating, ventilating, and air-conditioning systems is important for HVAC diagnostics, system control, system identification, as well as energy management and optimization.

Under the current pay-for-performance financing plan, building owners make payments based on the difference between their real energy consumption and what they would have used without any retrofits. The latter values come from an estimation model. However, building energy estimation models are challenging to build and current methods of estimation are fragmented and many of them do not scale well.

## Implementation
I worked with 4 different models to tackle this problem.
1. Linear Regression
2. Support Vector Machine
3. LightGBM
4. LSTM (long short-term memory)

Data processing could be found in: Data Preprocessing.ipynb
Exploratory Data Analysis could be found in: EDA.ipynb
Modeling could be found in: Modeling.ipynb
capstone_report.pdf is a detailed documentation of the project.
