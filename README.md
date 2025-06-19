# 📈 Nifty 50 Macro Dashboard

An interactive Power BI dashboard analyzing the **volatility of Nifty 50** in relation to key **macroeconomic indicators** of India from **2010 to 2025**, with forecasting and visual insights.

---

## 🧮 Macroeconomic Indicators Used

This project focuses on the intersection of capital markets and macroeconomic fundamentals. The following indicators were selected for their significant influence on stock market behavior:

- **GDP Growth (%)**
- **Inflation (CPI)**
- **Interest Rate (Repo Rate %)**
- **IIP (Index of Industrial Production)**
- **USD to INR Exchange Rate**
- **Nifty 50 Volatility**

---

## 🌐 Data Sources

The dataset was manually compiled and cleaned using **reliable, official macroeconomic databases**:

- 📊 [World Bank Open Data](https://data.worldbank.org/)
- 🏦 [RBI Database](https://dbie.rbi.org.in/)
- 🇮🇳 [MOSPI (Ministry of Statistics and Programme Implementation)](https://mospi.gov.in/)
- 📈 [Yahoo Finance](https://finance.yahoo.com/) (for historical Nifty 50 prices)
- 🧾 [Trading Economics](https://tradingeconomics.com/)
- 📁 Data combined and structured manually in Excel for preprocessing.

---

## 🐍 Data Preparation in Python

Before visualizing in Power BI, the dataset underwent preprocessing using **Python**.

Key libraries used:

```python
import pandas as pd
import numpy as np

## 📊 Power BI Dashboard

![Dashboard Preview](dashboard.png)

The Power BI dashboard is designed to be clean, intuitive, and analytically rich.

### 🔍 Key Visuals:

#### ✅ KPIs
- **Latest GDP Growth (%)**
- **Max Repo Rate (%)**
- **Most Volatile Year**
- **Cumulative GDP Growth**

#### 📉 Forecasting
- **Nifty 50 Volatility Forecast** based on past trends and macro indicators.

#### 🧠 Correlation Analysis
- Scatter plot between **Inflation and Nifty 50 Volatility**
- Decomposition Tree breaking down volatility by **GDP Bins**, **CPI**, and **Repo Rate**

#### 🌡️ Macro Heat Map (2010–2025)
- Conditional formatting applied to show **intensity of macro shocks** over time.

#### 📈 Dual Axis Chart
- Track **Inflation vs USD to INR** on a yearly basis.

#### 🧩 Interactive Elements
- **Slicers**:
  - Year (Horizontal)
  - GDP Growth Ranges (Bins)
- All visuals are connected via **interactive slicers** for dynamic filtering.

#### 📊 Pie Chart: GDP Performance Categories
- Proportion of years with **high**, **moderate**, and **low** GDP growth rates.
