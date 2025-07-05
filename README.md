# Amazon-Project-Product-Review(Excel case study)

## Analyzing product and customer review from data  extracted from Amazon
### Role: Junior Data Analyst (Project-Based)

### Tools Used: 
Microsoft Excel (Pivot Tables, Calculated Columns, Dashboarding)

### Project Overview
This project was carried out by analyzing product and customer review on data extracted from Amazon in order to derive insights that could help in  decision-making for product strategy, pricing, marketing, and customer engagement. The dataset was provided as part of a data analytics case study by RetailTech Insights as part of the training excercise.

### Project Scope and Objective
The objective was to analyse patterns in customer reviews, pricing behavior, and product performance. The Key goals are:

- Identifying top-performing products
- Understanding pricing and discount strategies
- Building a dynamic, executive-friendly Excel dashboard

### Dataset Overview
#### Source: Amazon product pages

- Rows: 1,465 products
- Columns: 16 fields including:
- Product details: name, category, actual price, discounted price, rating
- Customer engagement: review count, review titles and content

### Data Preparation
To ensure data integrity and avoid disrupting the original dataset:
- A separate working sheet was created for all analysis and transformations.
- Non-Essential columns (e.g about_product, User_id, User_name, Review_id, review_title, review_content,img_link, product_link 8 columns) were removed to streamline analysis.
- Data types were validated and cleaned for consistency across numerical and categorical fields.
- Extracted relevant values from comma-separated fields as needed for analysis.

### Key Analysis Conducted
Using Excel Pivot Tables, formulas, and calculated columns, the following insights were extracted:

- Average Discount Percentage by Category: E.g., Computers & Accessories had an average discount of ~54%.
- Number of Products per Category: E.g., Electronics had the highest count with 526 products.
- Total Number of Reviews per Category: Electronics again led with over 15 million reviews.
- Top Rated Products: Identified using the highest average rating.
- Average Actual Price vs Discounted Price by Category: Calculated and compared.
- Most Reviewed Products: Ranked based on the number of user reviews.
- High Discount Products: Counted how many had ≥50% discounts.
- Product Rating Distribution: Grouped and visualized the rating spectrum (e.g., 3.0, 4.0, etc.).
- Total Potential Revenue by Category: Derived from Actual_Price × Rating_Count.
- Products by Price Range Buckets: Categorized into <₹200, ₹200–₹500, >₹500.
- Rating vs Discount Correlation: Explored the relationship between higher discounts and customer ratings
- Low Engagement Products: Flagged those with fewer than 1,000 reviews.
- Top Discount Categories: Identified categories with the largest average markdowns.
- Top 5 Products: Ranked based on a combined score of rating and review volume.

### Tools & Techniques
- Microsoft Excel
- Pivot Tables
- Charts (Column, Pie, Scatter)
- IF, TRIM, REPT, RIGHT, LEFT etc.
- Slicers and visual filters

### Final Deliverable: Excel Dashboard
Created a clean and interactive Excel dashboard that features brand-aligned theme using Amazon’s colors, summarizes all the key insights, enabling users to slice, filter, and visualize product trends efficiently.

### This project demostrates:
- Strong Excel-based data analysis skills
- The ability to translate raw data into actionable business insights
- A solid understanding of e-commerce metrics and customer behavior
