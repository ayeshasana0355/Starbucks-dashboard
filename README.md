# ☕ Starbucks Beverage Analytics Dashboard — Brewing Insights. Fueling Connections.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

> An interactive Power BI dashboard analysing Starbucks beverage data — exploring calories, caffeine content, sugar levels, and beverage category distribution across the global menu.

---

## 🧾 Project Overview

This dashboard transforms Starbucks nutritional data into a visually engaging, branded analytics experience. It helps understand how different beverage categories compare in terms of calories, caffeine, and sugar — while showcasing Starbucks' global presence through an interactive world map.

The design is inspired by Starbucks' iconic green branding with rich imagery and a clean, consumer-friendly layout.

**Datasets used:** `starbucks.csv` · `directory.csv`

---

## 📸 Dashboard Preview

![Starbucks Dashboard](https://github.com/ayeshasana0355/Starbucks-dashboard/blob/main/Starbucks%20dashboard.pdf?raw=true)

> For the best interactive experience, download the `.pbix` file and open it in Power BI Desktop.

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| Total Beverages | 33 |
| Average Sugar | 33.02g |
| Average Calories | 194.30 kcal |
| Average Caffeine | 81mg |

---

## ✨ Key Features

### 🔢 KPI Cards
- Total beverages, Average Sugar, Average Calories, Average Caffeine
- Custom icon-based KPI design matching Starbucks branding

### 🍃 Calorie & Caffeine Analysis
- Average Calories by Beverage Category — area chart showing Smoothies and Frappuccino lead
- Average Caffeine by Category — bar chart for quick comparison
- Top 5 Highest Caffeine Beverages with product images:
  - Coffee (293.75mg) · Classic Espresso (122.07mg) · Frappuccino Blended (101.81mg) · Frappuccino Light (99.58mg) · Iced Beverages (98.53mg)

### 🌍 Global Presence Map
- Interactive Bing Maps visual showing Starbucks locations worldwide
- Coverage across North America, Europe, Asia, Africa, and South America

### 🥧 Beverage Category Distribution
- Donut chart showing category split: Classic Espresso (25%), Frappuccino variants, Tazo Tea, Shaken Iced, Signature, Smoothies

### 🎛️ Dynamic Filters
- Protein Range slicer
- Beverage Prep slicer

---

## 🛠️ Technical Highlights

### DAX Measures
- Average Calories, Average Caffeine, Average Sugar per category
- Total Beverage count
- Top N ranking for highest caffeine beverages

### Power Query (ETL)
- Data cleaning and standardisation across `starbucks.csv` and `directory.csv`
- Merging store directory data with beverage nutritional data
- Null handling and data type corrections

### Data Modelling
- Relationship between beverage data and store directory for geographic mapping
- Calculated columns for category grouping and ranking

### UI & Branding
- Custom Starbucks-themed colour palette (deep green, white, cream)
- Integrated product imagery for top beverage cards
- Starbucks logo and branded cup visual for dashboard identity

---

## 🔍 Key Findings

- Coffee (plain) has by far the highest caffeine at 293.75mg — nearly 2.5x the next category
- Smoothies and Frappuccino beverages are the most calorie-dense categories (0.28K average)
- Classic Espresso is the most represented category at 25% of the menu
- Caffeine levels drop significantly from espresso-based drinks to tea and blended options
- Starbucks presence is strongest in North America and Asia

---

## 📁 Project Structure

```
Starbucks-dashboard/
├── Starbucks dashboard.pbix     # Power BI file
├── Starbucks dashboard.pdf      # Dashboard PDF preview
├── starbucks.csv                # Beverage nutritional data
├── directory.csv                # Global store directory data
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/ayeshasana0355/Starbucks-dashboard.git
   ```
2. Open `Starbucks dashboard.pbix` in **Power BI Desktop**
3. Ensure `starbucks.csv` and `directory.csv` are in the same folder
4. Click **Refresh** to load the data
5. Use the Protein Range and Beverage Prep slicers to explore

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development & branding |
| DAX | Nutritional metrics & ranking |
| Power Query (M) | Data cleaning & merging |
| Bing Maps | Global store presence visualisation |
| Excel / CSV | Source data preparation |

---

## 🤝 Connect

If you enjoyed this project or want to discuss data visualisation, connect on [LinkedIn](https://linkedin.com/in/yourprofile) or open an issue.

---

*Built with 💚 using Power BI | Inspired by Starbucks' global brand*
