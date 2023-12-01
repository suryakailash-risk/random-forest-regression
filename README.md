
Hourly Load Prediction for New Hampshire
Overview
This project focuses on predicting hourly electricity demand in the state of New Hampshire to enhance operational efficiency and resource optimization in the energy sector. By employing predictive modeling based on weather data, the aim is to offer a reliable service providing accurate energy demand forecasts. These forecasts can aid energy providers and consumers in planning ahead, optimizing energy usage, and ultimately leading to cost savings and environmental benefits.

Data
The data for this project was sourced from ISO New England (ISO-NE), specifically the ISO Express platform. The dataset comprises hourly electricity demand and weather data for the years 2020, 2021, and 2022. Key features include date, hour, real-time demand, and weather variables such as dry bulb temperature and dew point.

Feature Engineering and Preprocessing
The dataset underwent feature engineering to enhance its predictive capabilities. Features like squared temperature and dew point, interaction term, day of the week, month, and weekend indicator were created. The data was then preprocessed using Python with Pandas and Statsmodels libraries.

Methodology
- Data exploration: The data was explored using descriptive statistics and visualization techniques to understand the distribution, trends and seasonality of the variables, as well as the correlation and interaction among them.
- Feature selection: The features were selected based on their importance and relevance for the prediction task, using methods such as variance threshold, correlation matrix, mutual information and recursive feature elimination.
- Model development: Two models were developed using Linear Regression and Random Forest algorithms, using scikit-learn library in Python. The models were trained on 80% of the data and tested on 20% of the data, using 10-fold cross-validation and grid search for hyperparameter tuning.
- Model evaluation: The models were evaluated using various metrics, such as mean absolute error (MAE), mean squared error (MSE) and coefficient of determination (R-squared). The results were compared and analyzed to assess the strengths and weaknesses of each model.
The project utilized two regression models: Random Forest and Linear Regression. The scikit-learn library in Python facilitated model development, training on data from 2020 and 2021, and testing on data from 2022. Model evaluation involved metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.

Results
Random Forest Model:
MAE: 18.30
MSE: 670.73
RMSE: 25.90
R-squared: 0.98
Linear Regression Model:
MAE: 142.27
MSE: 27748.38
RMSE: 166.58
R-squared: 0.17
The Random Forest model outperformed the Linear Regression model across all metrics, showcasing its ability to capture complex relationships in the data.

Recommendations
Service Implementation: The developed models can serve as the foundation for a service offering precise energy demand forecasts. Energy providers and consumers can utilize these forecasts for informed decision-making, leading to cost savings and environmental advantages.

Continuous Improvement: Enhance the project by incorporating more data, additional features, and exploring advanced techniques such as deep learning or time series analysis. This continuous improvement ensures the models' reliability and adaptability.

Applicability to Other Regions: Extend the project's applicability to other regions, countries, and sectors where energy demand forecasting is crucial. Adapt the models and methodologies to suit the specific characteristics of different regions.

References
ISO New England (ISO-NE) - ISO Express
Python Libraries: Pandas, Statsmodels, scikit-learn
