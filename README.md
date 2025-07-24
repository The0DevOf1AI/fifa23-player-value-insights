# FIFA 23 Player Analysis

A clean, interactive dashboard to explore player wages vs values in FIFA 23 using **Pandas**, **Seaborn**, and **Bokeh**.

---

## 🧠 Overview

1. **Data Loading** – Reads in `fifa23.csv` with Pandas.
2. **Data Cleaning** – Strips currency symbols (€, K, M); converts to float.
3. **New Columns** – Creates `Value_clean`, `Wage_clean`, and `Wage_minus_Value`.
4. **Exploratory Analysis** – Uses Seaborn for static distribution and scatter plots.
5. **Interactive Visualization** – Builds a Bokeh scatter plot with hover tooltips.

## 🔍 Requirements
1. Python 3.8+
2. numpy, pandas, seaborn
3. bokeh>=3.0 (uses width/height, not deprecated plot_width)
4. (optional) jupyter for notebooks
