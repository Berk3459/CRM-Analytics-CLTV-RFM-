# CRM-Analytics-CLTV-RFM-
## Project Overview

This project focuses on Customer Relationship Management (CRM) analytics by analyzing customer purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and Customer Lifetime Value (CLTV) modeling.
The main objectives of the project are:
* Segment customers based on their purchasing behavior
* Identify high-value and loyal customers
* Estimate future customer value using CLTV
* Support data-driven marketing and retention strategies

## Dataset
* The dataset contains historical customer transaction data, including:
* Customer ID
* Order dates
* Number of purchases
* Total spending
* The data is first cleaned and then structured to enable customer-level analysis.

## Technologies & Libraries Used

*Python
*pandas – Data cleaning and manipulation
*numpy – Numerical operations
*matplotlib – Visualization
*seaborn – Advanced visualizations
*scikit-learn – Scaling and modeling



## Methodology
**Data Preparation**
Removed missing and invalid values
Converted date columns to datetime format
Aggregated transactions at the customer level

**RFM Analysis**

RFM metrics were calculated as:
Recency – Days since the last purchase
Frequency – Total number of purchases
Monetary – Total amount spent

**CLTV Modeling**

CLTV results help identify customers who are expected to generate the highest long-term revenue.



## Results & Insights

* High-value customers were clearly identified through RFM segmentation
* CLTV modeling highlighted customers worth prioritizing for retention
* Marketing strategies can be tailored based on customer segments
