Revenue & Cohort Analysis
Overview

This project analyzes subscription and charge data to answer two business questions:

How do Fiction Box subscriptions perform over time in terms of revenue and cancellations?

Which products are the top sellers and which are underperforming, based on recent revenue?

The analysis is based on subscription creation data and charges processed in the last three months.

Data Used

Subscriptions_by_creation_date.xls
Contains subscription details such as creation date, product SKU, and cancellation status.

Charges_Processed.xls
Contains individual charge records including charge date, product SKU, subscription ID, and revenue.

Only successful charges from the last three months are used for revenue analysis.
Question 1 – Fiction Box Cohort Analysis

Cohorts are created using the subscription creation month.

Only subscriptions with SKU ABOS4FICTION|SUB are included.

Revenue is calculated from charges in the last three months.

Two outputs are generated:

Month-wise revenue cohort table

Cancellation summary by cohort

This helps understand how different batches of Fiction Box subscribers behave over time.

Question 2 – Product Performance Analysis

All successful charges from the last three months are analyzed.

Revenue is grouped by the actual charged product (line_item_sku).

Products are ranked based on total revenue.

The analysis highlights:

Top two selling products

Underperforming products with brief explanations

