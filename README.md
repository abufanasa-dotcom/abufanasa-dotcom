## Ahmed Abufanas

Engineering Physics graduate and MSc student at the University of Oldenburg, Germany.

I work with **Python and MATLAB on energy systems, optimization, scientific data analysis, machine learning, acoustics, and signal processing**, with a focus on reproducible engineering workflows and data-driven technical problem solving.

My current portfolio focuses on **battery energy storage, electricity markets, renewable-energy analytics, industrial acoustics, measurement engineering, machine learning, and signal processing**.

## Selected Projects

### [WindConnect – Modbus TCP Monitoring and Fault Diagnostics](https://github.com/abufanasa-dotcom/windconnect)

Independent wind-turbine simulation with **real server-side Modbus TCP exchanges, rule-based fault diagnostics, and isolated bilingual (German/English) Streamlit sessions**.

Separately monitors **communication status, measurement validity, and data freshness**. Includes reproducible connection-loss, stale-data and invalid-measurement scenarios, recovery events, **66 passing automated tests**, genuine screenshots in both languages, and matched German/English technical terminology. All turbine measurements are synthetic; no real VPP integration, turbine control, or emsys connection.

**[Live dashboard (EN)](https://windconnect-monitoring.streamlit.app/?lang=English)** · **[Dashboard (DE)](https://windconnect-monitoring.streamlit.app/)**

**[Project overview](https://abufanasa-dotcom.github.io/en/projects/windconnect.html)** · **[Deutsche Projektvorstellung](https://abufanasa-dotcom.github.io/projects/windconnect.html)**

---

### [German BESS Dispatch & Degradation Analytics](https://github.com/abufanasa-dotcom/bess-dispatch-analytics)

Techno-economic analysis of a **1 MW / 2 MWh Battery Energy Storage System** operating in the German/Luxembourg day-ahead electricity market using validated SMARD data, battery physics, and **SciPy/HiGHS mixed-integer linear programming (MILP)**.

The project compares a price-blind baseline with perfect-foresight optimized dispatch and degradation-cost-sensitive operation. The nominal cycling-cost scenario reduced annual cycling by **32.44% EFC** while sacrificing only **5.26% of gross arbitrage margin** relative to the zero-cost optimizer. Includes DST-safe German market-day handling, independent physical replay, sensitivity analysis, **200 automated tests**, and a read-only Streamlit dashboard.

**[Live Demo](https://bess-dispatch-analytics.streamlit.app)**

---

### [German Day-Ahead Electricity Price Forecasting](https://github.com/abufanasa-dotcom/german-power-price-forecasting)

Leakage-aware machine-learning pipeline for German/Luxembourg day-ahead electricity-price forecasting and negative-price risk detection using **SMARD data, LightGBM, and Logistic Regression**.

The primary regression model achieved **26.87 EUR/MWh holdout MAE**, improving on 24-hour persistence by **17.91%**. The negative-price classifier achieved **84.12% recall** on the untouched final holdout. Model choices were frozen before holdout evaluation, with **71 automated tests** and an interactive Streamlit dashboard.

**[Live Demo](https://german-power-price-forecasting.streamlit.app)**

---

### [Wind Turbine Performance](https://github.com/abufanasa-dotcom/wind-turbine-performance)

Engineering analysis of wind-turbine operational data using **Python, machine learning, event screening, and power-performance modeling**.

A wind-speed and direction model reduced MAE by **13.14% versus the baseline** on the November–December evaluation period. The workflow also identifies persistent underperformance candidates while separating model-estimated energy gaps from confirmed operational faults.

**[Live Demo](https://abufanasa-dotcom-wind-turbine-performance-app-vtq3j5.streamlit.app/)**

---

### [Industrial Noise Exposure & Acoustic Quality Assessment](https://github.com/abufanasa-dotcom/industrial-noise-exposure)

Engineering analysis of historical **NIOSH workplace noise measurements** using reproducible data cleaning, occupational-noise exposure assessment, acoustic measurement QA, standards-aware comparison, and investigation-level robustness analysis.

The project analyzes **807 personal dosimetry measurements** and **582 area sound-level measurements**. Among **758 valid NIOSH analytical-dose records**, the median dose is **174.20%**, with **477 / 758 (62.93%)** at or above the documented 100% NIOSH dose criterion.

The workflow also compares NIOSH and OSHA dosimetry, validates extreme exposure measurements, separates personal and stationary area measurements, evaluates investigation-level replication, and provides a carefully scoped German occupational-noise context. Includes **89 automated tests** and a read-only Streamlit engineering dashboard.

**Live Demo:** Coming soon

---

### [Heart Sound Analysis](https://github.com/abufanasa-dotcom/heart-sound-analysis)

Acoustic signal-processing and machine-learning study using phonocardiogram recordings, engineered audio features, identity-grouped data splitting, and frozen held-out evaluation.

The project includes transparent performance reporting, confusion-matrix and class-level analysis, explicit limitations, reproducible methodology, and a presentation-only Streamlit dashboard. It is an engineering portfolio study and **not a diagnostic product**.

**[Live Demo](https://heart-sound-ml-analysis.streamlit.app)**

## Technical Skills

**Programming & Scientific Computing**  
Python · MATLAB · C++ · NumPy · pandas · SciPy

**Machine Learning & Data Analysis**  
scikit-learn · LightGBM · Feature Engineering · Regression · Classification · Time-Series Analysis · Model Validation

**Energy Systems & Optimization**  
Battery Energy Storage Systems (BESS) · Renewable Energy Analytics · Electricity Markets · MILP · SciPy/HiGHS · Energy-System Modeling

**Acoustics, Signal Processing & Measurement Engineering**  
Industrial Acoustics · Occupational Noise · Acoustic Signal Processing · Measurement Engineering · Acoustic QA · Spectral Analysis · Measurement Data Analysis · MATLAB/Simulink

**Visualization & Development**  
Streamlit · Matplotlib · Git · GitHub · LaTeX · Excel

## Current Focus

I am particularly interested in opportunities involving:

- Energy systems and battery storage
- Renewable-energy and power-system analytics
- Engineering and scientific data analysis
- Industrial acoustics and measurement engineering
- Scientific Python and machine learning
- Optimization and technical modeling
- Signal processing and measurement technology

## Contact

Based in **Oldenburg, Germany**. Open to **engineering, energy, acoustics, measurement, data, and technical analytics roles** and willing to relocate.

[LinkedIn](https://www.linkedin.com/in/ahmedabufanas/)
