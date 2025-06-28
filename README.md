# Quant Finance Bootcamp Projects

Welcome to my Quant Finance Bootcamp portfolio! This repo contains a collection of projects where I explore real-world quantitative finance topics through simulations, statistical analysis, and interactive visualizations—all built in Python.

Each project progressively builds on financial theory, programming, and data analysis. From portfolio construction to options pricing and hedging strategies, this bootcamp was a deep dive into the mechanics of modern quantitative trading and risk management.

---

## Projects Overview

### Project 1: Risk-Based Portfolio Construction

**Goal:** Create two portfolios—one low-risk and one high-risk—using real-time stock data.

- Low-Risk: 10 S&P 100 stocks with low volatility and minimal covariance.
- High-Risk: Single-asset Tesla portfolio.
- Built with Python and yfinance.

**Key Concepts:**  
*Covariance matrices, portfolio weighting, volatility*

---

### Project 2: Hypothesis Testing of Log-Returns

**Goal:** Test whether daily log-returns are normally distributed for:

1. Major stock indices  
2. The low-risk portfolio (from Project 1)

- Classical tests (Shapiro-Wilk, Anderson-Darling) rejected normality.
- Developed custom tests:
  - **Sliding Window Test**
  - **Outlier Removal Test**

**Key Concepts:**  
*Statistical testing, normality assumptions in finance, custom test design*

---

### ⚙Project 3: Black-Scholes Option Pricing

**Goal:** Visualize how Black-Scholes option prices evolve over time and with varying spot prices.

- Discovered interesting geometric behaviors:
  - Call prices form **hyperbolic** shapes as spot varies
  - Call and put prices are vertically shifted reflections over time
- Interactive plots using `matplotlib` and `ipywidgets`
- Greeks derived from BS formula

**Key Concepts:**  
*Black-Scholes model, Greeks, geometric Brownian motion, 3D visualizations*

---

### Project 4: Delta Hedging with the Heston Model

**Goal:** Test how well a Black-Scholes Delta hedge performs under the Heston stochastic volatility model.

- Simulated the Heston model using Monte Carlo
- Applied a BS-based Delta hedge and tracked performance
- Found BS Deltas can still hedge well under stochastic volatility

**Key Concepts:**  
*Stochastic calculus, Heston model, Monte Carlo simulation, Delta hedging*

---

### 🎥 Bonus: Interactive Hedging Animation App

**Goal:** Help users visualize how Delta hedging works in real-time.

- Fully customizable (number of hedges, model parameters)
- Animated app simulates how stock and liquid positions evolve during a hedge
- Built as an educational tool

**Key Concepts:**  
*Python animations, Black-Scholes dynamics, user interactivity, financial intuition*

---

## Technologies Used

- Python
- NumPy, Pandas
- yfinance
- Matplotlib, Seaborn
- ipywidgets
- Scipy (for statistical tests)
- Object-oriented programming
- Monte Carlo simulation

---

## What I Learned

- Core statistical methods in financial data
- The mechanics of option pricing and hedging
- Model implementation (GBM, Heston)
- Interactive and visual Python design
- How to turn theory into insight

---

## Contact

**Alex Glickfield**  
Open to collaboration & research opportunities in quantitative finance and applied math.  
📫 [LinkedIn](https://www.linkedin.com/in/alexglickfield/) | ✉️ alexglickfield@gmail.com
