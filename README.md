

## **🌟 Featured Projects**
Explore some of my best work:

## 🌐 Driver-Side Alpha (DSA)

### Overview  
A predictive analytics platform that identifies high-demand windows for rideshare drivers by clustering **event** and **flight data**. Designed for modular deployment across cities, with emotionally literate architecture and scalable cloud integration.

### Data Sources  
- **SeatGeek API** – Weekly event data  
- **Flight Schedule API** – Weekly flight arrival/departure data

### Modeling & Clustering  
- **Flight data**: clustered using **Mean-Shift** for time-density analysis  
- **Event data**: clustered using **DBSCAN** with **Haversine logic** for geospatial grouping

### Visualization  
- Built with **Dash + Plotly**  
- Interactive dashboards per city  
- Geospatial maps for event clusters  
- Timeline graphs for flight density windows  
- Modular Python functions for reusable UI components

### Design Intent  
- Each city functions as a node with localized pipelines  
- Architecture supports multi-city scaling and cloud-native migration (AWS S3 + Athena)  
- Reflects Hunter’s ethos of **modular living, emotional sovereignty, and design coherence**

🔗 * [View Project](https://github.com/Hbravence/Driver_Side_Alpha/tree/main)

### **📝 Yelp Sentiment Analysis vs. Star Ratings**
- **Data Collection** – Extracts Yelp reviews using **SerpApi** and normalizes responses into a **structured DataFrame**.
- **Sentiment Analysis** – Applies **VADER lexicon** to classify reviews into **Positive, Neutral, Negative**, and **Compound** scores.
- **Key Finding** – Sentiment **does not always correlate** with the **star rating system**, highlighting potential biases in customer reviews.
- **Future Improvements** – Plans to refine analysis using **BERT/RoBERTa models** and integrate **spaCy’s Named Entity Recognition (NER)** to identify themes in customer feedback.

🔗 [View Project](https://github.com/Hbravence/Yelp_Reviews/tree/main)

## 🕵️ IMDb Top 250 Web Scraping  

- **Scraping Method** – Extracts **dynamically loaded data** using **Selenium** instead of traditional requests-based scraping.  
- **Key Insight** – Determines **1994** as the most frequently occurring release year in the IMDb Top 250.  
- **Data Storage** – Saves results as a **CSV file**.

🔗 [View Project](https://github.com/Hbravence/WebScrape_IMDB/tree/main)

### **📊 Stock Forecasting with SARIMAX**
- Uses **Yahoo Finance API** to retrieve stock data.
- Cleans, analyzes, and tests for **seasonality & stationarity**.
- Optimizes **SARIMAX model hyperparameters** for better forecasting.
  
🔗 [View Project](https://github.com/Hbravence/AMZN_Forecasting/blob/main)

### **⚙️ Realtors API**  
- **Retrieve real estate data** from the **Realtor.com API**.  
- **Convert raw JSON responses** into a structured **Pandas DataFrame** for easy analysis.    
- **Market Price Evaluation** – Compare the **latest estimates** vs. **actual asking prices**.  
- **Feature Correlation** – Analyze how the **number of beds, baths, and square footage** impacts pricing.
- **Random Forest** -- Used number of beds, baths, square footage as features to predict price.  
 
🔗 [View Project](https://github.com/Hbravence/Realtors_api_anaylsis/blob/main)

## 🚀 Java FBA Orders
- **Tech Stack** – Java, Maven, AWS Lambda, AWS S3, API integration  
- **Key Functionality** – Implements a serverless pipeline using AWS Lambda to extract and store Amazon Seller API data in S3  
- **Business Impact** –  
  - **Automates** the extraction of order data, reducing manual processing time and minimizing human error  
  - **Scales efficiently**, allowing seamless data collection for high-volume transactions without additional infrastructure costs  
  - **Enhances operational insights**, enabling businesses to track order trends and optimize fulfillment strategies  
- **Challenges & Learnings** – Experimented with multiple versions for cloud architecture  
- **Future Enhancements** – Forecasting orders in Python for actionable insights  

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




