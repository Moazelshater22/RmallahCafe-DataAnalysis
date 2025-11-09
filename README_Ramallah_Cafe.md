# ☕ Rmallah Café – Data Analysis Project

### 📊 Overview
This project analyzes **Rmallah Café’s food sales data** to uncover insights that support better decision-making on pricing, product performance, and category management.  
The analysis covers **data cleaning**, **exploratory data analysis (EDA)**, and **business insights generation**, turning raw sales data into actionable recommendations.

---

### 🧩 Objectives
- Clean and standardize the café’s sales dataset.  
- Identify the **top-selling and least-selling items**.  
- Analyze **category-level revenue and quantity** performance.  
- Visualize trends to help management optimize menu pricing and stock control.  

---

### 📁 Dataset
- **Source:** Internal Food Sales Report (July 2025)  
- **File:** `Food Sales Report2025-07-07.csv`  
- **Main Columns:**  
  - `Category Name` – item category (e.g., drinks, extras, desserts)  
  - `Food Menu(Code)` – menu item code or name  
  - `Quantity` – number of items sold  
  - `Sales Value` – total sales amount (EGP)  
  - `Ave Selling Price` – average selling price per item  

---

### 🧼 Data Cleaning Steps
- Removed commas from `Sales Value` and converted it to **float**.  
- Trimmed extra spaces and unified case for category and item names.  
- Translated Arabic entries (e.g., “إضافات” → `extras`, “إضافة رومي” → `extra cheese`).  
- Checked for **nulls** and **duplicates**.  

---

### 🔍 Exploratory Data Analysis (EDA)
The analysis answered key questions:

1. **What are the best-selling items?**  
   Top 10 items identified by total quantity sold.  
   → *Visualized in `Ramallah4.png`*

2. **Which items generate the most revenue?**  
   Top 10 items ranked by `Sales Value`.  
   → *Visualized in `top_revenue.png`*

3. **Which categories perform best overall?**  
   - Total revenue per category → `top_revenue(Cat).png`  
   - Quantity per category (pie chart) → `top_sales(Cat).png`

4. **How do average prices vary by category?**  
   Box-plot visualization of `Ave Selling Price` distribution across categories.

5. **Which items are underperforming?**  
   Bottom 10–50 items identified by low quantity and sales value.

---

### 📈 Key Business Insights
#### ✅ Best-Performing Items
- High-volume sellers should always be stocked and promoted.  
- Bundle top items or offer loyalty rewards to increase retention.

#### 💰 High-Revenue Items
- Premium items bring strong profits even if sold less frequently.  
- Small price adjustments can increase total revenue.

#### ⚠️ Low-Performing Items
- Review low-sales items — consider removal or marketing re-introduction.  
- Use promotions to test whether demand can be increased.

#### 📦 Category Strategy
- **High Revenue + High Quantity:** Prioritize and promote.  
- **Low Quantity + High Revenue:** Upsell through menu design or staff recommendations.  
- **High Quantity + Low Revenue:** Adjust pricing or portion sizes.

---

### 🧠 Tools & Libraries Used
- **Python**  
- **pandas** – data cleaning & manipulation  
- **matplotlib / seaborn** – data visualization  
- **Jupyter Notebook** – development environment  

---

### 🧾 Outputs
Generated visualizations saved as images:  
- `Ramallah4.png` – Top 10 Selling Items  
- `top_revenue.png` – Top 10 Revenue Items  
- `top_revenue(Cat).png` – Revenue by Category  
- `top_sales(Cat).png` – Quantity by Category (Pie)  
- `revnue vs qui.png` – Normalized Revenue vs Quantity  

---

### 🚀 Future Improvements
- Automate weekly or monthly updates with new café data.  
- Add forecasting models (e.g., ARIMA, Prophet) to predict demand.  
- Integrate dashboards (e.g., Power BI / Streamlit) for real-time insights.  

---

### 👤 Author
**Moaz Alnoby**  
Data Analyst – Rmallah Café Project  
📅 **August 8, 2025**  
