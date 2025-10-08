# 🕒 Electric Production Time Series Forecasting

## 📊 Project Overview
This project focuses on **forecasting future electric production** using **Time Series Analysis** techniques.  
The goal is to identify patterns and trends in historical data and build a predictive model to estimate future electricity output.

---

## 🧠 Key Objectives
- Analyze historical electric production data.
- Perform data cleaning, visualization, and exploratory analysis.
- Apply time series techniques such as **ARIMA, SARIMA**, and **Auto ARIMA**.
- Evaluate model performance using statistical metrics.
- Forecast future values based on trained models.

---

## 📂 Dataset
**File:** `Electric Production_Time Series.csv`  
- Source: Public dataset of U.S. electric production (in Megawatt-hours).  
- Contains monthly data from 1985 to 2018.  
- Features:
  - `DATE`: Time index (month/year)
  - `IPG2211A2N`: Electric Production

---

## ⚙️ Technologies Used
- **Python**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Statsmodels**
- **pmdarima (Auto ARIMA)**

---

## 📈 Steps Involved
1. **Importing Libraries & Loading Data**
2. **Data Exploration and Cleaning**
3. **Data Visualization**
4. **Checking Stationarity (ADF Test)**
5. **Differencing and Trend Removal**
6. **Model Building**
   - ARIMA
   - SARIMA
   - Auto ARIMA
7. **Model Evaluation**
8. **Forecasting Future Electric Production**

---

## 🔍 Model Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- AIC / BIC Scores

---

## 📉 Forecast Result
The best-fit model was selected using **AIC/BIC** criteria and forecasted production trends for upcoming months, showing seasonal patterns and gradual increase in electricity demand.

---

## 📁 Project Files
| File Name | Description |
|------------|-------------|
| `timesseriespractice.ipynb` | Main Jupyter notebook containing code and analysis |
| `Electric Production_Time Series.csv` | Dataset used for model training and forecasting |

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Electric-Production-TimeSeries.git
jupyter notebook timesseriespractice.ipynb


📚 Learnings & Insights

Gained hands-on experience in Time Series Forecasting.

Understood how to make a non-stationary series stationary.

Learned to tune ARIMA/SARIMA parameters effectively.

Practiced model performance evaluation and visualization.

## 👩‍💻 Author
**Ravali Ambadi**  
Aspiring Data Scientist  
[LinkedIn](www.linkedin.com/in/ravali-ambadi-872772187)
