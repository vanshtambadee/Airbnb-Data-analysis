# Airbnb-Data-analysis

#  Airbnb Data Analysis – Exploratory Data Analysis (EDA) Project

##  Overview

This project involves performing exploratory data analysis (EDA) on Airbnb listings data to understand pricing patterns, availability, host behavior, and location-based trends. The goal is to uncover meaningful insights using visual and statistical techniques.

---



### Objectives:

* Analyze distribution of listing prices
* Understand availability trends and booking density
* Explore host activity, reviews, and neighborhood popularity
* Identify potential factors that affect price and occupancy

---

##  Dataset

* **Source**: Inside Airbnb ([http://insideairbnb.com/](http://insideairbnb.com/)) or Kaggle
* **City**: \[Specify city, e.g., New York, Bangalore, etc.]
* **Size**: \~50,000+ listings
* **Fields**: Listing ID, Name, Host ID, Room Type, Price, Minimum Nights, Number of Reviews, Availability, Neighbourhood, Latitude, Longitude

---

##  Tools & Libraries Used

* **Python 3.x**

  * `pandas`, `numpy` – data manipulation
  * `matplotlib`, `seaborn` – visualization
  * `plotly` – interactive plotting
  * `Jupyter Notebook` – analysis and documentation

---

##  EDA Process

### 1. Data Cleaning

* Removed null values and duplicates
* Filtered out extreme outliers in price and minimum nights
* Converted data types and handled missing values

### 2. Univariate & Bivariate Analysis

* Distribution of room types and neighborhoods
* Price distribution with log transformation
* Correlation heatmaps for numeric fields
* Availability vs Room Type trends

### 3. Geospatial Analysis

* Plotted listings using latitude and longitude
* Identified popular areas based on number of listings and reviews
* Mapped average prices by location

---

##  Key Insights

*  **Price Range:** Majority of listings priced between \$50–\$150
* 🛏 **Most Common Room Type:** Entire home/apartment
*  **Top Neighborhoods:** Downtown and Central areas had highest listing density
*  **High Availability:** Listings with more than 300 days/year availability were mostly managed by commercial hosts


```

---

##  Results & Impact

* Identified pricing outliers and availability patterns for better decision-making
* Helped understand location trends and neighborhood saturation
* Created clear visual reports for stakeholders or academic showcase

---

##  Future Improvements

* Add predictive modeling (price prediction using regression)
* Build a dashboard using Streamlit or Tableau
* Include guest review sentiment analysis

---

