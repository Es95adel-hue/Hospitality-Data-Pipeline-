# 🏨 Hotel Search & Behavioral Data Analytics Project

An advanced end-to-end data analytics and behavioral insights project analyzing large-scale hotel search and booking interactions. This project focuses on data cleaning, outlier detection, statistical modeling, and customer journey funnel analysis to uncover key drivers of conversion and revenue.

---

## 🚀 Project Overview
Understanding user behavior in online travel booking platforms is critical for optimizing revenue and user experience. This project processes a massive dataset of hotel searches, clicks, and bookings to extract strategic KPIs and perform advanced statistical and visual analysis using Python.

---

## 📊 Key Metrics & Advanced KPIs Calculated
* **Average Booking Revenue (ABR):** Evaluates the average gross revenue generated per successful booking.
* **Expected Revenue Per Search:** Measures the monetization efficiency of individual search queries.
* **Booking Abandonment Rate:** Tracks user drop-off points (searches with clicks but no final bookings).
* **Price Elasticity & IQR Outlier Filtration:** Cleans price data and isolates normal market ranges using the Interquartile Range method.
* **Search-to-Click Behavioral Intensity:** Analyzes how search result positions impact user engagement and click-through rates.

---

## 📈 Visualizations & Insights Generated
The project includes custom advanced visualizations stored in the repository:
1. **Position Comparison Box Plot (`position_comparison.png`):** Compares search result rankings between clicked and non-clicked items.
2. **Cleaned Price Distribution (`price_distribution.png`):** Highlights core pricing frequencies after filtering out extreme outliers.
3. **Customer Journey Funnel (`customer_funnel.png`):** Visualizes drop-offs from total searches to clicks and final bookings.

---

## 🛠️ Tech Stack & Libraries
* **Python** (Core programming language)
* **Pandas & NumPy** (Data manipulation, chunking, and statistical aggregations)
* **Matplotlib** (Advanced data visualization and custom plotting)

---

## 📁 Repository Structure
```text
├── Hotel_Search_Advanced_Analytics.ipynb   # Main Jupyter Notebook with all codes
├── customer_funnel.png                     # Customer journey visualization
├── price_distribution.png                  # Cleaned price distribution plot
└── README.md                               # Project documentation