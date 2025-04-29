# Amazon Product Review Analysis

##  Problem Statement
Do deeper discounts lead to better product ratings?  
Which categories perform best in terms of customer satisfaction?  
In this project, I analyzed a real Amazon product dataset to uncover insights on customer sentiment, pricing, and product categories.

---

##  Data Source
- Dataset: Kaggle (Amazon Product Reviews)
- Columns: `product_name`, `category`, `discount_percentage`, `rating`, `rating_count`, `review_content`, etc.

---

##  Tools & Approach
- Python (Pandas, Seaborn, Matplotlib)
- Google Colab Notebook
- Data Cleaning & Feature Engineering
- EDA: Value counts, groupby aggregation, correlation
- Visualizations: Bar plots, scatter plots, correlation analysis

---

##  Key Findings
-  **Most Reviewed Categories**: Electronics, Fashion, and Home Decor dominate in review volume
-  **Highest Rated Categories**: Books and Home Decor have the best average customer ratings
-  **Discount vs Rating**: Correlation is **-0.16**  
  → Higher discounts do not lead to better ratings — in fact, slightly worse

---

##  Business Impact
- Businesses shouldn’t rely on discounts to drive customer satisfaction — quality matters more
- Focus marketing and inventory efforts on categories that perform well in both volume and rating
- Improve post-sale experience especially for high-discount items to avoid negative reviews

---

##  What I Learned
- Cleaned messy real-world data with inconsistent formats (e.g., "64%")
- Converted string-based numeric fields for analysis (e.g., discount %, rating)
- Built new features like `high_discount` flag
- Analyzed relationships between discounting and customer sentiment
- Practiced visual storytelling for insight communication

---

##  Project Links
-  Blog Post: *Coming soon*
-  LinkedIn Summary Post: *Coming soon*
-  One-Pager PDF: *Coming soon*
-  Notebook: [`notebook/amazon_review_analysis.ipynb`](notebook/amazon_review_analysis.ipynb)
