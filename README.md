# 🌍 COVID-19 Global Trends Analysis

A data analysis project to track global COVID-19 trends — including cases, deaths, and vaccinations — using Python, Pandas, and Seaborn.

## 📝 Project Description

In this project, we analyze **real-world COVID-19 data** to explore how the pandemic evolved globally, with a focus on **Kenya**, **USA**, and **India**.  
We generate insights, create visualizations, and summarize findings in a clear and interactive notebook.

## 🚀 Project Objectives

- ✅ Import and clean COVID-19 global data  
- ✅ Analyze time trends (cases, deaths, vaccinations)  
- ✅ Compare metrics across countries/regions  
- ✅ Visualize trends with charts and maps  
- ✅ Communicate findings in a Jupyter Notebook or PDF report  

## 🗂️ Project Workflow

### 1️⃣ Data Collection
- Source: [Our World in Data COVID-19 Dataset](https://ourworldindata.org/covid-cases)
- File used: `owid-covid-data.csv`

### 2️⃣ Data Loading & Exploration
- Load data with `pandas`
- Preview structure and identify missing values

### 3️⃣ Data Cleaning
- Filter countries of interest: **Kenya**, **USA**, **India**
- Drop rows with missing critical values (`date`, `total_cases`, etc.)
- Convert `date` column to datetime
- Fill missing numeric values with `0`

### 4️⃣ Exploratory Data Analysis (EDA)
- Plot **total cases** and **total deaths** over time  
- Compare **daily new cases** between countries  
- Calculate and plot **death rate** (`total_deaths / total_cases`)  

### 5️⃣ Visualizing Vaccination Progress
- Plot **% population vaccinated over time** (line chart)
- Plot **Vaccinated vs Unvaccinated** (line chart per country)


### 7️⃣ Insights & Reporting
- Summarize **3-5 key insights**
- Highlight patterns or anomalies
- Combine code, visualizations, and narrative into one **Jupyter Notebook report**

## 📊 Key Visualizations

- 📈 **Line Charts**  
  → COVID-19 cases, deaths, vaccinations over time

- 🥧 **Pie Charts**  
  → Vaccinated vs Unvaccinated per country


## 🛠️ Tools Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**

