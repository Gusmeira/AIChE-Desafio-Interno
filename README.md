# 🧪 Python for Chemical Engineering
**Author:** Gustavo J. V. Meira Filho  
**Language:** Python 3.x  
**Libraries:** NumPy • Pandas • Plotly • Matplotlib • Seaborn  

---

## 🎯 Overview
This repository contains a three-part introductory course designed for **engineering and data-science applications**.  
It progresses from the **fundamentals of Python programming** to **data manipulation and visualization**, and finally to **mathematical modeling, regression, and optimization** using linear algebra.

Each lesson builds toward real engineering problems — from **unit conversions** to **data analysis of the periodic table**, and finally **curve fitting and optimization**.

---

## 📘 Course Structure

### 🧩 **01 – Units Conversion**
**Objective:** Introduce Python syntax, logic, and function creation while applying it to unit conversions.

**Topics covered:**
- Variables, data types (`int`, `float`, `str`, `list`, `dict`)
- Operators, conditionals (`if`, `elif`, `else`)
- Loops (`for`, `while`)
- Functions and modularization
- Dictionaries and lists
- Building a **mini unit converter**:
  - Pressure: `atm ↔ Pa ↔ mmHg`
  - Temperature: `K ↔ °C ↔ °F`
  - Volume: `L ↔ m³ ↔ mL`
  - Energy: `J ↔ cal ↔ eV`
- Applying conversions in chemical equations (e.g., ideal gas law `PV = nRT`)
- Introduction to **pint** library for physical units

**Key file:** `01_Units_Conversion.pdf`

---

### 🧬 **02 – Periodic Table Data Analysis**
**Objective:** Explore **data manipulation** and **visualization** using real datasets.

**Topics covered:**
- Introduction to **pandas** for data handling
  - Importing and exploring CSV data
  - Filtering, sorting, grouping, and handling missing values
  - Calculated columns and pivot tables
- **Data cleaning** and preprocessing for analysis
- Visualization using **plotly** and **matplotlib**:
  - Scatter plots
  - Bar charts
  - Boxplots
  - Heatmaps
- Exploratory analysis of chemical properties:
  - Atomic weight, density, melting/boiling points
  - Periodic trends and property correlations

**Key file:** `02_Periodic_Table.pdf`

---

### 📈 **03 – Linear Regression and Optimization**
**Objective:** Introduce **data modeling** and **optimization** through linear algebra and numerical methods.

**Topics covered:**
- Mathematical foundation of regression:
  - Linear model:  `ŷ = a·x + b`
  - Normal Equation: `θ = (XᵀX)⁻¹Xᵀy`
  - Pseudoinverse and matrix invertibility
- Implementation of regression **from scratch** using **NumPy**
- Functions for:
  - Linear regression
  - Polynomial regression
  - Multiple regression (3D visualization)
- Metrics of model performance:
  - MAE, MSE, RMSE, (and optionally R²)
- Introduction to **Gradient Descent**:
  - Stochastic (SGD) and Batch versions
  - Visualization of convergence
- Theoretical link between regression and **neural networks**

**Key file:** `03_Linear_Regression.pdf`

---

## ⚙️ Installation and Setup

1. **Clone this repository**
   ```bash
   git clone https://github.com/Gusmeira/AIChE-Desafio-Interno.git
   cd AIChE-Desafio-Interno
