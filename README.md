# 🇰🇪 Kenya Youth Unemployment Analysis (1991–2025)
> A data science investigation into the long-term trajectory of youth unemployment in Kenya, combining exploratory analysis, statistical decomposition, and time series forecasting.

---

## 📌 Research Question
**How has youth unemployment in Kenya evolved over time, and can we forecast its future trajectory using time series modeling?**

### Sub-questions
- What is the long-term trend in Kenya's youth unemployment?
- Are there significant short-term fluctuations around the trend?
- Can we reliably forecast unemployment levels for the next 5 years?

---

## 💡 Hypothesis
Youth unemployment in Kenya shows a persistent upward structural trend, with short-term fluctuations driven by external economic shocks rather than cyclical patterns.

---

## 📂 Project Structure
kenya-youth-unemployment-analysis/
├── data/
│   └── SLUEM1524ZSKEN.csv
├── notebooks/
│   └── kenya_youth_unemployment_analysis.ipynb
├── trend_chart.html
├── bar_chart.html
├── heatmap.html
├── requirements.txt
└── README.md

---

## 🗃️ Dataset
| Field | Details |
|---|---|
| Source | FRED Economic Data — Federal Reserve Bank of St. Louis |
| Indicator | SLUEM1524ZSKEN (World Bank / ILO) |
| Coverage | 1991 — 2025 (35 years) |
| Link | https://fred.stlouisfed.org/series/SLUEM1524ZSKEN |
| License | Public Domain |

---

## 🛠️ Tools & Methods
- Python 3.12
- Pandas — data cleaning and manipulation
- Plotly — interactive visualizations
- Matplotlib and Seaborn — static chart exports
- Statsmodels — time series decomposition and ARIMA forecasting
- Google Colab — cloud development environment

---

## 📊 Key Findings
1. Youth unemployment rose from 6.21% in 1991 to 15.25% in 2025 — a 145% increase over 34 years
2. The highest recorded rate was 15.49% in 2022, driven by COVID-19 economic disruption
3. Decade analysis shows a consistent upward pattern across all periods
4. Time series decomposition reveals a clear structural trend with irregular short-term shocks
5. ARIMA forecasting projects continued upward pressure through 2030

---

## 📈 Visualizations
| Chart | Description |
|---|---|
| [Trend Chart](trend_chart.html) | Interactive line chart — unemployment rate over time |
| [Bar Chart](bar_chart.html) | Average unemployment rate by decade |
| [Heatmap](heatmap.html) | Correlation matrix of unemployment indicators |

---

## 🔍 Interpretation
Kenya's youth unemployment crisis reflects a structural mismatch between education systems and labour market demands. The persistent upward trend suggests that economic growth has not translated into proportional job creation for young people. Short-term spikes around 2008-2009 and 2020-2022 confirm that Kenya's youth employment is highly vulnerable to external shocks.

---

## 💼 Policy Recommendations
1. Invest in digital skills training — align education with tech sector demand
2. Support youth entrepreneurship — reduce barriers to self-employment
3. Strengthen vocational education — create pathways outside formal university
4. Target post-crisis recovery — youth-specific stimulus during economic shocks
5. Use data-driven policy monitoring to guide interventions

---

## 📚 Citations
- World Bank Open Data / FRED Economic Data — Federal Reserve Bank of St. Louis
- International Labour Organization (ILO) — ILOSTAT Database
- Indicator: Unemployment, youth total percentage of total labor force ages 15 to 24 — Kenya
