# Airbnb-Dashboard
Here is the generated **README.md** for your **Airbnb Power BI Dashboard** project, modeled after your EDA README:

---

# Airbnb Power BI Dashboard Project

<h1 align="center">Airbnb Listings Analysis with Power BI</h1>

<p align="center"> 
<img src="https://upload.wikimedia.org/wikipedia/commons/6/69/Airbnb_Logo_Bélo.svg" alt="Airbnb Logo" height="120px">
</p>

## 📚 Table Of Contents

* 📋 **Project Description**
* 💾 **Project Files Description**
* 🧾 **Dataset Overview**
* 📊 **Dashboard Components**
* ❓ **Business Problem**
* 🛠 **Technologies Used**
* 🔍 **Process and Methodology**
* 📌 **Key Insights**
* 🎯 **Conclusion**

---

## 📋 Project Description

This Power BI project provides an interactive dashboard for analyzing Airbnb listings data. It integrates data from two cities (merged via Python preprocessing) and visualizes insights on pricing, availability, room types, reviews, and geographical distribution. The goal is to empower users with actionable insights for hosts, travelers, and market analysts.

---

## 💾 Project Files Description

* `Capstone module 4.pbix`: Main Power BI report file containing visualizations and dashboards.
* Source Datasets: Preprocessed and merged data of two cities (prepared in Python, not included here).
* `README.md`: Project documentation.

---

## 🧾 Dataset Overview

The dataset comprises Airbnb listings from two major cities, including information on:

* Pricing
* Room types
* Availability throughout the year
* Neighborhood and geolocation
* Number of reviews
* Host and property characteristics

The data was cleaned and merged in Python prior to importing into Power BI.

---

## 📊 Dashboard Components

Key elements included in the Power BI dashboard:

* **Summary Cards:** KPIs such as total listings, average price, and total reviews.
* **Slicers:** Filters for city, neighborhood, room type, and availability range.
* **Bar Charts:** Room type distribution and average price per neighborhood.
* **Line Charts:** Trend of reviews and availability over time.
* **Donut Charts:** Proportion of room types.
* **Tree Maps:** Revenue contribution by neighborhood.

---

## ❓ Business Problem

With the rapid growth of Airbnb, both hosts and guests seek a deeper understanding of:

* Which locations and room types are most profitable?
* What pricing trends exist across neighborhoods?
* How does availability vary throughout the year?
* What is the distribution of reviews and customer feedback across different areas?

This dashboard aims to simplify exploration of these questions for better decision-making.

---

## 🛠 Technologies Used

* **Data Cleaning & Merging:** Python (pandas, numpy)
* **Visualization & Reporting:** Power BI
* **Design Elements:** Slicers, Cards, Filters, Custom Visualizations

---

## 🔍 Process and Methodology

1. **Data Preprocessing in Python**

   * Removed nulls, handled outliers
   * Merged datasets from two cities

2. **Import into Power BI**

   * Data modeling and relationship setup
   * Calculated columns and measures for KPIs

3. **Dashboard Design**

   * Implemented interactive filters
   * Created insightful visualizations for various metrics
   * Included a mobile view for dashboard too

4. **Review and Optimization**

   * Enhanced performance and usability for stakeholders

---

## 📌 Key Insights

* Pricing significantly varies across neighborhoods and room types.
* Entire homes generally command higher prices compared to private rooms.
* Some neighborhoods show a high density of listings and reviews, reflecting tourist hotspots.
* Seasonal patterns affect availability and booking trends.
* Revenue is concentrated in specific high-demand areas.
* Compatible for mobile viewing also

---

## 🎯 Conclusion

This Power BI dashboard offers a comprehensive view of Airbnb data, facilitating:

* Strategic pricing decisions for hosts
* Neighborhood-level analysis for travelers
* Market insights for analysts
* Foundation for further predictive or segmentation analyses

By leveraging data visualization, stakeholders can make informed, data-driven decisions to optimize their Airbnb strategies.
