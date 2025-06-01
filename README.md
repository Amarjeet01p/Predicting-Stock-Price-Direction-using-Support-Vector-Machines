# Predicting-Stock-Price-Direction-using-Support-Vector-Machines
This repository contains an end-to-end implementation of a stock price movement prediction strategy using Support Vector Machines (SVM) and historical trading data.
# Predicting Stock Price Direction using Support Vector Machines (SVM)
---

## Tools Used
- Python, NumPy, Pandas
- Scikit-learn (`SVC`)
- Matplotlib
- Yahoo Finance (CSV data)
- Jupyter Notebook
- BlueShift (for live deployment support)

---

## Strategy Logic

We use two engineered features:
- `Open-Close`
- `High-Low`

Then, we:
- Train an SVM classifier to predict next-day movement (+1 = Buy, 0 = No Position)
- Calculate actual and strategy returns
- Compare cumulative performance

---

## Strategy Performance Visualization

###  *Cumulative Returns: Strategy vs Stock*

![Strategy vs Stock](![alt text](image.png))

**Strategy Cumulative Return**  
**Actual Stock Cumulative Return**

The strategy outperformed the stock with a return of approximately **18.87%** compared to **5.97%** from holding the stock alone:contentReference[oaicite:0]{index=0}.

---
