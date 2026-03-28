# 🟠 Level 3: Data Analysis

## 📌 Objective
To perform basic data analysis using Power BI by creating KPI cards, understanding aggregation (Sum, Average, Max), and comparing income groups.

# 🔹 Task 1: KPI Cards

## 🎯 Goal
Display important summary metrics using Card visuals.

### ✔ Steps Performed
1. Went to **Report View**
2. Selected **Card Visual (123 icon)** from Visualizations pane
3. Dragged fields:
   - Population → (default: Sum)
   - GDP (Trillion $) → changed to Average
   - Population Growth % → changed to Max
4. Used field dropdown → selected aggregation:
   - **Sum / Average / Max**
5. Opened **Format (paint roller 🎨)**:
   - Title → ON
   - Renamed titles:
     - Total Population
     - Average GDP
     - Max Growth Rate
6. Adjusted size and aligned all cards in one row

---

# 🔹 Task 2: Understanding Sum vs Average vs Max

## 🎯 Concept
Different aggregations answer different questions:

- **Sum** → Total value (e.g., total population)
- **Average** → Typical value (e.g., average GDP)
- **Max** → Highest value (e.g., fastest growth rate)

### ✔ Practical Application
- Population → Sum (Total scale)
- GDP → Average (Typical economy size)
- Growth % → Max (Extreme case)

---

# 🔹 Task 3: Income Group Analysis

## 🎯 Goal
Compare economic strength across income groups.

### ✔ Steps Performed
1. Added **Bar Chart**
2. Set fields:
   - Axis → IncomeGroup
   - Values → GDP (Trillion $)
3. Changed aggregation:
   - Click dropdown → selected **Average**
4. Clicked **3 dots (⋯)** on chart:
   - Sort by GDP
   - Selected **Descending**
5. Opened **Format panel**:
   - Title → ON → "Average GDP by Income Group"
   - Data Labels → ON

---

# 📊 Key Insights
- High income countries have higher average GDP
- Low income countries have lower GDP
- DR Congo has the highest population growth rate

---

# 🧠 Concepts (Simple Explanation)

- **KPI (Key Performance Indicator)**  
  A single number that summarizes important information (e.g., total population)

- **GDP (Gross Domestic Product)**  
  Total value of goods and services produced by a country → shows economic strength

- **Population Growth %**  
  Rate at which population is increasing

- **Why Average GDP?**  
  Because each income group has multiple countries → average gives a typical value

---

# ⚠️ Important Note
By default, Power BI selects **Sum** as aggregation for numeric fields.  
You must manually change it based on the analysis requirement.

---

## 🚀 Status
Completed ✅
