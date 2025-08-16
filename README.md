# Interest Rate Model Risk Analysis Engine

This project implements a **risk analysis framework for interest rate models**, inspired by institutional platforms like BlackRock's Aladdin.  
It evaluates interest rate dynamics, quantifies model risks, and simulates potential portfolio impacts under various scenarios.

---

## 📌 Project Overview
- Models **interest rate term structures** and their evolution.  
- Simulates shocks and stress scenarios to measure **interest rate risk**.  
- Computes **key risk metrics** such as Value at Risk (VaR), Conditional VaR (CVaR), duration, convexity, and scenario P&L.  
- Provides tools for **stress testing** portfolios exposed to rate movements.  
- Designed as a foundation for a more comprehensive **risk management engine**.

---

## 📊 Mathematical Concepts Used
- **Yield to Maturity (YTM)** – used to estimate the return on fixed-income securities.  
- **Duration & Modified Duration** – measure interest rate sensitivity of bonds/portfolios.  
- **Convexity** – captures the curvature effect in bond pricing with respect to interest rate changes.  
- **Value at Risk (VaR)** – quantifies potential losses under normal market conditions.  
- **Conditional VaR (CVaR)** – measures the expected loss given that the loss has exceeded VaR.  
- **Scenario Analysis** – applies parallel shifts, twists, or stress conditions to yield curves.  
- **Backtesting Framework** – evaluates how portfolios would perform under historical or simulated interest rate environments.  

---

## 🛠️ Requirements
This project is written in **Python 3** and uses the following libraries:

- **NumPy** – Numerical computations  
- **Pandas** – Data handling  
- **SciPy** – Optimization & statistics  
- **Matplotlib** – Plotting and visualization  

---
