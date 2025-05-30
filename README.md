# Time-Series-Modeling

The report presents a time series forecasting project on international tourist arrivals to Italy using ARIMA and ARIMAX models, focusing on post-COVID recovery patterns. Through technical coding in Python, it demonstrates how incorporating external shocks like a post-COVID dummy improves forecast accuracy and informs strategic planning.

This project presents a comprehensive, end-to-end forecasting pipeline for international tourist arrivals to Italy, implemented entirely in Python. The report begins with the context: tourism's vital contribution to Italy’s economy and the need for reliable, data-driven forecasting tools, especially in a post-COVID recovery phase. 

The analysis uses monthly arrival data from Banca d’Italia (1997–2024), covering multiple countries of origin and aggregated into a single time series. 

Before any modeling, extensive data cleaning and exploratory analysis were performed to ensure integrity, identify seasonality and trends, and select the most relevant variables—laying the groundwork for effective modeling.

The project applies a series of time-series models: starting with ARIMA(1,1,1) as a baseline, then improving fit and reducing error with ARIMA(2,1,0), and finally incorporating a post-COVID intervention dummy into an ARIMAX(2,1,0) specification. These models were compared using AIC, residual diagnostics (Ljung–Box test, ACF/PACF), 

and out-of-sample forecasting performance measured through MAPE. Each model was carefully validated through hold-out forecasting, and visualized to compare actual vs predicted arrivals, showing how each model handles structural breaks and post-pandemic recovery.

The entire workflow was built in code—from initial Excel parsing, transformation, and validation, through model fitting and evaluation, to the production of publication-ready plots. The codebase emphasizes transparency, reproducibility, and interpretability, aligning with best practices in data science. The result is not just a forecast, 

but a technically sound, policy-relevant framework that can help both public and private stakeholders in tourism plan more effectively for the future.
