# Renewable Energy Generation Analysis

A data analysis project focused on understanding renewable energy production patterns across Indian states using generation and capacity data.

---

- [Project Overview](#-project-overview)
- [Data Source](#️-data-source)
- [Tools & Technologies](#️-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#️-how-to-use)

---

## 📊 Project Overview

This project analyzes renewable energy generation across different regions and states in India. The dataset includes information about power stations, energy types (Solar, Wind, Hybrid), generation capacity, and actual energy produced.

The objective of this project is to evaluate renewable energy performance by comparing installed capacity with actual generation. The analysis examines regional patterns, seasonal variations, and operational efficiency to understand how effectively renewable energy infrastructure is utilized.

---

## 🗂️ Data Source

The dataset used in this project was independently selected for renewable energy analysis.

**Dataset Details**

- Source: Public renewable energy dataset
- Link:https://catalog.data.gov/dataset/electric-vehicle-population-data
- File Format: Excel (.xlsx)
- Dataset Size: ~10–15 MB
- Total Records: 200,235
- Records Used for Analysis: 100,903

**Key Variables**

- Energy_ID
- Date
- State_Name
- Region
- Station_ID
- Station_Name
- Sector
- Owner
- Energy_Type
- Installed_Capacity
- Actual_Generation
- Efficiency
- Solar_Park

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- Power BI
- Data Modeling (Star Schema)
- DAX for calculated measures
- Markdown for documentation

---

## 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed to ensure data quality and consistency.

- Cleaned **Energy_ID** using `CLEAN()` and `TRIM()` functions.
- Converted **Date column** into proper Date format.
- Standardized **State_Code** using `CLEAN()` and `TRIM()`.
- Cleaned **State_Name** to remove extra spaces and formatting inconsistencies.
- Standardized **Region** column values.
- Cleaned **Solar_Park** column values.
- Standardized **Station_ID** using `CLEAN()` and `TRIM()`.
- Cleaned **Station_Name** values.
- Standardized **Sector** values (Central, State, Private).
- Cleaned **Owner** column values.
- Standardized **Energy_Type** values (Solar, Wind, Hybrid).
- Converted **Installed_Capacity** and **Actual_Generation** into numeric data types.
- Removed negative values in **Actual_Generation** as anomalies.
- Created a **Season column** derived from Date.
- Calculated **Efficiency** to measure generation performance.

---

## 🔍 Exploratory Data Analysis (EDA)

Key analytical questions explored in this project include:

- How does renewable energy generation vary across different states?
- Which energy type contributes the most to total generation?
- How efficiently are stations utilizing installed capacity?
- What seasonal patterns influence renewable energy generation?
- Which companies and sectors generate the highest renewable energy output?

---

## 💡 Key Insights

- Renewable energy generation has increased significantly across multiple regions.
- Solar and wind energy contribute the largest share of renewable power production.
- Private sector companies play a major role in renewable energy generation.
- Seasonal patterns significantly affect renewable energy output.
- Some power stations show lower efficiency relative to their installed capacity.

---

## 🚀 Recommendations

- Improve operational efficiency for stations with low generation performance.
- Increase investment in high-performing renewable energy sectors.
- Monitor seasonal generation trends to improve energy grid stability.
- Encourage renewable infrastructure development in lower-performing regions.
- Conduct regular monitoring of station-level efficiency.

---

## ⚙️ How to Use

## Download or Clone the Repository

Clone the project repository using Git:

```bash
git clone https://github.com/saranyasubramaniam9787-ship-it/Renewable-energy-generation-Analysis.git
```

Or download the repository as a ZIP file from GitHub.

---

## Open the Project Folder

Project structure:

```
renewable-energy-generation-analysis/
│
├── Renewable_Energy_Dashboard.pbix
├── data/
│   └── renewable_energy_dataset.xlsx
├── docs/
│   └── Project_Documentation.pdf
└── README.md
```
---

## Install Required Software

Make sure you have installed:

- Microsoft Power BI Desktop
- Microsoft Excel

## Open the Power BI Dashboard

1. Open **Power BI Desktop**
2. Click **File → Open**
3. Select:

```
Renewable_Energy_Dashboard.pbix
```
## Refresh the Dataset

1. Go to **Home**
2. Click **Refresh**
3. Ensure the dataset path is correctly linked to:

```
renewable_energy_dataset.xlsx
```



