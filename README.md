# 🏡 Melbourne Housing Market Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-E97627?style=for-the-badge&logo=tableau)

## 📌 Overview

This project is an **Exploratory Data Analysis (EDA)** of the Melbourne housing market. The goal was to uncover key factors influencing property prices, identify high-growth suburbs, and visualize market trends to assist potential investors or homebuyers in making data-driven decisions.

The analysis processes over **18,000+ property records**, handling data cleaning, statistical correlation, and interactive dashboarding.

### 🎯 Key Objectives
- Identify the correlation between **Price** and features like **Distance from CBD**, **Rooms**, and **Land Size**.
- Analyze the distribution of property sales across different regions.
- Visualize the data using **Tableau** for interactive insights.

---

## 📊 Dashboard Preview

*(Interactive dashboard built with Tableau)*

![Tableau Dashboard](./screenshot/SS%20Dashboard.jpeg)

> **[Download / View Tableau Workbook (.twbx)](./Dashboard.twbx)**

---

## 🛠 Tech Stack & Tools

* **Language:** Python (Jupyter Notebook)
* **Libraries:**
    * `Pandas` & `NumPy` (Data Manipulation)
    * `Matplotlib` & `Seaborn` (Static Visualizations)
    * `Scikit-learn` (Basic preprocessing)
* **Visualization Tool:** Tableau Public / Desktop
* **Presentation:** [View Analysis Presentation PDF](./presentation/Presentation.pdf)

---

## 🔍 Key Insights

Based on the analysis performed in `Melbourne Property Analysis.ipynb`:

1.  **Distance Matters:** There is a strong negative correlation between distance from the Central Business District (CBD) and property price. Properties closer to the city center command significantly higher premiums.
2.  **Room Count:** The number of rooms is one of the strongest predictors of price, more so than land size in certain dense suburbs.
3.  **Regional Trends:** The "Southern Metropolitan" region exhibits the highest median prices, while the "Western Metropolitan" offers more affordable entry points for first-time buyers.

---

## 📂 Project Structure

```text
├── dataset/
│   └── Property Sales of Melbourne City.csv  # Raw dataset
├── presentation/
│   └── Presentation.pdf                      # Summary slide deck
├── screenshot/
│   └── SS Dashboard.jpeg                     # Dashboard preview image
├── Dashboard.twbx                            # Tableau workbook file
├── Melbourne Property Analysis.ipynb         # Main analysis notebook
└── README.md                                 # Project documentation
```

## 🚀 How to Run

### Prerequisites
Make sure you have Python installed along with Jupyter Notebook.

### Installation
1. Clone this repository:
```bash
git clone [https://github.com/kochenkexe/melbourne-property-analysis.git](https://github.com/kochenkexe/melbourne-property-analysis.git)
```

2. Install required packages:
```
pip install pandas seaborn matplotlib jupyter
```

3. Open the notebook:
```
jupyter notebook "Melbourne Property Analysis.ipynb"
```
