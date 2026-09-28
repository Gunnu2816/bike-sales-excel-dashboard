# 🚲 Bike Sales Analysis & Interactive Excel Dashboard

## 📌 Project Overview

This project analyzes customer data to understand the factors associated with **bike purchasing behavior**.
The analysis uses customer attributes such as:

* Gender
* Marital Status
* Income
* Number of Children
* Education
* Occupation
* Home Ownership
* Cars Owned
* Commute Distance
* Region
* Age
* Bike Purchase Status

The cleaned dataset was transformed into an interactive Excel dashboard using **Pivot Tables, Pivot Charts, and Slicers**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Clean and prepare the dataset for analysis
* Identify and handle duplicate records
* Create calculated fields using Excel formulas
* Categorize customers into age brackets
* Analyze bike purchasing patterns across different customer segments
* Build Pivot Tables for structured analysis
* Create interactive Pivot Charts
* Develop an interactive dashboard using Excel Slicers
* Present the analysis in a clear and user-friendly format

---

## 🛠️ Tools & Technologies

| Tool                       | Purpose                                     |
| -------------------------- | ------------------------------------------- |
| **Microsoft Excel**        | Data cleaning, analysis and visualization   |
| **Excel Formulas**         | Data transformation and calculated columns  |
| **Pivot Tables**           | Aggregation and exploratory analysis        |
| **Pivot Charts**           | Visual representation of analytical results |
| **Slicers**                | Interactive filtering                       |
| **Conditional Formatting** | Data visualization and formatting           |

---

## 📂 Dataset

The dataset contains customer-level information related to demographics, financial characteristics, lifestyle attributes, and bike purchasing behavior.

### Key Columns

| Column           | Description                           |
| ---------------- | ------------------------------------- |
| ID               | Unique customer identifier            |
| Marital Status   | Customer's marital status             |
| Gender           | Customer gender                       |
| Income           | Customer income                       |
| Children         | Number of children                    |
| Education        | Education level                       |
| Occupation       | Customer occupation                   |
| Home Owner       | Whether the customer owns a home      |
| Cars             | Number of cars owned                  |
| Commute Distance | Customer commute distance             |
| Region           | Customer geographical region          |
| Age              | Customer age                          |
| Age Brackets     | Calculated age category               |
| Purchased Bike   | Whether the customer purchased a bike |

---

## 🧹 Data Cleaning & Preparation

The raw dataset was prepared before performing the analysis.

The data preparation process included:

* Reviewing the dataset structure
* Checking for duplicate records
* Removing duplicate entries where appropriate
* Standardizing categorical values
* Reviewing inconsistent data entries
* Creating calculated columns
* Preparing the dataset for Pivot Table analysis

### Age Bracket Calculation

A calculated **Age Brackets** column was created using an Excel `IF` formula to categorize customers based on their age.

Example:

```excel
=IF(L2>55,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))
```

This transformed the numerical **Age** field into meaningful categories for dashboard analysis.

---

## 📊 Exploratory Analysis

Pivot Tables were created to analyze relationships between customer characteristics and bike purchasing behavior.

The analysis includes:

### 1. Income & Bike Purchase

Comparison of average customer income based on:

* Gender
* Bike purchase status

This helps examine differences in income between customers who purchased a bike and those who did not.

### 2. Commute Distance

Customer commute distances were analyzed against bike purchase behavior.

Commute categories include:

* 0–1 Miles
* 1–2 Miles
* 2–5 Miles
* 5–10 Miles
* More Than 10 Miles

### 3. Age Brackets

Customers were grouped into age categories and analyzed based on bike purchase status.

### 4. Age Distribution

The project also includes analysis of individual customer ages against bike purchasing behavior.

---

## 📈 Interactive Dashboard

The final dashboard provides a visual summary of the analysis.

### Dashboard Components

The dashboard contains:

* **Average Income Per Purchase** chart
* **Customer Commute** chart
* **Customer Age Bracket** chart
* **Age Distribution** chart
* Interactive slicers
* Pivot-based visualizations

### Interactive Slicers

Users can dynamically filter the dashboard using slicers for:

* **Marital Status**
* **Region**
* **Education**

Changing a slicer selection updates the connected Pivot Charts, allowing different customer segments to be explored interactively.

---

## 🖥️ Dashboard Preview

The dashboard was designed to provide a simple interface for exploring customer purchasing behavior.

**Main dashboard features:**

> 📊 Income Analysis
> 🚗 Commute Analysis
> 👥 Age Bracket Analysis
> 📈 Age Distribution
> 🎓 Education Filtering
> 🌍 Region Filtering
> 💍 Marital Status Filtering

---

## 📁 Project Structure

```text
bike-sales-excel-dashboard/
│
├── Bike_Sales_Analysis_Dashboard.xlsx
├── README.md
│
└── images/
    └── dashboard.png
```

### Files

**`Bike_Sales_Analysis_Dashboard.xlsx`**

The complete Excel workbook containing:

* Working Sheet
* Cleaned dataset
* Calculated fields
* Pivot Tables
* Pivot Charts
* Interactive Dashboard
* Slicers

**`README.md`**

Project documentation and explanation.

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Duplicate & Data Validation
     ↓
Calculated Columns
     ↓
Age Bracket Creation
     ↓
Pivot Tables
     ↓
Pivot Charts
     ↓
Interactive Slicers
     ↓
Dashboard
     ↓
Customer Purchase Analysis
```

---

## 💡 Key Excel Skills Demonstrated

This project demonstrates practical application of:

* Data cleaning
* Data validation
* Duplicate removal
* `IF` formulas
* Calculated columns
* Conditional formatting
* Pivot Tables
* Pivot Charts
* Slicers
* Data filtering
* Dashboard design
* Data visualization
* Exploratory Data Analysis

---

## 📚 What I Learned

Through this project, I gained hands-on experience in converting a raw dataset into an interactive analytical dashboard.

The project helped strengthen my understanding of:

* Preparing real-world datasets for analysis
* Using Excel formulas for data transformation
* Summarizing large datasets using Pivot Tables
* Building interactive visualizations
* Connecting Slicers with Pivot-based dashboards
* Presenting analytical results in a user-friendly format
