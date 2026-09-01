#Lettuce Growth Days Analysis

# Data Analysis Project

# Data Analyst: Bushra Fawaz
Client/Sponsor: Agriculture Research Department

# Project Overview

This project analyzes lettuce growth data to explore the relationship between environmental conditions and lettuce growth duration.

#The analysis focuses on four main environmental factors:

* Temperature (°C)
* Humidity (%)
* TDS Value (ppm)
* pH Level

The dataset contains daily observations for individual lettuce plants, including plant ID, date, environmental conditions, and growth days.

 Project Objectives

The main objectives of this project are to:

* Understand the structure and characteristics of the lettuce growth dataset.
* Clean and prepare the data for analysis.
* Explore relationships between environmental factors and lettuce growth days.
* Identify trends and patterns that may influence lettuce growth.
* Develop data-driven insights and recommendations for improving growing conditions.

 Dataset

The dataset contains **3,170 records** covering **70 plants**.

Main Columns

| Column             | Description                                  |
| ------------------ | -------------------------------------------- |
| `Plant_ID`         | Unique identifier for each lettuce plant     |
| `Date`             | Date of the observation                      |
| `Temperature (°C)` | Recorded temperature                         |
| `Humidity (%)`     | Recorded humidity percentage                 |
| `TDS Value (ppm)`  | Total Dissolved Solids value                 |
| `pH Level`         | Recorded pH level                            |
| `Growth Days`      | Number of growth days recorded for the plant |

## Project Workflow

The project follows these main stages:

### 1. Data Collection

The lettuce growth dataset was imported into Excel for analysis.

### 2. Data Understanding

The dataset was reviewed to understand:

* Column names and meanings
* Data types
* Number of records
* Plant identifiers
* Growth-day observations
* Environmental variables

### 3. Data Cleaning

The data was reviewed for:

* Missing values
* Incorrect or inconsistent values
* Formatting issues
* Data consistency

### 4. Data Analysis

The analysis focuses on identifying relationships and patterns between:

* Temperature and growth days
* Humidity and growth days
* TDS and growth days
* pH and growth days

Descriptive analysis, calculations, and Pivot Tables are used to explore the dataset.

### 5. SMART Questions

Structured analytical questions are used to guide the analysis and identify meaningful patterns in the data.

### 6. Data Interpretation

The results are interpreted to identify important patterns and potential factors associated with lettuce growth duration.

### 7. Recommendations

Practical recommendations were developed based on the analysis findings, with particular attention to pH levels and the relationships between environmental factors and Average Growth Days.


## Analysis Outputs

The Excel analysis includes:

* Summary calculations
* Pivot Tables
* Data visualizations
* Comparison of environmental factors
* Key insights
* Recommendations
# Key Findings

The analysis found no strong linear relationship between the four environmental factors and Average Growth Days.

* **Temperature:** Very weak positive correlation (r = 0.127).
* **Humidity:** Very weak negative correlation (r = -0.139).
* **TDS Value:** Near-zero correlation (r = 0.0003).
* **pH Level:** Weak positive correlation (r = 0.300), which was the strongest correlation among the four factors.

Overall, the results suggest that no single environmental factor analyzed showed a strong linear relationship with lettuce growth duration.


#Out of Scope

This project does not include:

* Predictive models for forecasting future plant growth.
* Collecting additional data outside the provided dataset.
* Modifying the original dataset values.
* Advanced statistical modeling beyond basic descriptive analysis.

# Project Files

* `lettuce_dataset.csv.xlsx` — Lettuce growth dataset and analysis workbook.
* `Scope-Of-Work Lettuce Growth Days Analysis.docx` — Project scope and requirements.
* `README.md` — Project overview, methodology, and documentation.

# Tools

* Microsoft Excel
* Pivot Tables
* Data Cleaning
* Descriptive Data Analysis
* Data Visualization

# Project Status

**Completed**

The dataset has been collected, cleaned, analyzed, and visualized. The project includes data analysis, Pivot Tables, insights, recommendations, and final documentation.

# Author

**Bushra Fawaz**
Data Analyst | Information Systems
