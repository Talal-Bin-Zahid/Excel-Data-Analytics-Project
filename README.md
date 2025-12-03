# 📊 Vehicle Sales Dashboard — Excel Analytics Project
<img width="850" height="554" alt="Excel Vehicle Sales Dashboard" src="https://github.com/user-attachments/assets/18068576-4514-438e-8cdb-084479467aac" />

---

## 1. **Project Overview & Business Context**

**Project Name:** **Vehicle Sales Analytics Workbook**

**Purpose / Goal:**
To analyze customer demographics, purchasing behavior, commute patterns, and occupation-based trends to understand key drivers behind vehicle purchases. The dashboard centralizes all insights in a clean, interactive Excel environment.

**Target Audience:**

* Business Analysts
* Sales Strategy Teams
* Marketing & Customer Insights Teams
* Automotive Dealership Management

---

## 2. **Workbook Structure and Navigation**

### **Key Worksheets / Tabs**

* `01_RawData_Input`
* `02_Data_Cleansing`
* `03_PivotTables`
* `04_Vehicle_Sales_Dashboard`
* `05_Configurations`

### **Input Data Sheet**

* **`01_RawData_Input`**
  This sheet accepts new customer, sales, and demographic data. All imports and updates start here.

### **Output / Summary Sheet**

* **`04_Vehicle_Sales_Dashboard`**
  Contains charts showing:
  ✔ Income by Gender
  ✔ Customer Commute Patterns
  ✔ Cars by Occupation
  ✔ Age Bracket Analysis
  ✔ Purchase Behavior Comparisons

## 3. **Data Source and Update Procedure**

### **Data Source Location**

* Extracted from **Vehicle Sales CRM System**
* Supplementary demographic files exported monthly from **Marketing Data Hub**
* Commute distance & occupation attributes sourced from internal customer surveys

### **Data Update Steps**

1. Export the latest customer dataset (CSV or Excel).
2. Open the workbook and go to `01_RawData_Input`.
3. **Clear old data** (except headers).
4. **Paste new data starting at cell A2**.
5. Navigate to **Data → Refresh All** to update PivotTables and Dashboard.
6. Review updated charts in `04_Vehicle_Sales_Dashboard`.

---

## 4. **Key Formulas and Calculations**

### **Complex Formulas Used**

* **`SUMIFS`** – Used for aggregating income, car counts, and commute groupings.
* **`VLOOKUP / XLOOKUP`** – Maps demographic segments such as Age Bracket and Occupation.
* **`COUNTIFS`** – Used for counting purchase patterns (Yes/No).
* **PivotTables** – Drive all dashboard visualizations.
* **Power Query (Optional)** – Used for cleaning and shaping raw imported data.

### **Key Named Ranges**

* `Input_Data_Range`
* `Occupation_Lookup_Table`
* `Age_Bracket_Grouping`
* `Commute_Category`

### **Validation / Error Checks**

* **Dropdown lists** for Occupation, Commute Distance & Purchase Status.
* **Conditional formatting** for invalid or missing data.
* **Error flags** highlight blank demographic fields.

---

## 5. **Maintenance and Support**

**File Owner / Version:**
*Talal-Bin-Zahid*

**Date Last Updated:**
*2025-12-04*
