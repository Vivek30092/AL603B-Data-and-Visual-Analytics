# 📊 Data and Visual Analytics — Lab File (AL-605)

> **B.Tech Lab Assignment Repository | Semester VI**  
> _All experiments, datasets, and reports for the Data and Visual Analytics (DVA) course._

---

## 🎓 Student Information

| Field              | Details                        |
|--------------------|--------------------------------|
| **Name**           | Vivek Kumar Choudhary          |
| **Enrollment No.** | 0873AL231027                   |
| **Course Code**    | AL-605                        |
| **Course Name**    | Data and Visual Analytics      |
| **College**        | Sri Aurobindo Institute of Technology,Indore|
| **University**     | Rajiv Gandhi Proudyogiki Vishwavidyalaya,Bhopal|
| **Semester**       | VI (Sixth)                     |

---

## 📁 Repository Structure

```
AL603B-Data-and-Visual-Analytics/
│
├── 📓 01_Exp01.ipynb               # Experiment 1  — EDA on Car Dekho Dataset
├── 📓 02_Exp_housingEDA.ipynb      # Experiment 2  — EDA on Housing Dataset
├── 📓 03_Exp03.ipynb               # Experiment 3  — EDA on Income Dataset
├── 📓 04_Exp04.ipynb               # Experiment 4  — Analysis of Superstore USA Dataset
├── 📓 wineQuality_EDA.ipynb        # Bonus EDA     — Red Wine Quality Analysis
│
├── 📄 05_Exp05_studyPowerBI.docx   # Experiment 5  — Study of Power BI (Word Report)
├── 📄 05_Exp05_studyPowerBI.pdf    # Experiment 5  — Study of Power BI (PDF Report)
│
├── 📂 print/                       # Printable PDF versions of all experiments
│   ├── DVA_Exp01.pdf
│   ├── DVA_Exp02.pdf
│   ├── DVA_Exp03.pdf
│   └── DVA_Exp04.pdf
│
├── 🗃️ cardekho_dataset.csv         # Dataset: Used Car Prices (CarDekho)
├── 🗃️ Housing.csv                  # Dataset: Housing Prices
├── 🗃️ income-dataset.csv           # Dataset: Census Income (Adult Dataset)
├── 🗃️ Superstore_USA.csv           # Dataset: USA Retail Superstore Sales
│
└── README.md                       # This file
```

---

## 🧪 Experiments Overview

### Experiment 1 — EDA on CarDekho Dataset
**File:** `01_Exp01.ipynb` | **Dataset:** `cardekho_dataset.csv`

Performs **Exploratory Data Analysis (EDA)** on a real-world used-car dataset from CarDekho.com. Key tasks include:
- Loading and inspecting data (shape, dtypes, null values)
- Univariate and bivariate analysis using `matplotlib` and `seaborn`
- Correlation heatmap and distribution plots
- **Predictive Analysis** using Linear Regression (`sklearn`) to predict car prices
- Model evaluation using MAE, MSE, and R² Score

**Key Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

### Experiment 2 — EDA on Housing Dataset
**File:** `02_Exp_housingEDA.ipynb` | **Dataset:** `Housing.csv`

In-depth exploratory analysis on a housing prices dataset. Covers:
- Dataset overview: `.info()`, `.describe()`, missing value treatment
- Feature distribution and outlier detection
- Correlation analysis between housing features (area, bedrooms, bathrooms, price, etc.)
- Visualizations: Histograms, boxplots, pairplots, and heatmaps

**Key Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---

### Experiment 3 — EDA on Income/Census Dataset
**File:** `03_Exp03.ipynb` | **Dataset:** `income-dataset.csv`

Analysis of the **UCI Adult Census Income dataset**, answering key analytical questions:
- Identifying key attributes and data types
- Handling missing values and categorical encoding
- Analysis of factors affecting income (`>50K` vs `<=50K`)
- Visualizations of age, education, occupation, gender vs income distribution

**Key Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---

### Experiment 4 — Superstore USA Sales Analysis
**File:** `04_Exp04.ipynb` | **Dataset:** `Superstore_USA.csv`

Business intelligence-style analysis on a US retail superstore dataset:
- Sales, profit, and discount trend analysis
- Region-wise and category-wise performance breakdown
- Identifying top/bottom performing products and customers
- Visual dashboards using bar charts, pie charts, and line plots

**Key Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---

### Experiment 5 — Study of Power BI
**Files:** `05_Exp05_studyPowerBI.docx` / `.pdf`

A comprehensive written report on **Microsoft Power BI**, covering:
- Introduction to Business Intelligence (BI) tools
- Power BI architecture and components
- Creating dashboards, reports, and visualizations
- Connecting data sources and DAX basics

---

### Bonus — Red Wine Quality EDA
**File:** `wineQuality_EDA.ipynb`

EDA performed on the **Vinho Verde Red Wine Dataset** (Portuguese wine):
- Physicochemical properties analysis (acidity, sugar, alcohol, pH, etc.)
- Quality score distribution
- Correlation between features and wine quality
- Visualizations: Histograms, heatmaps, boxplots

---

## 🛠️ Technologies & Tools Used

| Tool / Library   | Purpose                              |
|------------------|--------------------------------------|
| Python 3.x       | Core programming language            |
| Jupyter Notebook | Interactive coding environment       |
| Pandas           | Data loading, cleaning, manipulation |
| NumPy            | Numerical operations                 |
| Matplotlib       | Static data visualization            |
| Seaborn          | Statistical data visualization       |
| Scikit-learn     | Machine learning / regression models |
| Microsoft Power BI | Business Intelligence dashboards   |

---

## 🚀 How to Run the Notebooks

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Vivek30092/AL603B-Data-and-Visual-Analytics.git
   cd AL603B-Data-and-Visual-Analytics
   ```

2. **Install required Python packages:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. Open any `.ipynb` file and run all cells (`Cell → Run All`).

> **Note:** All datasets (`.csv` files) are included in the root directory — no separate download needed.

---

## 📄 PDF Lab Reports

Printable/submittable PDF versions of all experiments are available in the [`print/`](./print/) folder:

| File              | Experiment                      |
|-------------------|---------------------------------|
| `DVA_Exp01.pdf`   | EDA — CarDekho Dataset          |
| `DVA_Exp02.pdf`   | EDA — Housing Dataset           |
| `DVA_Exp03.pdf`   | EDA — Income/Census Dataset     |
| `DVA_Exp04.pdf`   | Analysis — Superstore USA       |

---

## 🏫 About

This repository contains the complete **Lab File** for the subject **Data and Visual Analytics (AL-603B)**, submitted as part of the **B.Tech (Artificial Intelligence)** curriculum at:

> **SAIT — Shri Aurobindo Institute of Technology, Indore**  
> Affiliated to **RGPV — Rajiv Gandhi Proudyogiki Vishwavidyalaya, Bhopal**

---

## 🔍 Keywords

`Data Analytics Lab File` · `Visual Analytics` · `AL-603B` · `RGPV Lab File` · `SAIT Indore` · `B.Tech AI Lab` · `EDA Python` · `Jupyter Notebook Lab` · `Data and Visual Analytics RGPV` · `DVA Lab File` · `AL603B RGPV` · `Data Science Lab RGPV Bhopal` · `Vivek Kumar Choudhary` · `0873AL231027`

---

<div align="center">
  <sub>Made with ❤️ by <strong>Vivek Kumar Choudhary</strong> | Enrollment: 0873AL231027 | SAIT, Indore | RGPV, Bhopal</sub>
</div>
