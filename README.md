# Project 2: Exploratory Data Analysis (EDA)

## About this project

This is my second project for the data analytics internship.

For this project, I used an e-commerce order dataset and explored it to understand what was happening in the data. I calculated basic statistics, checked trends, looked for unusual values, and wrote down the main observations.

## What I worked on

- Calculated count, mean, and median
- Compared products based on orders and revenue
- Checked payment method usage
- Looked at order-status patterns
- Compared referral sources
- Checked monthly and yearly revenue
- Looked for outliers using the IQR method
- Checked relationships between numerical columns
- Summarised the main findings

## Dataset

The dataset contains **1,200 orders** and **14 columns**.

Some important columns are:

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- PaymentMethod
- OrderStatus
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice

The data covers orders from **January 2023 to June 2025**.

## Some findings

- Total revenue is **1,264,761.96**.
- The average order value is about **1,053.97**, while the median is **823.62**.
- **Chair** generated the highest total revenue among the products.
- **Printer** had the highest number of orders.
- **Online** was the most commonly used payment method.
- **Credit Card** generated the highest total revenue among the payment methods.
- **Instagram** was the strongest referral source by revenue.
- **June 2024** was the highest-revenue month.
- **Cancelled and Returned** orders together made up **41.42%** of all orders.
- The IQR check found **8 high-value TotalPrice outliers**.

## A note about the outliers

I did not automatically delete the outliers.

The unusual TotalPrice values are high-value orders, and they may be genuine purchases rather than data errors. So I kept them and listed the highest-value orders separately for review.

## A note about 2025

The 2025 data only covers January to June. Because of this, I did not treat 2025 as a complete-year comparison with 2023 and 2024.

## What is inside the Excel file?

The `EDA_Analysis.xlsx` file contains:

- Basic Statistics
- Product Analysis
- Payment Analysis
- Order Status
- Referral Analysis
- Coupon Usage
- Yearly Trend
- Monthly Trend
- Outlier Analysis
- Correlation
- Top 10 Orders

Charts are also included for some of the main comparisons and trends.

## Tools used

- Excel
- Python
- Pandas
- GitHub

## What I learned

This project helped me understand that EDA is more than just calculating numbers.

The useful part is looking at the results and asking questions such as which product is doing better, which month had higher revenue, and whether an unusual value is actually an error.

I also learned that an outlier should be checked before removing it.

## Conclusion

Overall, this project gave me good practice with basic data analysis. I was able to find patterns in products, payments, order status, referrals, and revenue over time.

It also helped me understand how raw business data can be turned into simple observations that can be used for further analysis.
