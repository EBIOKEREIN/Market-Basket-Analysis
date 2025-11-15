Overview
This project performs Market Basket Analysis (MBA) on grocery store transaction data to identify purchasing patterns and product associations. By leveraging the Apriori algorithm, we uncover which products are frequently bought together, enabling strategic business decisions around product placement, promotional bundles, and cross-selling opportunities.
What is Market Basket Analysis?
Market Basket Analysis is a data mining technique that discovers relationships between items purchased together. It answers critical retail questions like:

"What products do customers buy together?"
"How can we optimize product placement?"
"Which items should we bundle in promotions?"
"What recommendations can increase basket size?"


Business Problem
Retail businesses face several challenges:

Suboptimal Product Placement - Products aren't strategically positioned to encourage additional purchases
Low Basket Size - Customers purchase fewer items per transaction than they potentially could
Missed Cross-Selling - Lack of intelligent product recommendations
Inefficient Inventory - Poor understanding of complementary products
Weak Promotional Strategy - Generic discounts without data-driven bundling

Solution
Through comprehensive Market Basket Analysis, this project provides:

✅ Data-driven product placement strategies
✅ High-value promotional bundle recommendations
✅ Intelligent cross-selling opportunities
✅ Optimized inventory management insights
✅ Quantifiable business impact projections


Dataset
Overview

Source: Groceries transaction dataset
Format: CSV (Member_number, Date, itemDescription)
Size: ~15,000 transactions
Products: 169 unique items
Time Period: Multi-year transaction history
Average Basket Size: 4-5 items per transaction

Total Transactions:      ~15,000
Unique Customers:        ~15,000
Unique Products:         169
Total Items Sold:        ~67,500
Date Range:              2020-2023
Sparsity:               High (typical for retail data)


Key Findings

Top Product Associations
1. Strongest Rules (by Lift)
Rule                                              | Support | Confidence | Lift
--------------------------------------------------|---------|------------|------
other vegetables, whole milk → root vegetables    | 4.74%   | 43.5%      | 3.03
tropical fruit, yogurt → whole milk               | 3.56%   | 51.8%      | 2.02
root vegetables, yogurt → whole milk              | 3.89%   | 56.3%      | 2.20
rolls/buns, root vegetables → other vegetables    | 4.93%   | 50.2%      | 2.88

2. Most Popular Pairs (by Support)
Product Pair                              | Support | Frequency
------------------------------------------|---------|----------
Whole Milk + Other Vegetables             | 8.94%   | 1,338 transactions
Whole Milk + Rolls/Buns                   | 5.67%   | 848 transactions
Other Vegetables + Root Vegetables        | 4.74%   | 709 transactions
Whole Milk + Yogurt                       | 4.63%   | 693 transactions
Other Vegetables + Yogurt                 | 4.37%   | 653 transactions

3. Top Individual Products
Whole Milk - Appears in ~25% of all transactions
Other Vegetables - Second most popular item
Rolls/Buns - Strong bakery category performer
Soda - Popular beverage choice
Yogurt - Dairy category leader
