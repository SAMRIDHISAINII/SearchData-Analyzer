# SearchData Analyzer

#### Main Objective
The main objective of this project is to investigate whether the ability to predict search traffic can be translated into successful stock trading strategies. By cleverly analyzing MercadoLibre's financial and user data, the program aims to uncover any correlations or insights that could potentially contribute to the company's growth and success.

By utilizing Prophet's forecasting capabilities, it aims to predict future revenue for the company. The project incorporates data from MercadoLibre, the leading e-commerce platform in Latin America, including their search traffic and sales data.

#### Lib used
Pandas is a Python package that provides powerful data structures and tools for efficient data manipulation and analysis. It allows for easy handling of relational or labeled data, which will be crucial for processing and organizing the data from the CSV files.

Prophet is an open-source library specifically designed for time series forecasting. It utilizes an additive model to capture non-linear trends with seasonal patterns, including daily, weekly, and yearly effects. The Prophet library will be used to forecast future revenue based on the provided data.

hvPlot is a high-level plotting API built on top of HoloViews, a Python library for building interactive visualizations. It provides a convenient and consistent API for creating visualizations from data in Python. hvPlot will be employed to create insightful and informative plots based on the analyzed data.

#### Process
The analysis is done in the following order.

Step 1: Find unusual patterns in hourly Google search traffic
Step 2: Mine the search traffic data for seasonality
Step 3: Relate the search traffic to stock price patterns
Step 4: Create a time series model with Prophet
Step 5: Forecast revenue by using time series models

