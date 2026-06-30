# ☕ Starbucks Sales & Nutrition Analytics Dashboard | Power BI

> An interactive Power BI dashboard that analyzes Starbucks beverage nutrition data to uncover product insights, compare beverage categories, and visualize nutritional trends through dynamic dashboards.

---

# 📌 Project Overview

This project presents an interactive **Power BI Dashboard** built using Starbucks beverage nutrition data.

The objective of this project is to transform raw beverage information into meaningful business insights by analyzing nutritional values such as calories, sugar, caffeine, and protein across different beverage categories.

The dashboard enables users to interactively filter beverages, compare categories, and identify high-calorie or high-caffeine drinks for better decision-making.

---

# 🎯 Business Problem

Starbucks offers a wide variety of beverages with different nutritional compositions.

Customers and business stakeholders often need answers to questions like:

- Which beverage categories contain the highest calories?
- Which drinks have the highest caffeine?
- How are beverages distributed across categories?
- What is the average nutritional profile of Starbucks beverages?
- Which beverage types are healthier than others?

This dashboard answers these questions through interactive visualizations.

---

# 🚀 Dashboard Features

### KPI Cards

The dashboard displays important business metrics including:

- Total Beverage Categories
- Average Sugar
- Average Calories
- Average Caffeine

---

### Interactive Filters

Users can dynamically filter the dashboard using:

- Protein Range
- Beverage Preparation Type

All visualizations update automatically based on selected filters.

---

### Visualizations

#### 📈 Average Calories by Beverage Category

Shows the calorie distribution across beverage categories, helping identify high and low calorie drinks.

---

#### 🌍 Starbucks Global Presence

Displays Starbucks presence across beverage categories using a column chart.

---

#### 🍩 Beverage Category Distribution

Interactive donut chart showing percentage contribution of every beverage category.

---

#### ☕ Average Caffeine by Category

Ranks beverage categories according to average caffeine content.

---

#### 🔥 Top 5 Highest Caffeine Beverages

Highlights beverages with the highest caffeine values.

---

# 📊 Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| Total Beverages | Total beverages available in dataset |
| Average Sugar | Average sugar content |
| Average Calories | Average calories |
| Average Caffeine | Average caffeine content |

---

# 🛠 Tech Stack

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization

---

# 📂 Dataset Information

The dataset contains nutritional information for Starbucks beverages.

### Major Columns

- Beverage
- Beverage Category
- Beverage Preparation
- Calories
- Sugar (g)
- Caffeine (mg)
- Protein (g)
- Sodium (mg)
- Cholesterol (mg)
- Dietary Fibre (g)
- Saturated Fat (g)
- Calcium (%DV)
- Iron (%DV)

---

# 📈 DAX Measures Used

Examples of calculated measures used in this dashboard include:

```DAX
Total Beverages = COUNT(starbucks[Beverage])

Average Calories = AVERAGE(starbucks[Calories])

Average Sugar = AVERAGE(starbucks[Sugars_g])

Average Caffeine = AVERAGE(starbucks[Caffeine_mg])
```

Additional DAX calculations were used for:

- Dynamic KPI Cards
- Interactive filtering
- Category aggregations

---

# 🧹 Data Cleaning & Transformation

The dataset was cleaned using Power Query.

Cleaning steps included:

- Removing duplicate records
- Handling missing values
- Correcting data types
- Standardizing category names
- Preparing columns for analysis
- Creating calculated measures

---

# 📊 Dashboard Insights

Some key findings include:

- Coffee beverages contain the highest average caffeine levels.
- Smoothies and blended beverages contribute significantly to calorie intake.
- Beverage categories show diverse nutritional profiles.
- Certain beverages combine high sugar and high calories, making them less healthy choices.
- Interactive filters allow nutritional comparison across preparation methods.

---

# 🎨 Dashboard Design

The dashboard was designed with a Starbucks-inspired theme featuring:

- Green and white color palette
- Minimalistic layout
- Interactive slicers
- KPI cards
- Modern business visuals
- Easy-to-read charts
- Responsive report design

---

# 📷 Dashboard Preview

## Main Dashboard

<h2>📷 Dashboard Preview</h2>

<p align="center">
  <img src="Images/Dashboard.png" alt="Starbucks Dashboard" width="1000">
</p>

# 📁 Project Structure

```
Starbucks-Sales-PowerBI/
│
├── Starbucks Sales.pbix
├── Dataset/
│     └── starbucks.csv
│
├── Images/
│     ├── Dashboard.png
│     └── Preview.png
│
├── README.md
└── LICENSE
```

---

# 📌 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Power Query
- DAX
- Business Intelligence
- Dashboard Design
- Data Visualization
- Interactive Reporting
- KPI Development
- Business Analytics

---

# 📈 Future Improvements

Potential enhancements include:

- Profit & Revenue Analysis
- Sales Trend Analysis
- Seasonal Beverage Performance
- Geographic Sales Dashboard
- Customer Segmentation
- Mobile Responsive Dashboard
- Drill-through Pages
- Tooltip Reports
- Forecasting using Power BI Analytics

---

# 💡 Learning Outcomes

Through this project, I gained practical experience in:

- Building end-to-end Power BI dashboards
- Designing business KPIs
- Writing DAX measures
- Cleaning and transforming data
- Creating interactive reports
- Storytelling through data visualization

---

# 👨‍💻 Author

**Aritra Banerjee**

Final Year B.Tech (Electronics & Computer Science Engineering)

Aspiring Data Analyst | Power BI Developer | Python Developer | Machine Learning Enthusiast

### Connect with Me

- LinkedIn: *(Add your LinkedIn URL)*
- GitHub: *(Add your GitHub URL)*

---

⭐ If you found this project useful, consider giving it a star!
