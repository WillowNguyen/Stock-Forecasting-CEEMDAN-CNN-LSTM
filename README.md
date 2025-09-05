# 📊 Stock Price Forecasting with CEEMDAN–CNN–LSTM  
*A Data-Driven Business Intelligence Project for Financial Decision Support*  

This repository showcases an **individual project** where I built a hybrid deep learning model to forecast major Vietnam stock indices.  
By combining **signal decomposition (CEEMDAN)** with **deep learning (CNN–LSTM)**, the project demonstrates how advanced analytics can deliver **accurate, actionable insights** for investors and financial institutions.  

---

## 🎯 Business Motivation
Financial markets are highly volatile, and **poor forecasting increases risk exposure**.  
Investors and portfolio managers need reliable insights to:  
- Anticipate market movements  
- Manage risk effectively  
- Optimize investment decisions  

This project addresses that need by delivering **predictive analytics** that reduce forecast errors and improve confidence in decision-making.  

---

## 🔍 Project Objectives
1. **Build a predictive model** that can handle noisy, non-linear financial time series.  
2. **Evaluate forecasting accuracy** using standard error metrics (RMSE, MAE, MAPE).  
3. **Generate business-relevant insights** for investment strategy and risk management.  

---

## 📊 Data
- **Source**: VNStock API  
- **Period**: Sep 2017 – Oct 2024  
- **Indices analyzed**: VNINDEX, VN30, HNXINDEX, HNX30, UPCOMINDEX  
- **Features**: Daily open, close, high, low, and trading volume  

---

## ⚙️ Methodology
### 1. Data Preprocessing  
- Cleaning: handled missing values and outliers  
- Normalization: standardized input features for model stability  

### 2. Signal Decomposition (CEEMDAN)  
- Broke down raw stock index series into stable components (IMFs + residuals)  
- Reduced noise, highlighted true market patterns  

### 3. Hybrid Modeling (CNN + LSTM)  
- **CNN**: detected short-term fluctuations in IMFs  
- **LSTM**: captured long-term temporal dependencies  
- Combined forecasts to reconstruct full signal  

### 4. Evaluation Metrics  
- RMSE, MAE, MAPE – standard for financial forecasting models  

---

## 🚀 Key Results & Business Value
| Index       | RMSE  | MAE  | MAPE (%) |
|-------------|-------|------|----------|
| **VNINDEX** | 0.01  | 0.01 | **2.15** |
| VN30        | 0.01  | 0.01 | 2.22     |
| UPCOMINDEX  | 0.01  | 0.01 | 2.96     |
| HNXINDEX    | 0.01  | 0.00 | 3.80     |
| HNX30       | 0.01  | 0.00 | 5.55     |

✨ **Impact for Business Intelligence**:  
- Achieved forecasting accuracy with **MAPE as low as 2.15%** → enabling data-driven decision-making.  
- Predictions closely matched actual market trends → reducing uncertainty.  
- Demonstrated the **practical use of predictive analytics** in investment risk management.  

### Sample Forecasts
![VNINDEX Forecast](Results/forecast_vnindex.png)  
*Actual vs Predicted (VNINDEX)*  

![VN30 Forecast](Results/forecast_vn30.png)  
*Actual vs Predicted (VN30)*  

---

## 💡 Insights for Business Analysts & BI Teams
- **Predictive Power**: The hybrid model reduces noise and improves accuracy → directly supporting **investment planning**.  
- **Risk Management**: Forecast errors minimized → better scenario analysis and downside risk control.  
- **Scalability**: Approach can be extended beyond indices to **individual stocks, bonds, or derivatives**.  
- **BI Alignment**: Clear example of how **data preprocessing, advanced modeling, and visualization** can transform raw data into **business-ready insights**.  

---

## 🛠️ Tech Stack
- **Languages**: Python  
- **Libraries**: NumPy, Pandas, Matplotlib, TensorFlow/Keras, libeemd  
- **Techniques**: CEEMDAN decomposition, CNN, LSTM, Time-Series Forecasting  

---

## 📣 Author
👤 **Nguyen Thi Thanh Truc**  
- Bachelor of Investment Economics, University of Economics HCMC  
- Experienced in **Data Analysis, Predictive Modeling, and Business Intelligence**  
- Passionate about turning **complex data into actionable insights** for strategic decision-making  

---
