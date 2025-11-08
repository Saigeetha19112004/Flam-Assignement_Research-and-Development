# Flam-Assignement_Research-and-Development
Assignment for Research and Development / AI
# 🧾 Parametric Curve Fitting Optimization

## 🎯 Objective
The objective of this assignment is to find the optimal values of the unknown parameters **θ (theta)**, **M**, and **X** in the following nonlinear parametric equations so that the resulting curve best fits the dataset `xy_data.csv`:

\[
x(t) = t\cos(\theta) - e^{M|t|}\sin(0.3t)\sin(\theta) + X
\]
\[
y(t) = 42 + t\sin(\theta) + e^{M|t|}\sin(0.3t)\cos(\theta)
\]

---

## 🧮 Problem Constraints

| Parameter | Description | Range |
|------------|--------------|-------|
| θ | Angle (in radians) | 0° < θ < 50° |
| M | Exponential Factor | -0.05 < M < 0.05 |
| X | X-Offset | 0 < X < 100 |
| t | Independent Variable | 6 < t < 60 |

---

## 📂 Files Included

| File | Description |
|------|--------------|
| `fit_parametric_curve.py` | Python script to perform parametric curve fitting |
| `xy_data.csv` | Input data file containing `(t, x, y)` values |
| `fitted_curve.png` | Output graph of fitted curve and data points |
| `report.tex` | LaTeX report containing theory, code, and results |
| `README.md` | This documentation file |

---

## ⚙️ Requirements

Install the required Python libraries before running the script:
Numpy, Pandas, Matplotlib, scipy, os, sys, math

## Output
theta = <value> rad  = <value> deg
M     = <value>
X     = <value>
SSE   = <value>
RMSE  = <value>


```bash
pip install numpy pandas scipy matplotlib
