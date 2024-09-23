# Algerian Forest Fires - Regression Analysis

## Problem Statement
Forest fires are a major environmental concern, especially in regions with dense vegetation. Understanding the factors contributing to these fires is crucial for prevention and mitigation. This project aims to use historical data to build a predictive model for forest fire intensity based on multiple environmental variables.

## Dataset
- **Source:** [Predicting Forest Fire in Algeria Using Data Mining Techniques - ResearchGate](https://www.researchgate.net/publication/339062373_Predicting_Forest_Fire_in_Algeria_Using_Data_Mining_Techniques_Case_Study_of_the_Decision_Tree_Algorithm)
- **Description:** The dataset contains various environmental attributes such as temperature, humidity, wind speed, and rainfall, recorded over multiple years.

## Key Features
- **Temperature:** Recorded in degrees Celsius.
- **Humidity:** Relative humidity percentage.
- **Wind Speed:** Speed of the wind in km/h.
- **Rainfall:** Precipitation in mm.

## Methodology
1. **Data Cleaning:** Handling missing values, outliers, and transforming variables.
2. **Exploratory Data Analysis (EDA):** Visualization and statistical analysis to identify trends and patterns.
3. **Feature Engineering:** Creating new features to improve model performance.
4. **Model Building:** Implementing multiple linear regression to predict forest fire intensity.
5. **Model Evaluation:** Using metrics like R-squared, RMSE, and MAE to evaluate the model's performance.

## Technologies Used
- **Python:** For data processing and analysis.
- **Pandas & NumPy:** For data manipulation.
- **Matplotlib & Seaborn:** For data visualization.
- **Scikit-learn:** For building and evaluating the regression model.

## Results
The multiple linear regression model achieved an R-squared score of `0.651`, indicating the proportion of variance in the dependent variable explained by the independent variables.

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/pcpetty/Algerian-Forest-Fires-Regression-Analysis.git

2. **Navigate to the project directory:**
   ```bash
   cd Algerian-Forest-Fires-Regression-Analysis

3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt

4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/Algerian-Forest-Fires_Multiple-Linear-Regression.ipynb

