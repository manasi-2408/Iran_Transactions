# Transaction & Revenue Analysis (Power BI)

## Overview
This project analyzes transactional payment data to identify patterns in transaction volume, net revenue, payment failures, and zero-payment behavior. Python is used for data analysis, and Power BI is used to build an interactive dashboard for business insights.

## Objectives
- Identify cities with the highest transaction volume
- Analyze net revenue distribution across cities
- Examine transaction success vs failure rates
- Detect peak transaction hours
- Evaluate card-type usage and failure patterns
- Analyze zero-payment transactions

## Dataset Description
The dataset contains transaction-level records with the following fields:
- Transaction ID
- City
- Card Type
- Amount
- Status (Success / Fail)
- Time

### Notes
- Positive amounts represent successful payments
- Negative amounts represent refunds
- Zero amounts represent valid non-revenue transactions such as promotions or complimentary bookings

## Analysis Performed
- Transaction count analysis by city
- Net revenue analysis by city
- Hourly transaction activity analysis
- Success vs failure distribution
- Card-type usage and failure contribution
- Zero-payment transaction analysis by city and customer

## Power BI Dashboard Features
- KPI cards for total transactions, net revenue, failure rate, and zero-payment percentage
- Bar charts showing transaction volume and revenue by city
- Hourly transaction distribution
- Card-type failure analysis
- Zero-payment distribution by city
- Interactive slicers for city, card type, and status

## Tools & Technologies
- Python (Pandas, Matplotlib, Seaborn)
- Power BI
- Power Query
- DAX

## Conclusion
This project provides insights into transaction behavior, revenue concentration, and payment reliability. The findings help highlight operational risks and support data-driven decisions related to payment optimization, infrastructure planning, and promotional strategy.
