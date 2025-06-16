**Iowa Liquor Sales: EDA & Sales Forecasting**

This project analyzes historical liquor sales data from Iowa (2012–2017) through exploratory data analysis and predictive modeling. The goal was to understand sales patterns and model weekly liquor volume sold per county.

We performed:

- Data cleaning and filtering on 12.6M records.

- EDA on store locations, monthly seasonality, and county-level trends.

- Sales prediction using a LightGBM regression model trained on features like bottle size, price, month, and county.

*To accelerate model training, parallel processing was enabled via n_jobs = -1 in LightGBM.*
