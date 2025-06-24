# 🏨 Airbnb Market Insights: Chicago & New Orleans (Power BI Dashboard)

This project presents a comprehensive Power BI dashboard created using Airbnb data from **Chicago** and **New Orleans**. The original datasets were unstructured and messy, so I focused on **cleaning, transforming, and visualizing only the most relevant data** to generate actionable insights.

---

## 📊 Dashboard Overview

![Dashboard Screenshot](./assets/dashboard_image.png)

The dashboard explores key business metrics for short-term rentals, including:

- **Number of Reviews by Year** – Tracks growth in guest interactions
- **Monthly Availability Trends** – Identifies peak and low seasons
- **Number of Hosts by Month** – Helps monitor host engagement across time
- **Sum of Prices by Neighborhood** – Reveals high-value areas like Central Business District
- **Top 10 Hosts by Investment** – Highlights top performers based on listing volume and review count
- **Room Types Breakdown** – Distribution of entire units, private rooms, etc.
- **Review Count by Quarter** – Seasonal review trends
- **Geographical View of Neighborhoods** – Displays listing density across mapped regions
- **Dynamic Price vs Availability Analysis** – Visualizes daily patterns in pricing and occupancy

---

## 🔍 Key Insights

- 📈 The number of reviews has grown steadily year-over-year.
- 🏙️ The **Central Business District** shows the highest average listing prices.
- 🛏️ **Entire apartments** dominate the listing types.
- ❄️ **January and Q1** see the highest hosting and review activity.
- 📌 A few key hosts account for a significant portion of listings and reviews.

---

## 🧹 Data Cleaning & Transformation

The original datasets were messy and inconsistent, so I:

- Removed nulls and irrelevant columns
- Standardized date formats and text values
- Filtered out extreme outliers
- Merged data from both cities into a unified model
- Created custom DAX measures and calculated columns (e.g., `Average Price`, `Total Reviews`, `Availability Days`)

---

## 🛠 Tools & Technologies

- **Power BI** (Desktop)
- **DAX** (Data Analysis Expressions)
- **Power Query** for ETL
- Visuals used: Pie charts, Bar/Column charts, Tree maps, Maps, Line charts

---

## 📁 Folder Structure

/assets
└── dashboard_image.png
/data
└── chicago_data.csv
└── new_orleans_data.csv
Dashboard.pbix
README.md

---

## 🚀 How to Use

1. Clone this repository
2. Open `Dashboard.pbix` in Power BI Desktop
3. Refresh the data source (update paths if needed)
4. Explore the report or customize it for your own analysis

---

## 👤 Author

**Kumari Shivangi**  
Power BI | Data Analytics | Business Intelligence  
🔗 [LinkedIn](www.linkedin.com/in/kumarishivangi7) (replace with your actual profile)

---

## 🙌 Feedback & Contributions

Found something useful? Star ⭐ this repo!  
Have feedback or want to collaborate? Open an issue or reach out on LinkedIn.

---
