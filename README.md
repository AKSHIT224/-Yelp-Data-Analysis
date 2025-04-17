# -Yelp-Data-Analysis
# 🍽 Yelp Data Analysis for Travel App using PySpark
 
## Akshit Bhandari (Machine Learning Analyst) 

---

## 📌 Project Overview

This project uses the *Yelp Fusion API* to extract restaurant data and performs *big data processing* using *Apache Spark* and *Spark SQL. The goal is to simulate how a **travel recommendation app* can provide personalized food suggestions based on real-time user preferences like rating, price, cuisine, and location.

We designed the system to solve the common traveler’s issue: *“Where should I eat nearby?”* by offering smart, data-driven restaurant recommendations.

---

## 🎯 Key Objectives

- Build a mini recommendation engine using Yelp restaurant data.
- Fetch, transform, and analyze business listings using PySpark.
- Visualize key metrics such as restaurant popularity, pricing trends, and open status.
- Demonstrate a full ETL + analytics pipeline using modern big data tools.

---

## 📊 Data Collection & Features

- *Source*: Yelp Fusion API  
- *Locations Covered*: San Jose, Sunnyvale, Santa Clara, Mountain View, Palo Alto  
- *Data Extracted*:  
  - Business Name  
  - Rating  
  - Price  
  - Categories  
  - Review Count  
  - Location Info  

- *Challenges*:  
  - Handling nested JSON responses  
  - API rate limits  
  - Ensuring at least 1000 rows and 5 clean features per business

---

## 🧠 Data Management & Analysis with PySpark

### Spark Environment
- Initialized a local Spark session using PySpark.
- Loaded Yelp business data into Spark DataFrames.

### Data Operations
- *Filtering*: e.g., only restaurants with rating ≥ 4.0  
- *Grouping*: Count businesses by city, category, or price  
- *Aggregation*: Compute average ratings, price distribution  

### Spark SQL Queries Performed
- Count open/closed restaurants by location  
- Find top-rated restaurants (rating ≥ 4.5, 100+ reviews)  
- Identify popular categories in each city  
- Determine average price level by rating  
- Count restaurants by price tier and review volume  

---

## 📈 Visualization Highlights

Using *Matplotlib* and *Seaborn*, we created:
- Bar charts of top restaurant categories
- Histograms of review counts and ratings
- Heatmaps showing rating vs. price trends
- Pie charts of open vs. closed restaurants

These visuals supported our business idea and helped communicate insights clearly.

---

## 🚀 Tech Stack

- Python  
- Yelp Fusion API  
- Apache Spark & PySpark  
- Spark SQL  
- Matplotlib & Seaborn  
- Jupyter Notebook

---

## 💡 Key Insights

- Most highly rated restaurants are in Mountain View and Palo Alto.
- Price range doesn't always correlate with review count.
- Categories like "Mexican", "Italian", and "Asian Fusion" dominated the dataset.
- Users prefer restaurants with balanced pricing and high review volume.

---

## 🔮 Future Enhancements

- Automate real-time data fetching via scheduled API calls
- Add user feedback loop for personalized recommendation refinement
- Deploy as an interactive Streamlit dashboard for end users

---

## 📞 Contact

*Akshit Bhandari*  
📧 abhandari78@norquest.ca  
📞 +1 (437) 970-9974

---
