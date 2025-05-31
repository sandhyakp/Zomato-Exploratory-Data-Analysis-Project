

# 🍽️ Zomato Exploratory Data Analysis Project

This project explores key trends and insights in the global restaurant industry using the **Zomato Dataset**. It uncovers patterns in restaurant ratings, pricing, cuisine preferences, service availability, and regional differences across cities and countries.

## 📌 Objectives

This analysis is guided by the following research questions:

* **Top-rated Restaurants**: What are the highest-rated restaurants in specific cities or countries?
* **Rating Trends**: How do average ratings vary across different cuisines and price ranges?
* **Most Reviewed Restaurants**: Which restaurants have received the most reviews (votes) regionally?
* **Geographical Distribution**: How are restaurants distributed across cities and countries?
* **Location-Based Patterns**: Are there noticeable geographical patterns in restaurant ratings?
* **Top Cuisines**: What are the most popular cuisines in specific locations?
* **Service Availability**: How many restaurants offer table booking or online delivery services?
* **Delivery vs Ratings**: Is there a correlation between online delivery availability and higher customer ratings?
* **Cost Analysis**: What is the average cost for two people in various regions?
* **Price vs Ratings**: Are higher-priced restaurants generally rated better?

---

## ✨ Key Insights

### 🌍 Global Coverage

* Data spans **15 countries**, including India, USA, UAE, UK, South Africa, and more.

### 🍛 Top Cuisines Worldwide

* **North Indian** is the most common cuisine, followed by:

  * Chinese
  * Fast Food
  * Mughlai
  * Italian

### 💰 Cost Standardization

* Introduced a new column to convert average costs into INR (Indian Rupees), enabling fair cross-country comparisons.

### 📈 Price vs Rating (Work-in-progress)

* Converted prices are analyzed to assess if higher-priced restaurants tend to get better ratings.

### 🏙️ Country & City-Level Insights

* Cities like **Makati**, **Delhi NCR**, and **London** dominate the dataset.
* Preparation is underway for more detailed region-specific insights.

### 🔗 Rich Dataset Merging

* Successfully merged `zomato_data.csv` with `zomato_country_data.csv` for geographic and financial context.

---

## 🧰 Tools & Technologies Used

* **Python** 🐍

  * Data Analysis: `pandas`, `numpy`
  * Visualization: `matplotlib`, `seaborn`, `plotly`
* **Jupyter Notebook**: For interactive data exploration
* **GeoPandas**, **Folium**: For geographic plotting
* **Zomato Dataset**: Publicly available dataset with global restaurant data

---

## 🚀 Why This Project Stands Out

* Tackles **real-world business questions** relevant to the food and hospitality industry.
* Covers **multi-dimensional analysis**: ratings, reviews, cost, services, and geography.
* Offers **interactive visualizations** and insightful correlations between features.
* **Scalable and adaptable** to other restaurant/food industry datasets.

---

## 📁 Dataset Source

The dataset is publicly available and can typically be found on platforms like **[Kaggle](https://www.kaggle.com)** or other open data repositories that host Zomato data snapshots.


## 📊 Sample Visualizations

* ✅ Heatmaps showing average ratings by city
* ✅ Bar charts of top cuisines per country
* ✅ Scatter plots of cost vs rating
* ✅ Choropleth maps of restaurant density


Feel free to **clone this repository**, explore the notebooks, and adapt the analyses to your own city or region. Let the data tell the story of food around the world! 🌍🍴

