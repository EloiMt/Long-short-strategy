# Long-short-strategy

# Python Project: Long-Short Strategy

### **Project Overview**
This project explores a **Long-Short Investment Strategy**, using momentum and value-based scoring metrics to identify the most promising stocks for long and short positions. The goal is to assess the viability and profitability of this strategy in a real-world setting using historical market data.

The methodology builds upon widely recognized momentum and value investing principles, combining them to create an optimized portfolio strategy.

---

### **Methodology**

#### **1. Scoring Phase**
**Objective:** Rank stocks based on momentum and value scores to construct long and short portfolios.

- **Momentum Score:** Calculated as the rolling standard deviation of average monthly returns over the past 12 months.
- **Value Score:** Derived as the inverse of the rolling standard deviation of the price-to-book ratio.
- **Global Score:** Averaged from the momentum and value scores.

#### **2. Portfolio Formation**
- Stocks are sorted based on their global scores.
- The **Top 15 stocks** with the highest scores form the **Long Portfolio**.
- The **Bottom 15 stocks** with the lowest scores form the **Short Portfolio**.

#### **3. Investment Simulation**
- Starting with an initial capital of €100,000:
  - **50%** is allocated to long positions.
  - **50%** is allocated to short positions.
- The portfolios are rebalanced monthly, updating weights and capital.
- The strategy performance is benchmarked against major indices (e.g., S&P 500, CAC 40, DAX).

---

### **Key Results**
- **Net Capital Evolution:** A positive cumulative performance was observed over the investment period.
- The strategy consistently outperformed key indices (S&P 500, CAC 40, etc.) across the simulated period (2008–2023).

---

### **Results**

#### **Portfolio Performance vs. Indices**
The strategy was benchmarked against indices like the S&P 500, CAC 40, DAX, FTSE 100, Nikkei 225, and Hang Seng.

#### **Findings**
- **Long Portfolio:** High-performing stocks consistently delivered strong returns.
- **Short Portfolio:** Low-performing stocks often underperformed, aligning with the strategy's objectives.

---

### **References**
- **Academic Foundations:**
  - Jegadeesh, N., & Titman, S. (1993). *Returns to Buying Winners and Selling Losers: Implications for Stock Market Efficiency.* Journal of Finance.
- **Market Data:** Obtained through **Yahoo Finance**.

---

### **License**
This project is licensed under the MIT License. See the LICENSE file for details.

---

### **Contact**
For any questions or feedback, feel free to contact:
- **Email:** your_email@domain.com
- **GitHub Profile:** [Your GitHub Profile](https://github.com/your_username)

The data used in this project is included in `DATA.xlsx` and consists of:
- **Date:** Monthly observations.
- **Stock Metrics:** Returns, Price-to-Book ratios, and other fundamental data.

---

