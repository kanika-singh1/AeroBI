# ✈️ AeroBI
Business Intelligence Project
<br>


## 📌 Background
Flight delays and cancellations continue to be a major challenge for the airline industry, leading to passenger frustration and operational inefficiencies. This project utilizes data warehousing, ETL, machine learning, and visualization techniques to analyze historical flight data, uncover trends, and generate actionable insights to enhance operational efficiency and customer satisfaction.
<br>


## 🎯 Objectives
- Analyze historical flight data to identify trends in delays and cancellations
- Determine key factors contributing to flight disruptions
- Perform sentiment analysis on airline reviews to assess passenger sentiment
- Design and implement a Data Warehouse (DW) using a Star Schema
- Develop interactive dashboards for real-time insights and decision-making
<br>

## 📂 Project Components

### 1️⃣ Datasets
- Flight Delays & Cancellations (3M+ records, 30+ attributes) – [Link]([https://example.com](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023?select=flights_sample_3m.csv)).
- Airline Customer Reviews (23K+ reviews) – [Link](https://www.kaggle.com/datasets/juhibhojani/airline-reviews)
- Airport Metadata (380 records).

### 2️⃣ Exploratory Data Analysis (EDA)
Data Cleaning: Addressed missing values, removed duplicates, and standardized attributes.
Sentiment Analysis: TextBlob and NLTK (VADER) were used to classify airline reviews into positive, neutral, or negative sentiments.
Feature Engineering: Derived key attributes to enhance predictive analysis.

### 3️⃣ Data Warehouse Design & ETL
Star Schema: Built a dimensional model with key dimensions such as Airlines, Airports, Date, Cancellations, and Reviews.
Fact Table: Stores flight-related data, including delays, cancellations, departure, and arrival details.
ETL Pipeline: Implemented using SQL Server Integration Services (SSIS) for seamless data extraction, transformation, and loading.
Slowly Changing Dimensions (SCD Type 2): Applied for tracking changes in airport details over time.

### 4️⃣ Data Visualization & Dashboards
Key Dashboards:
1. Net Promoter Score (NPS) Dashboard
  - Evaluates airline reputation using Promoters, Passives, and Detractors.
  - Analyzes customer satisfaction trends for individual airlines.
2. Airline Performance Dashboard
  - Examines flight delays and cancellations by airline.
  - Investigates root causes of delays, including Carrier, Weather, Security, NAS, and Late Aircraft.
3. Real-Time Flight Tracker Dashboard
  - Monitors live flight status updates.
  - Tracks delays and reasons for disruptions in real time.
<br>

## 🚀 Technologies Used
- **Programming Languages:** Python  
- **Tools & Libraries:** Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, NLTK, TextBlob  
- **Data Warehousing & ETL:** SQL Server, SSIS, SSMS 
- **Data Visualization:** Power BI  
- **Data Source:** Kaggle
<br>

## 📜 Business Implications
The insights derived from this project offer value to multiple stakeholders including:
- Airline Management: Identify and mitigate operational inefficiencies leading to delays and cancellations.
- Customer Service Teams: Address passenger concerns from reviews to improve overall satisfaction.
- Investors & Analysts: Leverage NPS and performance metrics to assess airline reputation.
- Passengers: Make data-driven decisions when selecting airlines based on reviews and reliability scores.
