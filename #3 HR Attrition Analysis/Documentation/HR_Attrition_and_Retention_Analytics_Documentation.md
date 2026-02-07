# HR Attrition & Retention Analytics Documentation

## 1️⃣ Data Preparation (Power Query in Excel)
Steps performed in Power Query for cleaning and transforming the data:

- **Standardized Demographics:** Age groups, education levels, salary brackets, gender, and business travel column.
- **Replaced 'None' in numeric columns with 0** to handle missing data.
- **Ensured consistent department and job role names** for accurate aggregation.
- **Verified data types** for each column to ensure proper calculations in Power BI.


## 2️⃣ Data Modeling (Power BI)
- **Fact Table:** Employee Attrition Data
- **Dimension Tables:** Department, Job Role, Education Level
- **Relationships:** Each dimension connected to the fact table via primary key.
- **Data Model Type:** Star Schema (1 Fact Table, 3 Dimension Tables) for optimized reporting and calculations.

## 3️⃣ Measures / Calculations (DAX)
Key calculated measures used in Power BI:

- **Attrition Rate:** `Attrition Count / Employee Count`
- **Average Tenure:** `AVERAGE(FactEmployee[YearsAtCompany])`



## 4️⃣ Notes / Assumptions
- Dataset represents a mid-sized company preparing to scale.
- Analysis focuses on attrition by age, salary, education, gender, and years at company.
- Data was cleaned but anonymized for confidentiality.
- Attrition defined as employees marked as 'Yes' in the Attrition field.

---
*This documentation complements the main README and provides a detailed technical record of data transformation, modeling, and calculations.*
