# nykaa
This project conducts a comprehensive *data analysis* on a set of Nykaa product information, focusing on *customer engagement (reviews)* and *e-commerce strategy (pricing and discounts)*.  
The goal is to provide *data-backed insights* into product performance and promotional effectiveness.

---

## 🎯 Project Objectives

The analysis was structured to answer key business questions:

1. *Sentiment Benchmarking:*  
   Determine the average customer engagement (reviews) and identify top-performing products.

2. *Discount Strategy Assessment:*  
   Quantify the average discount rate and pinpoint products with the highest and lowest promotional offers.

3. *Pricing Tier Impact:*  
   Compare review volume between high-priced and low-priced product segments to identify potential correlations.

---

## 🔍 Key Findings Summary

| Metric | Result | Business Insight |
| :--- | :--- | :--- |
| *Highest Reviewed Product* | Nykaa Naturals Skin Secrets Exotic Indulgence (Multiple variations) | This product line is a market leader in terms of customer feedback and recognition. |
| *Average Discount* | *~21.82%* | Represents the baseline promotional cost required to move inventory on the platform. |
| *Highest Discount* | *88.0%* (Le Marbelle Black Obsidian Roller) | Suggests a clearance effort or aggressive promotional push for specific stock. |
| *Average Original Price* | *~₹791.20* | Reflects the general market price point for the analyzed catalog. |

---

## 🛠️ Technical Implementation

The entire analysis pipeline was built using the following tools:

- *Python* → Core language for all data processing  
- *Pandas* → Data manipulation, aggregation, and analysis (mean, sort_values, idxmax, etc.)

### Core Analysis Steps

1. *Review Metrics:*  
   Calculated maximum reviews, average reviews, and identified the *Top 5 most-reviewed products*.

2. *Pricing Analysis:*  
   Determined the mean *Original Price* and *Offer Price* for benchmarking.

3. *Discount Analysis:*  
   Identified the products with the *highest* and *lowest* discounts, and calculated the overall *average discount*.

4. *Comparative Analysis:*  
   Established a *median price point* to compare review performance between *high-priced* and *low-priced* products.

---

## 🚀 Future Enhancements

- *Correlation Testing:*  
  Compute the correlation coefficient between *Discount %* and *Review Count*.

- *Brand Performance:*  
  Group data by brand to assess which brands offer the most competitive pricing or generate the most reviews.

- *Text Analysis:*  
  Use NLP techniques on customer reviews for deeper *sentiment insights*.
