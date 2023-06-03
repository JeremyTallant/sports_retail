# Optimizing Online Sports Retail Revenue
## Description
Sports clothing is a booming sector!

In this notebook, we will use our SQL skills to analyze product data for an online sports retail company.

We will work with numeric, string, and timestamp data on pricing and revenue, ratings, reviews, descriptions, and website traffic.

We will use techniques such as aggregation, cleaning, labeling, Common Table Expressions, and correlation to produce recommendations on how the company can maximize revenue!
## Contents
1. **Counting missing values:** Count the total number of products, along with the number of non-missing values in `description`, `listing_price`, and `last_visited`.
2. **Nike vs Adidas pricing:** Find out how listing_price varies between Adidas and Nike products.
3. **Labeling price ranges:** Create labels for products grouped by price range and `brand`.
4. **Average discount by brand:** Calculate the average `discount` offered by brand.
5. **Correlation between revenue and reviews:** Calculate the correlation between reviews and revenue.
6. **Ratings and reviews by product description length:** Split `description` into bins in increments of one hundred characters, and calculate average `rating` by for each bin.
7. **Reviews by month and brand:** Count the number of `reviews` per `brand` per month.
8. **Footwear product performance:** Create the `footwear` CTE, then calculate the number of products and average revenue from these items.
9. **Clothing product performance:**