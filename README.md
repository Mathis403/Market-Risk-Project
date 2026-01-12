# Market Risk – Quantitative Analysis Project

## Team

**Developed by:** Mathis Fourreau & Natacha Gaussin
**School:** ESILV - École Supérieure d'Ingénieurs Léonard de Vinci  
**Program:** 4th Year Financial Engineering (2025/2026)  
**Course:** Market Risk

## 📌 Project Overview

This repository contains a **Market Risk project** developed during the **2025–2026 academic year** at **ESILV (De Vinci Engineering School)**.  
The project focuses on **quantitative risk measurement**, **extreme value theory**, and **market microstructure**, using real financial datasets and numerical methods implemented in **Python (Jupyter Notebook)**.

---

## 🎯 Objectives

The goal of this project is to:
- Estimate and validate **risk measures** (VaR, Expected Shortfall)
- Analyze **tail risk** using Extreme Value Theory (EVT)
- Study **price impact models** in market microstructure
- Investigate **multi-scale correlations** and the **Epps effect**
- Estimate **Hurst exponents** and long-range dependence in FX markets

---

## 🧠 Project Structure & Methods

### 1️⃣ Non-Parametric Value at Risk (VaR)
- Historical VaR estimation on Natixis stock returns
- **Kernel Density Estimation (Biweight kernel)**
- Bandwidth selection (Scott & Silverman rules)
- Backtesting on out-of-sample data (2017–2018)

📌 Key focus: robustness of non-parametric VaR and sensitivity to bandwidth choice.

---

### 2️⃣ Expected Shortfall (ES)
- Empirical estimation of ES at fixed confidence levels
- Comparison with VaR
- Interpretation of tail risk beyond the VaR threshold

---

### 3️⃣ Extreme Value Theory (EVT)
- Tail modeling using **Pickands estimator**
- Separate analysis of gains and losses
- Estimation of **GEV tail indices**
- EVT-based VaR for extreme confidence levels

📌 Result: asymmetry between gain and loss tails (Fréchet vs Weibull behavior).

---

### 4️⃣ Market Microstructure – Bouchaud Price Impact Model
- Estimation of:
  - Impact kernel \( G(\ell) \)
  - Volume exponent \( r \)
- Log–log regression and power-law behavior
- Model calibration via **least squares minimization**
- Comparison between observed and model-implied prices

📌 Discussion on model specification and limitations due to data size.

---

### 5️⃣ Wavelet Multi-Scale Correlations & Epps Effect
- Haar wavelet decomposition
- Multi-resolution correlation between FX rates:
  - GBPEUR
  - SEKEUR
  - CADEUR
- Empirical analysis of the **Epps effect**
- Interpretation of frequency-dependent correlations

---

### 6️⃣ Long Memory & Volatility Scaling
- Estimation of **Hurst exponents**
- Detection of long-range dependence
- Annualized volatility scaling using Hurst-adjusted formulas


## 📂 Repository Content

