# 🏥 Hospital Inpatient Clinical Analysis

An interactive Power BI dashboard designed to analyze hospital inpatient data and provide meaningful insights into patient demographics, severity of illness, treatment costs, hospital performance, and length of stay.

The dashboard transforms raw hospital data into an interactive analytical report using data cleaning, transformation, DAX calculations, and data visualization.

---

## 📊 Dashboard Preview

![Hospital Inpatient Clinical Analysis Dashboard](screenshots/dashboard.png)

---

## 🎯 Project Objective

The objective of this project is to analyze hospital inpatient data and answer key business and healthcare-related questions such as:

- How many patients were admitted?
- What is the average length of hospital stay?
- How does treatment cost vary across hospitals?
- What is the distribution of patients by severity of illness?
- How are patients distributed across different demographic categories?
- Which hospitals contribute the highest treatment costs?
- How can interactive filtering help explore patient-level patterns?

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculated metrics
- **Data Modeling** – Structuring data for analysis
- **Data Visualization** – Interactive charts, KPIs and slicers

---

## 📌 Key KPIs

The dashboard provides an overview of important hospital metrics, including:

- 👥 Total Patients
- 💰 Total Treatment Cost
- ⏱️ Average Length of Stay
- 🏥 Hospital-wise Cost Analysis
- 🩺 Severity of Illness Distribution
- 👤 Patient Demographic Analysis

---

## 📈 Dashboard Features

### 1. KPI Overview

Provides a quick summary of the major hospital performance indicators.

![KPI Overview](screenshots/kpi-overview.png)

---

### 2. Hospital-wise Treatment Cost

Compares treatment costs across hospitals to identify hospitals with higher and lower overall inpatient costs.

![Hospital Cost Analysis](screenshots/hospital-cost-analysis.png)

---

### 3. Severity of Illness Analysis

Visualizes the distribution of patients across different severity levels, helping understand the overall patient case mix.

![Severity Analysis](screenshots/severity-analysis.png)

---

### 4. Patient Analysis

Provides demographic-level analysis and allows users to interactively explore patient data using filters.

![Patient Analysis](screenshots/patient-analysis.png)

---

## 🎛️ Interactive Filters

The dashboard includes interactive slicers that allow users to explore the data based on:

- Gender
- Severity of Illness

The **Clear Filters** option allows users to quickly reset their selections.

---

## 🔍 Key Insights

The dashboard enables users to identify patterns and trends related to:

- Patient severity
- Hospital treatment costs
- Average length of stay
- Patient demographics
- Distribution of inpatient cases

These insights can help support data-driven understanding of hospital operations and patient characteristics.

---

## 🧠 Data Analysis Process

The project follows a typical data analytics workflow:

**Raw Data → Data Cleaning → Data Transformation → Data Modeling → DAX Measures → Visualization → Insights**

### Data Preparation

The data was prepared and transformed using Power Query before being used for dashboard development.

### Data Modeling

The dataset was structured to support efficient analysis and interactive filtering.

### DAX

DAX measures were used to calculate key metrics and KPIs required for the dashboard.

---

## 📂 Project Structure

```text
Hospital-Inpatient-Clinical-Analysis/
│
├── Hospital_Inpatient_Clinical_Analysis.pbix
├── README.md
│
└── screenshots/
    ├── dashboard.png
    ├── kpi-overview.png
    ├── hospital-cost-analysis.png
    ├── severity-analysis.png
    └── patient-analysis.png
