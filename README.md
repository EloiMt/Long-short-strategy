# Long-Short Strategy

## **Python Project: Long-Short Strategy**

### **Project Overview**
This project explores a **Long-Short Investment Strategy**, leveraging momentum and value-based scoring metrics to identify the most promising stocks for long and short positions. The aim is to evaluate the strategy's profitability and its ability to outperform key market indices using historical data.

By combining established momentum and value investing principles, the strategy seeks to maximize returns through monthly portfolio rebalancing and dynamic scoring.

---

### **Methodology**

#### **1. Scoring Phase**
**Objective:** Rank stocks based on momentum and value scores to construct long and short portfolios.

- **Momentum Score:** Calculated as the rolling standard deviation of average monthly returns over the past 12 months. This identifies consistent top performers.
- **Value Score:** Derived as the inverse of the rolling standard deviation of the price-to-book ratio, prioritizing stable valuation metrics.
- **Global Score:** The average of momentum and value scores, balancing growth potential and valuation consistency.

#### **2. Portfolio Formation**
- Stocks are ranked based on their global scores.
- The **Top 15 stocks** with the highest scores form the **Long Portfolio**.
- The **Bottom 15 stocks** with the lowest scores form the **Short Portfolio**.

#### **3. Investment Simulation**
- **Initial Capital:** €100,000.
  - **50%** is allocated to the **Long Portfolio**.
  - **50%** is allocated to the **Short Portfolio**.
- **Monthly Rebalancing:** Portfolios are reweighted, and capital is adjusted dynamically.
- **Benchmark Comparison:** The strategy's performance is compared to major indices, including:
  - **S&P 500** (US market)
  - **CAC 40** (French market)
  - **DAX** (German market)
  - **FTSE 100** (UK market)
  - **Nikkei 225** (Japanese market)
  - **Hang Seng** (Hong Kong market)

---

### **Results**

#### **Portfolio Performance**
- **Initial Capital:** €100,000
- **Final Capital:** €201,310.06
- **Profitability:** **101.31%** over the investment period (March 2008 – March 2023).

The strategy demonstrates a significant cumulative performance, showcasing the effectiveness of combining momentum and value-based scoring metrics for a long-short investment approach.

#### **Portfolio Performance vs. Indices**
The strategy was benchmarked against key indices like:
- **Outperformed:** Hang Seng, CAC 40, FTSE 100
- **Underperformed:** S&P 500, DAX 30, Nikkei 225

#### **Findings**
- **Long Portfolio:** High-performing stocks consistently delivered strong returns.
- **Short Portfolio:** Low-performing stocks often underperformed, aligning with the strategy's objectives.
- The strategy capitalizes on market inefficiencies, leveraging both momentum and value to drive superior returns.

---

### **Dataset**
The dataset, provided in `DATA.xlsx`, includes:
- **Date:** Monthly data points.
- **Stock Metrics:** Returns and Price-to-Book ratios for each stock.
- **Benchmark Returns:** Performance of indices for comparison.

---

### **References**
- **Market Data:** 
  - The indices' historical data were obtained through **Yahoo Finance** using the `yfinance` Python library. This data includes key indices like the **S&P 500**, **CAC 40**, **DAX**, **FTSE 100**, **Nikkei 225**, and **Hang Seng**, which were used to benchmark the strategy's performance.

---

### **License**
This project is licensed under the MIT License. See the LICENSE file for details.

---

### **Contact**
For any questions or feedback, feel free to contact:
- **Email:** eloi.martin@edu.devinci.fr
- **GitHub Profile:** [EloiMt](https://github.com/EloiMt)
