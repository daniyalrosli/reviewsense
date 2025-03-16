ReviewSense: Advanced Sentiment Analysis for E-Commerce Reviews

Overview

ReviewSense is an advanced sentiment analysis system designed to analyze customer reviews from e-commerce platforms. It extracts sentiment insights to help businesses better understand customer feedback, improve products, and enhance customer satisfaction.

This project applies natural language processing (NLP) techniques, exploratory data analysis (EDA), and machine learning models to classify reviews as positive or negative and generate actionable insights.


Dataset

The dataset contains Amazon product reviews with the following key columns:
- reviewText: The text of the customer review.
- overall: The rating given by the customer (1 to 5 stars).
- reviewTime: Date of the review.
- summary: Summary of the review.

Data Preprocessing & EDA

Steps involved:
- Removed missing/null values.
- Performed tokenization, stopwords removal, and text normalization.
- Extracted review length, word count, and rating distribution.
- Created a sentiment label:
- Positive (1) if rating ≥ 4
- Negative (0) if rating ≤ 3

Sentiment Model Building & Evaluation

![image](https://github.com/user-attachments/assets/7ce8ca32-bd55-49c4-897e-9249ec477b57)

Best Performing Model: Linear SVC (F1-Score: 0.929)

Dashboard Insights:

Explanation:
1. Distribution of Ratings: Most customers gave 5-star ratings, indicating high customer satisfaction.
2. Average Rating by Year: Shows a steady increase in average ratings over the years.
3. Distribution of Review Word Count: The majority of reviews are under 100 words, which indicates concise feedback.
4. Top 10 Most Common Words: Displays the most frequently used words in reviews (e.g., “card”, “work”, “phone”, etc.).
6. Sentiment Distribution: Overwhelmingly positive sentiment dominates (80-90%).

![image](https://github.com/user-attachments/assets/08be7c86-ee5a-498c-968b-466d356c8e61)









