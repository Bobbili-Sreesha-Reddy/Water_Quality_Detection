# 💧 Water Quality Analysis

This project analyzes the potability of water samples using physicochemical properties. The goal is to explore which factors influence whether water is safe for drinking.

---

## ❗ Problem Statement

* Clean drinking water is crucial for maintaining public health.
* Water quality depends on various physicochemical properties like pH, hardness, turbidity, etc.
* Not all sources of water meet safety standards for potability.
* The dataset provides samples labeled as potable or not, based on multiple water quality features.
* The objective is to analyze these features to understand what affects potability.
* Insights from this analysis can help in identifying unsafe water and guiding predictive modeling efforts.

---

## 📌 Methodology

* Loaded the `water_potability.csv` dataset using Pandas.
* Performed initial data inspection to understand structure and identify missing values.
* Conducted exploratory data analysis using visualizations to examine feature distributions and relationships.
* Used correlation analysis to find key factors affecting potability.
* Generated insights to support future predictive modeling.

---

## ✅ Solution

* Loaded and explored the water potability dataset.
* Identified and reviewed missing values.
* Used Seaborn and Matplotlib for visual analysis.
* Found key influencing features through correlation.
* Built the foundation for a predictive modeling web app.

---

## 🎯 Learning Objectives

* Understand and interpret a real-world environmental dataset.
* Perform data cleaning and exploratory analysis using Pandas and visualization libraries.
* Identify key features affecting water potability through correlation and comparative analysis.
* Organize your analysis in a clear and structured format.
* Prepare the project for integration with machine learning and web deployment.

---

## 🧰 Tools and Technologies Used

* **Python 3.x** – Programming language
* **Pandas** – Data manipulation
* **Matplotlib** – Basic plotting and charts
* **Seaborn** – Advanced statistical visualizations
* **Jupyter Notebook / VS Code** – Development environment
* **CSV File Format** – Input data file
* **Flask** – Web framework for deploying the model

---

## 🚀 How to Run the Flask Application

1. **Clone the Repository**

```bash
git clone https://github.com/YourUsername/Water-Quality-Prediction.git
```

2. **Navigate to Project Directory**

```bash
cd Water-Quality-Prediction
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the Flask App**

```bash
python app.py
```

5. **Access the Application**
   Open your browser and go to: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

6. **Input Water Quality Parameters**
   Fill in the form fields for pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity.

7. **Submit the Form**
   Click on "Predict Potability" to view the result.

8. **Explore Results**
   The app will display whether the water is **Potable** or **Not Potable** based on the input.

---

## ✨ Improvements Made

* Structured the notebook into clearly defined sections.
* Added print statements for better data visibility.
* Created a complete and professional README to improve project documentation and usability.

---

## 📝 Conclusion

* The project reveals key features that influence whether water is safe to drink.
* Data visualization and correlation analysis provided meaningful insights.
* The model and Flask app demonstrate a practical application of machine learning in public health.
* This project highlights how data science can be used to address real-world environmental challenges.

Feel free to explore and contribute to enhance the project further.
