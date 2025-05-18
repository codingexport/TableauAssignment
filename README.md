# 📊 Tableau Assignments
#Solution
---

## 📁 Assignment 1 – Charts & Quick Table Calculations

**Task:**

Create a table with:
- `Category`, `Sub-Category` on **Rows**
- `Region` on **Columns**
- Show `Total Sales` and `Total Profit` for each region
- Include `Grand Total` and `Percent of Pane Total`
- Sort by `Sum of Sales` in **descending** order

**Expected Output:**

![Assignment 1 Example](![image](https://github.com/user-attachments/assets/c9191c2c-e10b-4135-ab1e-7af2edebe6c6)
)

---

## 🔗 Assignment 2 – Data Combining Techniques & Filtering

**Task:**

Using the **Netflix Titles** dataset:
- Merge tables using **Inner Joins**
- Identify the actor/actress with the **highest number of appearances** in **Sports Movies**
- Provide the **name** and **corresponding movie titles**

---

## 📊 Assignment 3 – LODs & Histogram

**Task:**

Create a **Histogram** in Tableau:
- `X-axis`: Number of Orders
- `Y-axis`: Count of Customers (based on order frequency)

---

## 🍰 Assignment 4 – Sets

**Task:**

Create a **Pie Chart** showing:
- **Top 50 Customers** vs **Other Customers**
- Based on `Sum of Sales`

**Expected Output:**

![Assignment 4 Example](./images/assignment4.png)

---

## 📈 Assignment 5 – KPI Card & Table Calculations

**Task:**

Build a **KPI Card** showing:
- `Total Profit` for the **current year** (last year of dataset)
- `% Growth` from previous year using:
  - `▲` and “+” for **positive growth**
  - `▼` and “-ve” for **negative growth**
- Include a **line chart** for **monthly profit trends** (current year)

**Helpful Symbols:**
▼ , ▲

---

## 🎛 Assignment 6 – Parameters & Groups

### Part 1: Parameter – View By
- Create a parameter named **View by**
- Values: `Region`, `Category`, `Sub-Category`
- Display **bar chart** based on selected value (e.g., category-wise sales)
- Update the **worksheet title dynamically**

### Part 2: Groups
- Group the following products:
  - `Acco`, `3M`, `Samsung`, `Apple`, `Xerox`
  - All others in a group named `Others`
- Show **average discount percentage** for each group

---

## 📊 Assignment 7 – Dashboard (Superstore)

**Task:**

Create a **Tableau Dashboard** using the **Sample Superstore** dataset.

### 🔧 Features:

- Split dashboard into **two planes**:
  - **Left**: Logo, interaction controls, filters for `Year` and `Region`
  - **Right**: 6 dynamic visualizations + 3 KPI Cards

- **KPI Metrics**:
  - **Profit Margin** = `Total Profit / Total Sales`
  - **Return Rate** = `Quantity Returned / Quantity Ordered`

- Add a **Metric Parameter** for:
  - `Sales`, `Profit`, `# Orders`
  - Visuals & titles dynamically change per selected metric

- **Filters**:
  - `Year` and `Region`
  - Include **Show/Hide filter buttons**

- Always show **Top 5 Products** by selected metric

- Apply **Filter Action**:
  - Clicking the **Category Chart** should filter other charts + KPI cards

- Clicking on the **logo** redirects to Tableau Public dashboard

- Include **Average Lines & Trend Lines** where needed

---

### 🖼 Dashboard Images

**Dashboard Logo:**

![Dashboard Logo](./images/dashboard_logo.png)

**Show Filters Icon:**

![Show Filters](./images/show_filters_icon.png)

**Hide Filters Icon:**

![Hide Filters](./images/hide_filters_icon.png)

**Dashboard Example:**

![Dashboard Example](./images/dashboard_example.png)

---

📍 _ExcelR Edtech Pvt. Ltd._
