Amazon Products — Power BI Analytics Dashboard

An interactive Amazon Products Analytics Dashboard built in Microsoft Power BI to analyze product performance, pricing, discounts, categories, ratings and customer review activity.

The project transforms Amazon product-level data into a multi-page business intelligence dashboard designed to answer practical questions such as:

Which product categories attract the most customer attention?

How are ratings distributed across products?

What is the relationship between product price and customer ratings?

Which products/categories use the highest discounts?

How do discount levels vary across the catalog?

Which products generate the largest volume of customer ratings/reviews?

How can pricing, discounting, and customer feedback be evaluated together?

Project Overview

Item

Details

Project Type

Business Intelligence / Data Visualization

Tool

Microsoft Power BI

File

AMAZON.pbix

Primary Dataset

Amazon product-level data

Main Dimensions

Product, Main Category, Rating, Discount Percentage

Main Measures

Total Products, Average Rating, Total Rating Count, Average Discount %

Dashboard Pages

4

Analysis Areas

Executive Overview, Pricing & Discounts, Product & Category Analysis, Customer Reviews

Business Objectives

The dashboard is designed to provide a consolidated view of Amazon product performance and customer engagement.

1. Product Performance

Understand the size and composition of the product catalog and identify products/categories receiving significant customer attention.

2. Pricing Strategy

Examine product prices and investigate how pricing relates to customer ratings and product positioning.

3. Discount Strategy

Analyze discount percentages and group products into discount bands to understand the overall discounting strategy.

4. Category Analysis

Compare major product categories by product volume, customer engagement and performance indicators.

5. Customer Reviews

Use rating counts and rating distributions as indicators of customer engagement and product popularity.

Dashboard Structure

The report contains four analytical pages, each focused on a different business question.

1. Executive Overview

The Executive Overview provides a high-level snapshot of the Amazon product catalog.

<img width="1898" height="947" alt="Executive Overview" src="https://github.com/user-attachments/assets/de49c1ec-2387-4f1c-8689-3a6cc9145e89" />


Key KPIs

Total Products

Average Rating

Total Rating Count

Average Discount %

Visual Analysis

The page combines:

Category-level rating-count analysis

Rating distribution by product count

Price vs. average rating analysis

Interactive slicers for:

Main Category

Rating

Discount Percentage

Purpose

This page is intended for users who need a quick understanding of overall catalog performance before drilling into pricing, categories, or customer reviews.

2. Pricing & Discount Strategy

The Executive Overview provides a high-level snapshot of overall catalog performance, allowing users to quickly identify key trends and insights before drilling down into pricing, categories, discounts, and customer reviews.
<img width="1912" height="971" alt="Pricing   Discont Strategy" src="https://github.com/user-attachments/assets/d8fcd38c-85a4-4d1b-ad6a-548eb8ddb8a2" />


Analysis Included

Product prices across the catalog

Distribution of products by discount band

Category-level pricing analysis

Core product and customer metrics

Interactive filtering by:

Main Category

Rating

Discount Percentage

Key Questions

How are products distributed across different price levels?

Which discount bands contain the most products?

How does pricing differ between product categories?

Are heavily discounted products concentrated in particular categories?

Business Value

The page can support pricing and promotional decisions by helping identify patterns in discounting and product positioning.

3. Product & Category Analysis

This page provides a more detailed view of the product catalog.
<img width="1913" height="990" alt="Product   Category Analysis" src="https://github.com/user-attachments/assets/e89dff0e-f320-4ec4-8cb2-8f52b8c9c257" />


Analysis Included

Product count by main category

Category-level comparisons

Product-level analysis

Product names and performance indicators

Category and product hierarchy analysis

Key Questions

Which categories contain the largest number of products?

Which products stand out within their categories?

How does product performance vary across categories?

Where are the strongest opportunities for category-level investigation?

Business Value

This view is useful for category managers, analysts and decision-makers who need to move from portfolio-level trends into individual product and category analysis.

4. Customer Review Analysis

The Customer Review page focuses on customer engagement and product feedback.
<img width="1917" height="988" alt="Customer Review" src="https://github.com/user-attachments/assets/4fb3e3b3-20d1-49ad-9770-82f38274a258" />


Analysis Included

Rating distribution

Product-level review/rating activity

Product names with category context

Customer rating counts

Average rating KPI

Key Questions

How are customer ratings distributed?

Which products receive the most customer feedback?

Are highly reviewed products concentrated in specific categories?

How can review volume be used alongside ratings to evaluate product visibility and engagement?

Important Note

A high rating count represents customer engagement/review volume, not necessarily high product quality. Rating count and average rating should therefore be interpreted together.

Key Metrics

The dashboard uses several core metrics to summarize the dataset.

Total Products

Measures the number of products represented in the dataset.

Average Rating

Calculates the average customer rating across the selected products/filter context.

Total Rating Count

Represents the total number of ratings/review counts associated with the selected products.

Average Discount %

Represents the average discount percentage within the current filter context.

Discount Band

Products are grouped into discount ranges to make discounting patterns easier to compare visually.

Interactive Filters

The report provides slicers that allow users to dynamically filter the analysis.

Main Category

Filter the dashboard to a specific product category.

Rating

Analyze products within selected customer-rating ranges.

Discount Percentage

Investigate products according to their discount level.

Because the pages use interactive Power BI filtering, selecting a value on a slicer updates the relevant visuals and KPIs across the page.

Data Model / Fields

The report is built around an Amazon product table containing fields used for product, pricing, category and customer-feedback analysis.

Key fields used by the dashboard include:

product_name
Main Category
rating
rating_count
actual_price
discount_percentage

Additional calculated/cleaned fields and measures used by the report include:

Clean Price
Clean Discounted Price
Discount Band
Total Products
Average Rating
Total Rating Count
Avg Discount %

Analytical Approach

The dashboard follows a simple business intelligence workflow:

Raw Amazon Product Data
          │
          ▼
   Data Preparation
          │
          ▼
  Clean / Standardize Fields
          │
          ▼
   Create Measures & Groups
          │
          ▼
   Build Interactive Visuals
          │
          ▼
     Business Analysis

The analysis combines:

Descriptive statistics

Category segmentation

Price analysis

Discount analysis

Rating analysis

Review-volume analysis

Interactive filtering

Technologies Used

Microsoft Power BI

Used for:

Data modeling

Data transformation

Calculated measures

Interactive dashboards

KPI cards

Slicers

Charts and tables

Cross-filtering

Business intelligence reporting

Power BI Visuals

The report includes visual types such as:

KPI/Card visuals

Clustered bar charts

Clustered column charts

Scatter plots

Tables

Pivot/matrix-style tables

Slicers

Images and dashboard design elements

Repository Structure

A recommended GitHub repository structure is:

amazon-products-powerbi/
│
├── README.md
├── AMAZON.pbix
│
├── assets/
│   ├── executive-overview.png
│   ├── pricing-discount-strategy.png
│   ├── product-category-analysis.png
│   └── customer-review.png
│
└── docs/
    └── project-documentation.md


Getting Started

Prerequisites

To open and explore the dashboard, install:

Microsoft Power BI Desktop

Windows environment capable of running Power BI Desktop

Installation

1. Clone the repository

git clone https://github.com/<your-username>/amazon-products-powerbi.git

2. Navigate to the project

cd amazon-products-powerbi

3. Open the Power BI file

Open:

AMAZON.pbix

using Microsoft Power BI Desktop.

4. Explore the report

Navigate through the four dashboard pages:

Executive Overview
        ↓
Pricing & Discount Strategy
        ↓
Product & Category Analysis
        ↓
Customer Review

Use the slicers to investigate specific categories, ratings, and discount levels.


Executive Overview

![Executive Overview](assets/executive-overview.png)

Pricing & Discount Strategy

![Pricing & Discount Strategy](assets/pricing-discount-strategy.png)

Product & Category Analysis

![Product & Category Analysis](assets/product-category-analysis.png)

Customer Review

![Customer Review](assets/customer-review.png)

💡 Example Business Questions

This dashboard can be used to investigate questions such as:

Product Portfolio

How large is the Amazon product catalog?

Which categories contain the most products?

Which products receive significant customer attention?

Pricing

How are products distributed by price?

Does price appear to be associated with customer ratings?

Which categories have higher or lower typical prices?

Discounts

What percentage of products receive substantial discounts?

Which categories rely more heavily on discounts?

How does the discount distribution change when filtering by rating?

Customer Engagement

Which products have the highest rating counts?

How is the overall rating distribution shaped?

Do highly reviewed products also maintain strong average ratings?

Recommended Interpretation Framework

When analyzing the dashboard, avoid evaluating a product using only one metric.

A more reliable approach is to consider:

Product
   │
   ├── Price
   │
   ├── Discount %
   │
   ├── Average Rating
   │
   └── Rating Count

For example:

High rating + high rating count → strong evidence of positive customer reception at scale.

High rating + low rating count → positive signal, but based on less customer feedback.

Low rating + high rating count → potentially important product-quality/customer-satisfaction issue.

High discount + high rating count → potentially strong promotional visibility and customer engagement.

High discount + low rating → discounting may not be sufficient to overcome product dissatisfaction.

These are analytical patterns rather than causal conclusions.

Potential Future Improvements

The dashboard can be extended with additional analytical capabilities.

Advanced KPIs

Median product price

Median discount

Average discounted price

Minimum/maximum price

Review-to-product ratios

Advanced Visualizations

Top 10 products by rating count

Top 10 products by rating

Price distribution histogram

Discount vs. rating relationship

Category profitability proxy

Rating distribution by category

Pareto analysis of customer engagement

Time-Series Analysis

If historical data becomes available:

Price changes over time

Discount changes over time

Rating growth

Review growth

Product performance trends

Advanced Analytics

Potential future additions include:

Product segmentation

Outlier detection

Correlation analysis

Customer sentiment analysis from review text

Predictive modeling

Category opportunity scoring

Intended Audience

This project is useful for:

Data analysts

Business intelligence analysts

Power BI developers

E-commerce analysts

Product managers

Category managers

Marketing analysts

Students building data analytics portfolios

Skills Demonstrated

This project demonstrates practical skills in:

Power BI dashboard development

Data visualization

Business intelligence

KPI design

Interactive report design

Product analytics

Category analysis

Pricing analysis

Discount analysis

Customer review analysis

Exploratory data analysis

Business storytelling


Acknowledgements

This project was created as a Power BI analytics project focused on transforming Amazon product data into an interactive business intelligence experience.

If you find the project useful, consider ⭐ starring the repository.


