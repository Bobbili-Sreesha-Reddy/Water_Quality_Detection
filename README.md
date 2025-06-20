# 💧 Water Quality Analysis

This project analyzes water potability using physicochemical features from the `water_potability.csv` dataset. The goal is to understand which water properties impact its safety for human consumption.

## 📂 Dataset Description

The dataset contains the following columns:

- **ph**: pH level of the water
- **Hardness**: Water hardness in mg/L
- **Solids**: Total dissolved solids (TDS) in ppm
- **Chloramines**: Chloramines concentration in ppm
- **Sulfate**: Sulfate concentration in mg/L
- **Conductivity**: Conductivity of water in μS/cm
- **Organic_carbon**: Organic carbon concentration in ppm
- **Trihalomethanes**: Trihalomethanes concentration in μg/L
- **Turbidity**: Turbidity in NTU
- **Potability**: Binary indicator (1 = safe to drink, 0 = not safe)

## 🧪 Project Workflow

1. **Data Loading**  
   Read the CSV file into a Pandas DataFrame.

2. **Data Exploration**  
   Inspect dataset shape, column names, and initial rows.

3. **Missing Value Handling** *(to be added if needed)*  
   Identify and impute/remove null values.

4. **Visual Analysis**  
   Use `seaborn` and `matplotlib` to:
   - Plot distributions of each feature
   - Compare feature distributions between potable and non-potable samples
   - Analyze correlations using a heatmap


## 🔧 Tech Stack

- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook / VS Code

## 🚀 How to Run

1. Clone this repository or download the files.
2. Make sure `water_potability.csv` is in the same folder.
3. Open `Water_Quality.ipynb` using Jupyter Notebook or VS Code.
4. Run all cells to explore data and generate visualizations.

## 📌 Future Improvements

- Add ML models to predict water potability
- Clean missing data more robustly
- Build a dashboard using Streamlit or Flask

## 📊 Sample Visualization

*Histograms, heatmaps, and comparative boxplots are generated to understand feature impact.*

---

