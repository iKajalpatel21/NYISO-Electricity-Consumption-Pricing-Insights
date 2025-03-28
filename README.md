# ⚡ NYISO Electricity Consumption & Pricing Insights

Hello! 👋  
This is my fourth and final project for **CSCI 6444 – Introduction to Big Data and Analytics (Fall 2024)** at **George Washington University**.

In this notebook, I dive into time-series data from the **New York Independent System Operator (NYISO)** to explore patterns in electricity consumption, market pricing, and grid conditions.

---

## 📌 What’s the Project About?

This project uses real-world energy market data from NYISO to analyze and predict:

1. 💰 **Electricity price (LBMP)** changes based on demand and grid congestion
2. 📈 **Future demand forecasting** using pricing and marginal cost metrics
3. 🔥 **Anomaly detection** for sudden price spikes due to system stress

The data spans from 2001 to 2023 and includes:
- Load (demand) data
- Pricing data (locational marginal prices)
- Grid condition data (congestion and losses)

---

## 🧰 Tools & Tech Stack

- **Google Colab**
- **Python**
- **PySpark (Structured Streaming)**
- **Scikit-learn / MLlib**
- **Matplotlib / Seaborn**
- **CSV files** (public NYISO data)

---

## 🗂️ What’s in This Repo?

```bash
.
├── Project_4_NYISO_Electricity_Consumption_and_Pricing_Insights.ipynb   # Main notebook
├── Project 4 - NYISO Electricity Consumption and Pricing Insights.pdf   # Assignment prompt
└── README.md                                                            # This file
