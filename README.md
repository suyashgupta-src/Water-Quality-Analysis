# 💧 Water Quality Analysis & Potability Assessment

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-3F4F75?style=for-the-badge&logo=plotly)

## 📌 Project Overview

Water quality plays a crucial role in determining whether water is safe for human consumption. This project performs **Exploratory Data Analysis (EDA)** on the **Water Potability Dataset** to understand how various physicochemical properties influence the potability of water.

The analysis includes data cleaning, handling missing values, visualizing feature distributions, and comparing water quality parameters for potable and non-potable water using interactive and statistical visualizations.

---

## 🎯 Objectives

- Understand the characteristics of potable and non-potable water.
- Perform data cleaning and preprocessing.
- Analyze the distribution of water quality parameters.
- Identify patterns affecting water potability.
- Create informative visualizations for better insights.

---

## 📂 Dataset

The dataset contains water quality measurements collected from different water samples.

### Features

| Feature | Description |
|----------|-------------|
| pH | Acidic or alkaline nature of water |
| Hardness | Concentration of calcium and magnesium |
| Solids | Total dissolved solids (TDS) |
| Chloramines | Disinfectant concentration |
| Sulfate | Sulfate content in water |
| Conductivity | Electrical conductivity |
| Organic_carbon | Organic carbon concentration |
| Trihalomethanes | Chlorination by-products |
| Turbidity | Suspended particles in water |
| Potability | Target variable (0 = Not Potable, 1 = Potable) |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly Express
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The notebook includes the following analyses:

### ✔ Data Cleaning

- Imported the dataset
- Removed missing values
- Verified null values

---

### ✔ Distribution of Potability

A count plot is used to visualize the distribution of potable and non-potable water samples.

**Observation**

- The dataset is slightly imbalanced.
- Non-potable samples are more frequent than potable samples.

---

### ✔ Feature-wise Distribution Analysis

Histograms are created for the following water quality parameters:

- pH
- Hardness
- Total Dissolved Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

Interactive visualizations are generated using **Plotly Express** for better exploration of the data.

---

## 📈 Key Insights

- The dataset contains both potable and non-potable water samples.
- Missing values are removed before analysis.
- Water quality parameters show varying distributions between potable and non-potable water.
- The dataset is not perfectly balanced.
- Visual analysis helps identify important trends and relationships among water quality indicators.

---

## 📁 Project Structure

```
Water-Quality-Analysis/
│
├── Quality_Analysis.ipynb
├── water_potability.csv
├── README.md
└── .gitignore
```

---

## ▶️ Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/Water-Quality-Analysis.git
```

### Navigate to the project folder

```bash
cd Water-Quality-Analysis
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly
```

### Run the notebook

```bash
jupyter notebook
```

Open:

```
Quality_Analysis.ipynb
```

---

## 📸 Visualizations

The notebook contains:

- Count Plot
- Interactive Histograms
- Distribution Analysis
- Data Cleaning Workflow

---

## 🚀 Future Improvements

- Feature correlation analysis
- Box plots and pair plots
- Outlier detection
- Machine Learning model for water potability prediction
- Feature importance analysis
- Dashboard using Streamlit

---

## 👨‍💻 Author

**Suyash Gupta**

- GitHub: https://github.com/suyashgupta-src
- LinkedIn: *https://www.linkedin.com/in/suyash-gupta-a3131431a?utm_source=share_via&utm_content=profile&utm_medium=member_android*

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
