# Netflix-Product-BI-Analysis
SQL-based Product &amp; business Intelligence analysis using Netflix user behavior data

## 📌 Project Overview
This project analyzes Netflix user behavior to answer key product, business,
and recommendation performance questions using PostgreSQL.

## 🧠 Business Questions Answered
1. Which movies have the highest watch completion rate?
2. Which genres share are most popular within each country?
3. What percentage of recommendations lead to a watch?
4. Who are the most active users and what do they watch?
5. How does engagement differ by subscription type?
6. How long it takes a new user to have their first meaningful interaction (first watch)?

## 🛠️ Tools Used
- PostgreSQL
- SQL (Joins, Aggregations, CTEs, Window Functions)
- PgAdmin
- Kaggle Dataset

## 📊 Key Insights
- By filtering out short-form content and low-engagement titles, long-form movies with high completion rates emerged as key engagement drivers, reinforcing completion          rate as a valuable signal for content promotion and recommendation decisions.
- To account for the dominance of US users in the dataset, genre popularity was evaluated using normalized metrics such as percentage share and per-user engagement, enabling   more accurate insights into regional content preferences.
- Approximately 20% of recommendation events resulted in a watch, indicating that while recommendations play a meaningful role in content discovery, the majority do not        convert into immediate engagement. This suggests opportunities to improve recommendation relevance, timing, and contextual alignment with user intent.
- While movies attract a broader audience, a smaller group of highly active users contributes a disproportionate share of total watch time by spending extended time on long-   form content, particularly TV series. This suggests that movies drive reach, whereas series drive sustained engagement and deeper user retention.
- Standard and Premium users drive the highest total watch time due to their larger user bases, while average completion rates remain consistent (~65–66%) across all           subscription tiers. Basic users show slightly higher completion, suggesting more focused viewing, and Premium+ engagement is similar to lower tiers, indicating that higher-tier features enhance experience rather than consumption.
- Delayed first engagement strongly correlates with increased churn risk.

## 📁 Repository Structure
- `/sql` → SQL scripts used for analysis
- `/insights` → Written conclusions

## 🚀 Why This Project
This project demonstrates my readiness for:
- Product Analyst roles
- Business Intelligence Analyst roles
- Data / Performance Analyst roles
