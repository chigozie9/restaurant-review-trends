# Restaurant Review Trends and Sentiment Analysis

This project analyzes restaurant reviews using text processing and sentiment analysis to uncover patterns in customer feedback over time. The goal is to identify sentiment trends, review frequency, and common topics mentioned by customers.

---

## 📁 Files Included

- `restaurant_eda.py` – Main Python script for data cleaning, sentiment analysis, and visualizations
- `restaurants_reviews.csv` – Dataset containing textual reviews, ratings, and time descriptions
- `review_trends.png` – Line chart showing average rating and sentiment trends over time
- `sentiment_chart.png` – Bar chart showing number of reviews per period
- `review_wordcloud.png` – Word cloud visualizing common review words
- `restaurant-reviews.qmd` – Project summary report written in Quarto

---

## 🔍 Key Features & Insights

- Uses **TextBlob** to compute sentiment polarity of each review  
- Groups reviews by period to track changes in:
  - Average rating
  - Average sentiment
  - Volume of reviews

### Sample Insights:
- Sentiment and rating do not always trend in the same direction
- Seasonal or event-based fluctuations are visible in review frequency
- Frequent terms in reviews include service, food, atmosphere, etc.

---

## ⚙️ Tools & Techniques

- `pandas` for data manipulation
- `TextBlob` for sentiment scoring
- `matplotlib` for visualization
- `WordCloud` for text-based image generation
- Basic EDA and time-based aggregation

---

## 📌 Summary

This project demonstrates how to process real customer feedback at scale and translate raw reviews into actionable visual trends. It’s useful for understanding public perception, seasonal sentiment swings, and customer priorities over time.
