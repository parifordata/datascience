# 🔵 Level 4: DAX & Interactivity

## 📌 Objective
To create custom logic using DAX and build interactive dashboards using slicers.

# 🔹 Task 1: Created Calculated Column (DAX)

## ✔ Population Category

Used DAX to classify countries based on population:

- Very High → Population > 1 Billion  
- High → Population > 100 Million  
- Medium → Others  

### DAX Code:
```DAX
Population Category = 
IF([Population] > 1000000000, "Very High",
IF([Population] > 100000000, "High",
"Medium"))
### ✔ Slicer Added
Field → Population Category
✔ What it does:
Acts as an interactive filter
Allows user to select:
Very High
High
Medium
