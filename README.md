# 📊 Employee Project Cost & Performance Management Analysis (Python)

Structured data engineering and business rule automation project using Python (Pandas & NumPy) to model employee–project performance evaluation and cost governance workflows.

---

## 📌 Project Objective

Develop an integrated workforce–project analytical model to demonstrate how structured data can be:

- Cleaned and validated  
- Integrated across relational datasets  
- Transformed using defined business rules  
- Aggregated for managerial reporting  

The analysis focuses on cost management, employee performance tracking, and designation-level governance.

---

## 🗂 Dataset Structure

Three relational datasets were created and stored as CSV files:

### Project Dataset
- Employee ID  
- Project Name  
- Cost  
- Status (Finished / Ongoing / Failed)

### Employee Dataset
- Employee ID  
- Name  
- Gender  
- City  
- Age  

### Seniority Dataset
- Employee ID  
- Designation Level  

These datasets simulate HR records, project accounting data, and organizational hierarchy structures.

---

## 🔧 Data Engineering & Business Logic Implementation

### 1️⃣ Missing Cost Imputation

- Identified missing values in the `Cost` column  
- Computed running average using iterative logic (for-loop)  
- Replaced missing values and updated source file  

Ensures financial data consistency and reporting integrity.

---

### 2️⃣ Name Standardization

- Split full name into `First Name` and `Last Name`  
- Removed original column  

Improves structural consistency for reporting and downstream processing.

---

### 3️⃣ Relational Data Integration

- Merged project, employee, and seniority datasets  
- Created consolidated analytical dataset (`Final`)  

Enables unified employee–project performance evaluation.

---

### 4️⃣ Performance-Based Incentive Logic

- Applied 5% bonus to employees with project status = "Finished"  

Demonstrates automated incentive calculation based on defined performance criteria.

---

### 5️⃣ Designation Governance Rules

- Adjusted designation level for failed projects  
- Removed records exceeding permitted designation thresholds  
- Applied promotion logic for employees above age threshold  

Models structured HR policy automation and hierarchical control logic.

---

### 6️⃣ Identity Transformation

- Added formal prefixes based on gender  
- Removed gender column after transformation  

Demonstrates controlled transformation for standardized presentation.

---

### 7️⃣ Project Cost Aggregation

Created aggregated dataset:

**TotalProjCost**
- ID  
- First Name  
- Total Cost (sum of project costs per employee)

Supports managerial evaluation of cost allocation and resource exposure.

---

### 8️⃣ Conditional Record Filtering

Filtered employee records based on city name criteria.

Demonstrates targeted segmentation and conditional querying capability.

---

## 🛠 Technical Competencies Demonstrated

- Python (Pandas, NumPy)  
- CSV File Handling  
- Iterative Imputation Logic  
- Conditional Transformations (`np.where`, `lambda`)  
- Multi-Table Merging  
- Feature Engineering  
- GroupBy Aggregation  
- Business Rule Automation  
- String Manipulation  
- Structured Data Filtering  

---

## 🎯 Business Application

This project demonstrates practical implementation of:

- Incentive calculation systems  
- Performance-based designation adjustments  
- Workforce cost accountability reporting  
- Automated policy-driven transformations  
- Structured multi-source data integration  

It reflects applied analytical capability in translating organizational policies into executable data logic using Python.
