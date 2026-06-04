# Time-series-analysis
# 📈 Time Series Sales Forecasting using ARIMA & SARIMAX

An end-to-end Python implementation for simulating historical monthly sales data and applying classic statistical time-series models (**ARIMA** and **SARIMAX**) to forecast future trends.

This project outlines data generation, exploratory data visualization, and time-series model preparation using popular Python data science libraries.

---

## 🚀 Features
* **Synthetic Data Generation:** Generates 3 years (36 months) of synthetic sales data incorporating a linear growth trend and normal random noise.
* **Data Visualization:** Built-in charting using `matplotlib` to analyze monthly sales patterns over time.
* **Advanced Modeling:** Structural setup for fitting Autoregressive Integrated Moving Average (**ARIMA**) and Seasonal ARIMA (**SARIMAX**) forecasting models using `statsmodels`.

---

## 📊 Dataset Preview

The model evaluates a simulated pandas DataFrame containing continuous monthly sales tracking over time[cite: 1]:

| Date | Sales ($) |
| :--- | :--- |
| 2021-01-01 | 207.45 |
| 2021-02-01 | 200.93 |
| 2021-03-01 | 215.71 |
| 2021-04-01 | 231.85 |
| 2021-05-01 | 208.49 |

---

## 🛠️ Technology Stack & Dependencies

The project relies on the following Python packages[cite: 1]:
* **Pandas** - Data manipulation and analysis[cite: 1].
* **NumPy** - Numerical computations and random distributions[cite: 1].
* **Matplotlib** - Data visualization and plotting[cite: 1].
* **Statsmodels** - Time-series analysis and statistical models (`ARIMA`/`SARIMAX`)[cite: 1].

---

