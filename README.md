# Amazon-Sales-Dataset

This project presents Executive Dashboard built from Amazon India product data (1,465 listings, 26.8M reviews).
It transforms raw, unstructured e-commerce data into decision-ready business intelligence using AI-assisted analytics and prompt engineering.
The goal was not just visualization — but to simulate executive decision-making through data.

# Key Highlights
-Built 10+ interactive visualizations using Chart.js (donut, histograms, scatter, ranking tables)
-Processed 1,465 products & 26.8M reviews
-Applied AI-assisted prompt engineering to generate and refine insights
-Delivered CEO-level strategic insights from raw data
-Focused on business impact, not just charts
-Data Processing & Feature Engineering
-Cleaned price fields (₹ symbols, commas → float conversion)
-Extracted top-level categories from hierarchical strings

# Metrics:
-Savings = Actual Price – Discounted Price
-Discount % (normalized)
-Cleaned rating_count (review volume)
-Structured dataset for analytics-ready consumption
-KPI Strip → Total Products, Reviews, Avg Rating, Avg Discount, Avg Savings, Top Category
-Category Distribution → Donut chart (product count)
-Pricing Analysis → Avg price by category
-Discount Behavior → Histogram (10% buckets)
-Customer Sentiment → Rating distribution
-Price Segmentation → Product count by price ranges
-Category Performance → Avg rating (zoomed axis for clarity)
-Savings Analysis → Avg savings by category
-Top Products Table → Ranked by review volume with discount badges
-Correlation Analysis → Scatter plot (Discount % vs Rating)

# AI + Prompt Approach
Instead of manually coding every insight, this project leverages AI as a thinking partner:

-Designed structured prompts to:
-Generate meaningful KPIs
-Suggest relevant visualizations
-Extract business insights from patterns
-Iteratively refined prompts to improve:
-Accuracy
-Clarity
-Business relevance
-Validated AI outputs using data reasoning and statistical logic


# Key Business Insights
-Electronics dominates (36% of catalog) with highest pricing & savings → aggressive discount-led growth strategy
-50–70% discount range is optimal, but has no correlation with ratings → pricing ≠ perceived quality
-₹200–500 segment drives volume, indicating strong mass-market demand
-Office Products is underrepresented but highest rated (4.31★) → expansion opportunity


