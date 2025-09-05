# 🏠 Airbnb Data Analysis

## 📖 Overview
This project explores **Airbnb listing data** to uncover insights about pricing, availability, customer preferences, and geographic trends.  
The goal of this analysis is to help understand the Airbnb market and identify patterns that can support **business strategy, customer experience, and investment opportunities**.

---

## 📂 Dataset
- Source: Airbnb open dataset (Kaggle / InsideAirbnb / Provided dataset)  
- Format: CSV/Excel  
- Features include:
  - `id`, `name`, `host_id`, `neighbourhood`, `room_type`
  - `price`, `minimum_nights`, `availability_365`
  - `number_of_reviews`, `reviews_per_month`, etc.

---

## 🔍 Analysis Performed
1. **Data Cleaning**
   - Removed missing values & duplicates  
   - Handled outliers in `price` and `minimum_nights`  
   - Standardized categorical values  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of listings by city & neighbourhood  
   - Popular room types (Entire home vs Private room)  
   - Pricing trends & outlier detection  
   - Availability vs Booking patterns  

3. **Visualizations**
   - Top 10 neighbourhoods by number of listings  
   - Average price by room type  
   - Correlation heatmap of numerical features  
   - Price distribution (histogram, boxplot)  

---

## 📊 Key Insights (Report Summary)
- **Room Type Popularity:** Majority of listings are for *Entire homes/apartments*, followed by *Private rooms*.  
- **Pricing Trends:** Prices vary significantly by neighbourhood. Outliers exist (extremely high-priced listings).  
- **Neighbourhood Trends:** Certain areas (e.g., City Center, Downtown) have the **highest concentration of listings and reviews**.  
- **Availability:** Many hosts list properties for the full year, but actual booking activity is concentrated in seasonal peaks.  
- **Correlation Findings:** Price does not strongly correlate with number of reviews, suggesting that affordability and visibility drive engagement.  

---


## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/airbnb-data-analysis.git
   cd airbnb-data-analysis
