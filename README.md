# Swiggy-vs-Zomato-Analysis

## Project Background

Food delivery apps have become integral to urban Indian lifestyles. Swiggy and Zomato together dominate the market, but how do they truly compare in terms of user satisfaction, public sentiment, and service consistency? 

This project aims to go beyond star‐ratings and promotional noise by scraping real user feedback from both the Google Play Store (50,000+ reviews) and relevant Reddit communities (350+ posts).

## Project Overview

This project compares Swiggy and Zomato using user sentiment and financial performance data. I scraped over 50,000 Google Play reviews and Reddit posts, cleaned and analyzed them using Python, NLP techniques, and VADER. 

The key insights were visualized in a dashboard in PowerBI. The dashboard highlights differences in user ratings, sentiment distribution, monthly active users, and financial metrics like revenue and net profit from FY19 to FY25. Swiggy shows stronger user sentiment and higher revenue growth, while Zomato leads in overall sentiment score. The goal was to blend public opinion with business performance to understand how user perception aligns with financial outcomes.

## Tech Stack
- Python 3.8+
- Data handling: pandas, numpy
- Scraping: google-play-scraper, praw
- NLP & Sentiment: nltk (stopwords, lemmatizer), vaderSentiment
- Visualization: matplotlib, seaborn, plotly
- Dashboard: PowerBI

## Conclusion

Zomato leads in both average star rating (4.23 vs. 3.57) and average sentiment score (≈0.34 vs. ≈0.20) on Play Store.
Swiggy exhibits more volatility in daily sentiment—indicating periodic service breakdowns or app issues that create spikes of dissatisfaction. Financially, Zomato also outperforms Swiggy across the years analyzed.


Overall, this project successfully displayed the contrast in the performance of the two major food delivery giants in India - combining public sentiment and financial metrics to offer a clearer view of how each brand is perceived and how they’ve grown.
Establish a near-real-time sentiment dashboard for product and operations teams to catch emerging issues before they trend.

By continuously monitoring and responding to user sentiment—across app reviews and social media—Swiggy and Zomato can stay ahead of service gaps, reinforce customer loyalty, and maintain a competitive edge.
