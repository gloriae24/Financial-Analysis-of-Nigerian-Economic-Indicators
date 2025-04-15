
# 📊 Financial Analysis of Nigerian Economic Indicators

**Project Title:** Correlation Analysis and Productivity Modeling Using Nigerian Macroeconomic Data

---

## 🔍 Project Overview

This data science project investigates the interdependencies between major macroeconomic variables in Nigeria. It derives a custom productivity model from real-world financial indicators like money supply, inflation, exchange rates, and stock performance.

![Project Overview](visuals/Fin report.jpg)

---

## 🧠 Objectives

- Visualize and analyze trends in core Nigerian economic indicators
- Identify key correlations across stock prices, inflation, M1 money supply, and currency rates
- Design a productivity formula that reflects real economic health
- Derive insights backed by economic theory and statistical methods

---

## 📁 Folder Structure

- `data/` – Contains raw and cleaned datasets  
- `notebooks/` – Jupyter notebooks used for analysis  
- `visuals/` – Graphs and visualizations exported from the notebook  
- `reports/` – PDF report summarizing the findings  
- `models/` – Documentation for the productivity model  
- `requirements.txt` – Python dependencies  

---

## 📈 Exploratory Data Analysis

Visualizations include:

- 💵 M1 Money Supply Over Time  
- 📈 Stock Market Volume Trends  
- 📊 12-Month Average Inflation  
- 💱 Exchange Rate (Open vs Close)  
- 🔥 Correlation Heatmap  

All charts are stored in `visuals/`.

---

## 🔗 Correlation Highlights

| Variables                          | Correlation |
|-----------------------------------|-------------|
| Stock Price & M1 Supply           | 0.9227      |
| M1 Supply & Inflation (12M Avg)   | 0.8622      |
| M1 Supply & Exchange Rate (Open)  | -0.8054     |
| Inflation & Exchange Rate         | -0.7        |
| High/Low Stock & Inflation        | 0.8         |

---

## 🧮 Productivity Model

📘 **Formula**  

Productivity = (M1 Supply / (Currency Devaluation + 1)) × (Inflation Rate + 1)

Where:  
`Currency Devaluation = Exchange Rate Close – Exchange Rate Open`

📄 Formula breakdown stored in `models/productivity_model_formula.txt`

---

## 🛠 Tools Used

- Python (Pandas, Seaborn, Matplotlib)  
- Jupyter Notebook  
- Google Sheets (initial data prep)  

---

## 📄 Report & Outputs

- Full notebook: [`notebooks/correlation_productivity_model.ipynb`](notebooks/correlation_productivity_model.ipynb)  
- PDF Summary Report: [`reports/final_report.pdf`](reports/final_report.pdf)  
- Charts: [`visuals/`](visuals/)  

---

## ✅ Conclusion

This project builds a data-driven model to analyze Nigeria’s macroeconomic performance. It can be extended for:

- Forecasting productivity under policy changes  
- Comparing cross-country economic trends  
- Building real-time dashboards for policymakers

---

## 📬 Contact

For collaboration or data access, please reach out via [GitHub Issues](https://github.com/yourusername/Financial-Analysis-Nigerian-Economy/issues).
📄 requirements.txt (sample content)
pandas
matplotlib
seaborn
jupyter

