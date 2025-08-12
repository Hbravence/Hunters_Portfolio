

# 🌟 Featured Projects  
Explore a curated selection of modular systems and predictive analytics.

---

## 🌐 Driver-Side Alpha (DSA)

**Overview**  
A predictive analytics platform that identifies high-demand windows for rideshare drivers by clustering **event** and **flight data**. Designed for modular deployment across cities and scalable cloud integration.

**Data Sources**  
- **SeatGeek API** – Weekly event data  
- **Flight Schedule API** – Weekly flight arrival/departure data

**Modeling & Clustering**  
- **Flight data**: clustered using **Mean-Shift** for time-density analysis  
- **Event data**: clustered using **DBSCAN** with **Haversine logic** for geospatial grouping

**Visualization**  
- Built with **Dash + Plotly**  
- Interactive dashboards per city  
- Geospatial maps for event clusters  
- Timeline graphs for flight density windows  
- Modular Python functions for reusable UI components

**Design Intent**  
- Each city functions as a node with localized pipelines  
- Architecture supports multi-city scaling and cloud-native migration (AWS S3 + Athena)  
- Reflects Hunter’s ethos of **modular living, emotional sovereignty, and design coherence**

🔗 [View Project](https://github.com/Hbravence/Driver_Side_Alpha/tree/main)

---

## 📝 Yelp Sentiment Analysis vs. Star Ratings

- **Data Collection** – Extracts Yelp reviews using **SerpApi** and normalizes responses into a structured **DataFrame**  
- **Sentiment Analysis** – Applies **VADER lexicon** to classify reviews into **Positive, Neutral, Negative**, and **Compound** scores  
- **Key Finding** – Sentiment does not always correlate with star ratings, revealing bias in customer feedback  
- **Future Improvements** – Plans to refine analysis using **BERT/RoBERTa** and integrate **spaCy NER** to extract themes

🔗 [View Project](https://github.com/Hbravence/Yelp_Reviews/tree/main)

---

## 🕵️ IMDb Top 250 Web Scraping

- **Scraping Method** – Uses **Selenium** to extract dynamically loaded data  
- **Key Insight** – Identifies **1994** as the most frequent release year in IMDb’s Top 250  
- **Data Storage** – Saves results as a **CSV file**

🔗 [View Project](https://github.com/Hbravence/WebScrape_IMDB/tree/main)

---

## 📊 Stock Forecasting with SARIMAX

- Retrieves stock data via **Yahoo Finance API**  
- Cleans, analyzes, and tests for **seasonality & stationarity**  
- Optimizes **SARIMAX model hyperparameters** for improved forecasting

🔗 [View Project](https://github.com/Hbravence/AMZN_Forecasting/blob/main)

---

## ⚙️ Realtors API

- Retrieves real estate data from the **Realtor.com API**  
- Converts raw JSON into a structured **Pandas DataFrame**  
- **Market Price Evaluation** – Compares latest estimates vs. asking prices  
- **Feature Correlation** – Analyzes how beds, baths, and square footage impact pricing  
- **Random Forest** – Predicts price using core features

🔗 [View Project](https://github.com/Hbravence/Realtors_api_anaylsis/blob/main)

---

## 🚀 Java FBA Orders

- **Tech Stack** – Java, Maven, AWS Lambda, AWS S3, Amazon Seller API  
- **Key Functionality** – Serverless pipeline extracts and stores order data in S3  
- **Business Impact**  
  - Automates data extraction, reducing manual errors  
  - Scales for high-volume transactions  
  - Enhances operational insights for fulfillment optimization  
- **Challenges & Learnings** – Iterated cloud architecture for performance  
- **Future Enhancements** – Add Python-based forecasting layer

🔗 [View Project](https://github.com/Hbravence/FBA_Orders_API)
 


## 🏆 Certifications  

These certifications demonstrate my expertise in **data analytics, cloud infrastructure, and business intelligence**.

### 📊 **Microsoft Certified: Power BI Data Analyst Associate**  
✅ Proficient in **Power BI**, data modeling, and dashboard creation.  
✅ Experienced in **data transformation, DAX calculations, and report optimization**.  
🔗 [View Certification](https://learn.microsoft.com/api/credentials/share/en-us/Hunter-4438/119EEC522867D2F6?sharingId=814368B9FE402D82)  

### ☁️ **Microsoft Certified: Azure Data Fundamentals**  
✅ Strong understanding of **Azure data services, cloud storage, and relational databases**.  
✅ Skilled in **data governance, security, and AI-powered analytics**.  
🔗 [View Certification](https://learn.microsoft.com/api/credentials/share/en-us/Hunter-4438/10D8D2BE128E740?sharingId=814368B9FE402D82)  

### 🎓 **Data Analyst Nanodegree (Udacity)**  
✅ Hands-on training in **data wrangling, python development, and statistical analysis**.  
✅ Developed **real-world projects** focused on exploratory data analysis and visualization.  
🔗 [View Certification](https://www.udacity.com/certificate/e/ad57b69a-87f9-11ea-946c-0b56a632aecd)  

### 🔧 **Google Professional Data Engineer Certification** _(Expired, Planning to Recertify)_  
✅ Expertise in **data pipeline design, cloud infrastructure, and machine learning workflows**.  
✅ Hands-on experience with **Google Cloud services**, including **BigQuery, Dataflow, and Pub/Sub**.  
✅ Advanced skills in **data modeling, performance optimization, and security best practices**.  
🔗 [View Certification](https://www.credly.com/badges/6b3153dd-eea2-4aa5-a91f-69177d41f508) _(Previously earned, renewal in progress)_  




---




