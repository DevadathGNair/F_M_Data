# 📱 Flipkart Mobile Sales Analysis (Python + Power BI)

A comprehensive data science and business intelligence project analyzing Flipkart mobile sales data. This project includes data cleaning, feature engineering, exploratory data analysis (EDA), insights generation using Python, and interactive dashboard development in Power BI.

---

## 📂 Project Structure

- `Flipkart_Mobiles.csv` – Raw dataset with 3,100+ records of mobile phones sold on Flipkart
- `Flipkart_Analysis.ipynb` – Python notebook for data processing, feature engineering, and EDA
- `Flipkart_Dashboard.pbix` – Power BI file with executive and summary dashboards
- `README.md` – Project documentation

---

## 🧠 Objectives

- Clean and preprocess messy data (e.g., memory/storage in text format)
- Engineer new features (e.g., price segments, RAM/ROM in GB, discount %, low ratings)
- Extract actionable business insights
- Design a dual-view Power BI dashboard (Executive + Summary)

---

## 📊 Key Insights

1. **Price Segments Identified**:
   - Ultra Budget (< ₹10,000)
   - Budget (₹10,000–₹15,000)
   - Mid-Range (₹15,000–₹25,000)
   - Premium (₹25,000–₹40,000)
   - Flagship (₹40,000+)

2. **Top Brands by Product Count**:
   - Xiaomi, Realme, Samsung are top in number of offerings.

3. **Brand Coverage**:
   - Samsung and Xiaomi cater to **all price segments**, from budget to flagship.
   - OnePlus and Apple focus only on premium/flagship segments.

4. **Common Specifications**:
   - **RAM**: 4GB and 6GB most common
   - **ROM**: 64GB and 128GB dominate

5. **User Ratings**:
   - Most phones are rated **4.2 to 4.5**
   - Less than 10% of models are low-rated (<3.5)

---

## ⚙️ Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Power BI** (Data Modeling, Slicers, KPIs, Custom Visuals)
- **Git** / GitHub

---

## 🧹 Feature Engineering Highlights

- Extracted numeric values from messy strings like `"4 GB RAM"` → `RAM_GB = 4`
- Converted `"128 MB"` to GB format for consistency
- Created:
  - `Price_Segment`
  - `Discount_Percentage`
  - `Low_Rated` (binary feature)

---

## 📈 Dashboard Design (Power BI)

### Executive View (For Leadership)
- KPI Cards (Avg. Price, Avg. Rating, Discount %)
- Heatmap (Brand x Price Segment)
- Brand-wise Distribution
- Rating Distribution (Area Chart)
- Segment Share (Donut Chart)

### Summary View (For Analysts)
- RAM & ROM Distribution (Clustered Charts)
- Box Plot: Price by Brand
- Scatter Plot: Discount % vs Price
- Detailed Specs Table with filters

---

## 📌 How to Use

1. Open the Jupyter Notebook `Flipkart_Analysis.ipynb` to view and rerun the analysis.
2. Load `Flipkart_Dashboard.pbix` in Power BI Desktop to interact with the dashboards.
3. Use slicers to filter by Brand, RAM/ROM size, Ratings, and Price Segment.

---

## 🧠 Learnings

This project helped reinforce key concepts in:
- Real-world messy data handling
- Feature engineering for business analytics
- Visual storytelling via executive dashboards
- KPI selection and audience-based design (CXO vs Analyst)

---

## 📬 Contact

**Devadath G Nair**  

---

⭐ If you found this project helpful, give it a ⭐ on GitHub!
