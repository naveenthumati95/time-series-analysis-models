# Time Series Analysis Models 📈

A comprehensive repository dedicated to the implementation and exploration of models for time series analysis and forecasting. This project serves as a learning resource and a practical guide for applying various techniques to temporal data.

---

## 📖 Overview

Time series forecasting is a critical technique in many domains, including finance, economics, and supply chain management. This repository breaks down the core concepts behind popular models and provides ready-to-use code within well-documented Jupyter notebooks.

---

## 📂 Models Implemented

### Classical Statistical Models

These models form the foundation of time series analysis and are excellent for understanding underlying patterns like trend and seasonality.

* #### `statistical_tsa_models.ipynb`
    This notebook provides a detailed walkthrough of the following models:
    * **ARMA (Autoregressive Moving Average):** Ideal for modeling stationary time series.
    * **ARIMA (Autoregressive Integrated Moving Average):** A versatile model that extends ARMA to handle non-stationary data.
    * **SARIMA (Seasonal ARIMA):** A powerful extension of ARIMA that incorporates seasonal components, making it highly effective for data with cyclical patterns (e.g., monthly sales data).

    The notebook covers key steps such as data visualization, stationarity testing (e.g., ADF test), model identification using ACF/PACF plots, and forecasting.

---

## 🚀 Getting Started

To get started with the code in this repository:

1.  Clone the repository to your local machine:
    ```bash
    git clone https://github.com/naveenthumati95/time-series-analysis-models.git
    ```
2.  Navigate into the directory:
    ```bash
    cd time-series-analysis-models
    ```
3.  Install the required dependencies and run the Jupyter notebook.

Happy forecasting!
