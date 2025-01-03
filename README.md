# Bank Churn Analysis Project

This project focuses on analyzing bank churn data. Churn refers to the number of customers who have left the bank (attrition). This is a practice project using a sample dataset to create reports and gain insights. Below is a detailed overview of the steps and tasks undertaken in this project.

<img width="533" alt="Screenshot 2024-04-06 102636" src="https://github.com/user-attachments/assets/0ab9ea1e-7819-4bae-9ce0-1c0c04e27ee7" />


## Key Steps:
1. **Data Connection**
2. **Data Preparation**
3. **Data Modeling and Analysis**
4. **Data Visualization**
5. **Report Sharing and Distribution**

## Data Cleaning and Preparation

### 1. Check Data Types and Column Names
- Ensured all data types and column names are correct and consistent.

### 2. Remove Unnecessary Columns
- Removed the `Estimated Salary` column.

### 3. Standardize Column Names
- Updated column names to start with capital letters.

### 4. Renamed Columns
- Updated column names for clarity:
  1. `Credit Score`
  2. `Credit Card Status`
  3. `Activity Status`
  4. `Churn Status`

### 5. Add Example Column
- Added a `Products` column with sample values (e.g., `Prod 1`).

### 6. Update Column Values
- **Churn Status:** Replaced values (`1` -> `Churned`, `0` -> `Not Churned`).
- **Activity Status:** Replaced values (`1` -> `Active`, `0` -> `Inactive`).
- **Credit Card Status:** Replaced values (`1` -> `Owned`, `0` -> `Not Owned`).

### 7. Add Conditional Columns
- **Age Group:** Created based on the `Age` column.
- **Credit Scores:** Categorized based on the `Credit Score` column.
- **Account Balance:** Categorized based on the `Balance` column.

### 8. Create Reference Tables
- **Age Groups Table:**
  - Created a reference table with the `Age Group` column and removed duplicates.
  - Added a conditional column `Age Group ID` (e.g., 1, 2, 3, ...).
- **Account Balance Table:**
  - Created a reference table with the `Account Balance` column.
  - Added a conditional column `Account Balance ID` (e.g., 1, 2, 3, ...).
- **Credit Scores Table:**
  - Created a reference table with the `Credit Score` column.
  - Added a conditional column `Credit Scores ID` (e.g., 1, 2, 3, ...).

## Creating Measures

### 1. Total Customers
- Created a DAX measure to calculate the total number of customers.

### 2. Lost Customers
- Created a DAX measure to calculate the number of lost customers.

### 3. Churn Rate
- Created a DAX measure to calculate the churn rate.

## Visuals Used in the Report

### **Cards**
1. Total Customers
2. Churn Rate
3. Lost Customers

### **Charts**
1. **Donut Charts:**
   - Number of Customers by Gender
   - Number of Customers by Activity Status
   - Number of Customers by Credit Card Status
   - Number of Customers by Country
   - Churn Rate
2. **Line Clustered Bar Chart:**
   - Customers and Churn Rate by Age Group
3. **Line and Stacked Column Chart:**
   - Customers and Churn Rate by Credit Score
4. **Line Chart:**
   - Customer Loss by Country
5. **Stacked Column Chart:**
   - Customers by Products

## Summary
This project demonstrates how to clean and prepare bank churn data, create meaningful measures, and build insightful visualizations in Power BI. The final report provides a comprehensive analysis of customer churn, activity status, credit card ownership, and more, enabling better decision-making for business stakeholders.
