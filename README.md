# Giacomo Papa

**Quantitative Analyst** — Mathematical Engineering · FX Derivatives


I hold an MSc in Mathematical Engineering with a specialization in Quantitative Finance from Politecnico di Milano, and professional experience at **Murex** (Paris), where I worked on the pricing and lifecycle management of FX derivatives, cross-currency swaps, non-deliverable forwards, interest rate swaps, on the MX.3 platform.

My background spans the full spectrum from rigorous mathematical modeling to hands-on implementation. I am equally comfortable deriving a pricing model from first principles, building a numerical simulation, or integrating a quantitative framework into a production system.

I have a strong inclination toward experimentation particularly at the intersection of classical quantitative finance and modern machine learning. My personal projects reflect a consistent interest in pushing standard methodologies further: applying Hidden Markov Models for regime detection, exploring Kalman filtering for dynamic factor estimation, and incorporating ensemble methods and shrinkage estimators where classical approaches fall short. I actively explore deep learning architectures in the context of financial time series, signal generation, and feature extraction.

---

## Projects

### Systematic Equity System (Python)
A modular, research-grade pipeline for systematic equity investing built across three interconnected components:
- **Walk-forward optimizer** — portfolio scoring via a composite metric (Sharpe, Calmar, Win Rate, Profit Factor) with HMM-based market regime classification and cached pre-fitting for computational efficiency
- **Daily decision engine** — Kelly-criterion position sizing integrated with a fundamental score multiplier
- **Fundamental analyzer** — multi-factor scoring across corporate health, valuation, growth, and macro regime, structured over five discrete states

### Black-Box Index Replication
Dynamic replication of an undisclosed benchmark using a **Kalman Filter** initialized with Ridge regression coefficients, ensembled with a **James-Stein shrinkage** estimator. The system incorporates a pairs trading overlay and was developed as part of a FinTech course at Politecnico di Milano.

### Asset Allocation Study
Systematic comparison of **16 portfolio construction methodologies**: Markowitz mean-variance, resampling, Black-Litterman, maximum diversification, maximum entropy, PCA-based dimensionality reduction, and VaR-adjusted approaches — evaluated across a consistent set of risk-adjusted return metrics.


## Background

- MSc Mathematical Engineering — Quantitative Finance · Politecnico di Milano  
- Product & Expertise Specialist · Murex, Paris — FX Derivatives, XCS, IRS on MX.3  
- Based in Milan
