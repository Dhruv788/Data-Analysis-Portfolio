# 📊 Data Analysis Portfolio

> A professional collection of data analysis projects showcasing skills in data cleaning, visualization, statistical analysis, and business insight generation using Python.

---

## 👨‍💻 About This Portfolio

This portfolio contains **2 complete data analysis projects** built using real-world datasets. Each project includes:
- ✅ Full data exploration and cleaning
- ✅ Statistical analysis
- ✅ Professional visualizations (6 charts per project)
- ✅ Business insights and recommendations

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3.12 | Core programming language |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| JupyterLab | Interactive development environment |

---

## 📁 Project Structure

```
data_portfolio/
│
├── 📓 project1_supermarket_sales.ipynb   ← Project 1 notebook
├── 📓 project2_house_prices.ipynb        ← Project 2 notebook
│
├── 📊 supermarket_sales.csv    ← Dataset 1
├── 📊 house_prices.csv         ← Dataset 2
│
├── 🖼️ chart1_branch_sales.png
├── 🖼️ chart2_product_sales.png
├── 🖼️ chart3_gender_spending.png
├── 🖼️ chart4_busiest_hours.png
├── 🖼️ chart5_payment_method.png
├── 🖼️ chart6_ratings.png
├── 🖼️ chart1_price_by_location.png
├── 🖼️ chart2_area_vs_price.png
├── 🖼️ chart3_bedroom_price.png
├── 🖼️ chart4_property_type.png
├── 🖼️ chart5_age_vs_price.png
├── 🖼️ chart6_correlation_heatmap.png
│
└── 📝 README.md   ← You are here
```

---

## 🛒 Project 1 — Supermarket Sales Analysis

### 📌 Objective
Analyze 2,000 supermarket transactions to discover sales patterns, top products, customer behavior, and peak hours.

### 📊 Dataset
| Property | Value |
|----------|-------|
| File | `supermarket_sales.csv` |
| Rows | 2,000 |
| Columns | 14 |
| Period | 2023 |

### 🔍 Analysis Performed
- Branch-wise revenue comparison (A, B, C)
- Product line performance ranking
- Gender-based spending patterns
- Hourly customer traffic analysis
- Payment method preference study
- Customer satisfaction rating distribution

### 📈 Key Findings

| Metric | Result |
|--------|--------|
| Total Revenue | 519,281 |
| Best Branch | Branch B |
| Top Product | Health & Beauty |
| Busiest Hour | 8:00 AM |
| Top Payment | Ewallet |
| Avg Rating | 6.96 / 10 |

### 💡 Business Recommendations
1. **Branch C** needs targeted promotions — it trails Branch B by 12%
2. **Increase stock** of Health & Beauty products — highest revenue generator
3. **Schedule more staff** at 8:00 AM — peak customer traffic hour
4. **Promote Ewallet** payments — most preferred by customers
5. **Investigate low-rated** products and improve quality or presentation

### 📊 Charts Generated
- Bar Chart: Total Sales by Branch
- Horizontal Bar: Sales by Product Line
- Pie Chart: Average Spending by Gender
- Line Graph: Customer Traffic by Hour
- Bar Chart: Payment Method Preference
- Histogram: Customer Rating Distribution

---

## 🏠 Project 2 — House Price Analysis

### 📌 Objective
Analyze 300 property records to understand what factors most influence house prices across different locations and property types.

### 📊 Dataset
| Property | Value |
|----------|-------|
| File | `house_prices.csv` |
| Rows | 300 |
| Columns | 8 |
| Features | Area, Bedrooms, Bathrooms, Age, Location, Type, Price |

### 🔍 Analysis Performed
- Average price by location (City Center, Suburb, Rural)
- Area vs Price correlation analysis
- Bedroom count impact on pricing
- Property type price distribution
- House age vs price relationship
- Full feature correlation heatmap

### 📈 Key Findings

| Metric | Result |
|--------|--------|
| Average House Price | Rs 24.88M |
| Most Expensive Location | City Center |
| Best Property Type | Apartment |
| Area-Price Correlation | 0.8 (Strong) |
| Age-Price Correlation | Negative |

### 💡 Business Recommendations
1. **City Center** properties are 2x more expensive than Rural — buyers on budget should explore Rural
2. **Area is the strongest price driver** — correlation of 0.8 confirms bigger = pricier
3. **Villa properties** command premium prices — best for investment
4. **More bedrooms** = higher value — renovation to add bedrooms boosts resale
5. **Newer properties** are priced higher — factor renovation costs for older homes

### 📊 Charts Generated
- Bar Chart: Average Price by Location
- Scatter Plot: Area vs Price (colored by Location)
- Line Graph: Price by Number of Bedrooms
- Box Plot: Price Distribution by Property Type
- Scatter Plot: Age vs Price
- Heatmap: Full Feature Correlation Matrix

---

## ⚙️ How to Run This Project

### Step 1 — Install Requirements
```bash
pip install pandas matplotlib seaborn jupyterlab reportlab
```

### Step 2 — Launch JupyterLab
```bash
python -m jupyterlab
```

### Step 3 — Open and Run Notebooks
1. Open `project1_supermarket_sales.ipynb`
2. Click **Run → Run All Cells**
3. Open `project2_house_prices.ipynb`
4. Click **Run → Run All Cells**

All charts will be saved automatically as PNG files and PDF reports will be generated.

---

## 📦 Requirements

```
pandas
matplotlib
seaborn
jupyterlab
reportlab
```

---

## 📬 Contact

Built as part of a **Data Analysis Portfolio Project**.

Feel free to explore the notebooks and PDF reports for full analysis details!

---

*Made with Python 🐍 | Powered by Pandas, Matplotlib & Seaborn*
