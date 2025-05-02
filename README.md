# TASK8-DATA-ANALYSIS
POWERBI-TASK3
# 📊 Simple Sales Dashboard – Power BI

This project presents a clean and interactive **Sales Dashboard** built using **Power BI**. It provides visual insights into sales performance by **month**, **region**, and **category** using sample e-commerce data.

---

## 🎯 Objective

To create an interactive dashboard that helps stakeholders:
- Track monthly sales trends
- Analyze performance by region and category
- Identify top-performing segments

---

## 🛠 Tools Used

- **Power BI Desktop**
- (Optional) **Python + Pandas** (for data preprocessing)
- GitHub for version control and documentation

---

## 📁 Dataset

- File Used: `Superstore_Sales.csv`  
- Sample Columns:
  - `Order Date`
  - `Region`
  - `Category`
  - `Sales`
  - `Profit`

---

## 📌 Steps Followed

1. **Imported** the CSV into Power BI.
2. **Converted** `Order Date` into `Month-Year` format using DAX:
   ```DAX
   MonthYear = FORMAT('Sales'[Order Date], "MMM-YYYY")
