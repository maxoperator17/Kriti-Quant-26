# Kritit-Quant-26

Welcome to the **Kriti-Quant-26** repository. This project contains a comprehensive quantitative trading framework, showcasing a proprietary trading strategy, its long-term backtesting results, forward testing analysis, and detailed performance documentation.

---

## 📂 Repository Structure

The repository is organized with the following key files:

| File Name | Description |
| :--- | :--- |
| **`2651_AMLR_strategy_final_QuantFinChallenge`** | The core python/notebook implementation containing the primary quantitative strategy. |
| **`2651_2020_2025_testing_QuantFiChallenge`** | Out-of-sample forward testing and validation script using asset data from 2020 to 2025. |
| **`2651_DocmenReport_QuantFinChallenge`** | Detailed methodology documentation explaining the logic, indicators, and mathematical formulation behind the strategy. |
| **`2651_PerformanceReport_QuantFinChallenge`** | Extensive performance breakdown including risk-adjusted metrics (Sharpe, Sortino, Drawdown, etc.). |
| **`Market data.txt`** | The underlying data dictionary or raw data source information utilized for calculations. |

---

## 📊 Strategy Timeline & Testing Pipeline

The model development followed a rigorous institutional-grade validation lifecycle divided into two distinct phases:

### 1. Strategy Backtesting (2010 – 2020)
* **Duration:** 10 Years
* **Focus:** Historical parameter optimization, indicator calibration, and regime testing across multiple market cycles (including the 2011 European Debt Crisis and the 2020 Market Crash).
* **Implementation:** Contained inside the final strategy pipeline file.

### 2. Forward / Out-of-Sample Testing (2020 – 2025)
* **Duration:** 5 Years
* **Focus:** Testing for overfitting and evaluating how the strategy adapts to post-pandemic market dynamics and high-inflation environments.
* **Implementation:** Located in the `2020_2025_testing` file.

---

## 🧠 Methodology Overview

The strategy leverages advanced statistical modeling and quantitative techniques. A brief summary of the process documented in the **Methodology Report**:
* **Feature Engineering:** Alpha generation through signal extraction.
* **Risk Management:** Dynamic stop-loss mechanism and position-sizing constraints to minimize maximum drawdowns.
* **Execution Simulation:** Factoring in realistic transaction costs and slippage parameters.

---

## 📈 Performance & Results

For a granular breakdown of the strategy's equity curve, monthly returns matrix, and benchmark comparisons (Alpha, Beta, Information Ratio), please refer directly to the **`2651_PerformanceReport_QuantFin...`** file.

---

## 🚀 Getting Started

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Akshat-Jain2005/Kriti-Quant-26.git](https://github.com/Akshat-Jain2005/Kriti-Quant-26.git)
