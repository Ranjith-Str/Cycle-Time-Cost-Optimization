# Cycle Time vs Cost Analysis  


## 🎯 Objective  
Analyze how manufacturing **cycle time** affects **unit cost** across materials and suppliers,  
and identify process areas for cost optimization.

---

## 🧰 Tools & Techniques  
- **Python (pandas, matplotlib)** – data cleaning and profiling  
- **SQLite (SQL)** – validation and aggregations  
- **PowerPoint (CCX theme)** – professional reporting  
- **Excel (optional)** – cross-check and charting  

---

## 🧹 Data Cleaning (Performed in Python)  
1. Loaded raw file `cycle_cost_raw_unclean.csv`.  
2. Removed duplicates and null records.  
3. Fixed negative `CostPerUnitINR` and invalid cycle times.  
4. Capped outliers using
