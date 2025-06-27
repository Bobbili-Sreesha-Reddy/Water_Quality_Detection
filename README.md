# 💧 Water Quality Analysis

This project analyzes the potability of water samples using physicochemical properties. The goal is to explore which factors influence whether water is safe for drinking.

## 📂 Dataset Overview

The dataset (`water_potability.csv`) includes the following columns:

- **ph** — pH level of the water
- **Hardness** — Hardness in mg/L
- **Solids** — Total dissolved solids (ppm)
- **Chloramines** — Chloramine concentration (ppm)
- **Sulfate** — Sulfate concentration (mg/L)
- **Conductivity** — Electrical conductivity (μS/cm)
- **Organic_carbon** — Organic carbon content (ppm)
- **Trihalomethanes** — Trihalomethane concentration (μg/L)
- **Turbidity** — Turbidity (NTU)
- **Potability** — 1 if safe to drink, 0 if not

## 🛠️ Project Workflow

1. **Data Loading**
   - Read the dataset into a Pandas DataFrame.
   - Display dataset shape and column names.
2. **Data Exploration**
   - Preview the first few rows.
   - Check for missing or inconsistent values.
3. **Visualization**
   - Use Seaborn and Matplotlib to:
     - Plot feature distributions
     - Create correlation heatmaps
     - Compare potable vs. non-potable samples
4. *(Optional)* **Modeling**
   - You can extend this notebook to include machine learning models for classification.

## ✨ Improvements Made

This notebook was improved by:
- Structuring the workflow into clear sections for easier understanding.
- Adding print statements to clarify dataset structure and contents.
- Creating this README to document the project purpose, tools, and suggested next steps.

## 🔧 Technologies Used

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

## 🚀 How to Run

1. Make sure you have Python installed.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
