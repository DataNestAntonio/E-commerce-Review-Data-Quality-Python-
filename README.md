# JCPenney E‑Commerce Analysis on Python
This project analyses JCPenney’s online product reviews to compare numeric star ratings with text sentiment. Using Python-based data cleaning, visualisation, and sentiment analysis, it uncovers a 31.1% gap between low ratings and predominantly positive review text, suggesting a potential issue with the rating interface rather than product quality.
​

Project Goals
- Clean and validate multi-source retail data (CSV and JSON)
- Explore review score distributions and product engagement
- Apply sentiment analysis (VADER) to written reviews
- Compare numeric ratings vs. sentiment to detect misalignment
- Translate findings into business recommendations for JCPenney
​

Data
The original dataset includes:
- 39,063 customer reviews
- 7,982 products
- 4,998 unique users
- CSV files for products, reviews, users
- JSON files with additional product and reviewer metadata
​
Raw data is also included in this repo.

Methods
- Data manipulation and quality checks with pandas and numpy
- Visualisation with matplotlib and seaborn (e.g., violin plots, lollipop chart, regression plot)
- Sentiment analysis using VADER to classify reviews as positive, negative, or neutral
- Comparative analysis between rating distribution and sentiment distribution
​

Key Findings
58.8% of ratings fall in the 0–1 range, suggesting widespread dissatisfaction at first glance

89.8% of review texts are classified as positive, revealing a strong positive sentiment

A 31.1% gap between low ratings and positive sentiment points to a likely interface or rating-scale design issue rather than a product quality crisi
