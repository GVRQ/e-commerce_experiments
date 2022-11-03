# E-Commerce Experiments
This Data Science project's goal is to conduct experiments with various metrics on e-commerce data.

I am going to use a dataset from *Shopify's 2022 Data Science Internship*.

Plan:
- EDA is performed on the original dataset: data description; detecting & treating outliers; Understanding relationships through plots;
- Heuristic metrics - CLV
- Gamma-Gamma & BG/NBD - CLV
- Customer Lifetime Value prediction and segmentation
- RFM Segmentation (Recency, Frequency, and Monetary)
- CLV Segments + RFM
- Recommendations (marketing tips for every customer segment)

**Customer Lifetime Value**

It is essential to know what each customer is worth to a business and understand the success rate of current strategies. CLV is a metric that grants knowledge and shows the amount of value a customer is expected to bring to a business over time.

CLV is a great asset and key to making financial forecasts and addressing any budget concerns. It gives an insight into many areas of a business and provides the knowledge to be projected onto future business decisions. 

**Heuristic metrics vs Gamma-Gamma & BG/NBD**

For E-Commerce CLV calculation we are going to use two methods:
- **Heuristic metrics** | Practical but suboptimal approach
- **Gamma-Gamma & BG/NBD** | Robust methodology with individual metrics and predictions

**RFM Segmentation**

RFM segmentation is a great method to identify groups of customers for special treatment. RFM analysis allows marketers to target specific clusters of customers with communications that are much more relevant for their particular behavior – and thus generate much higher rates of response, plus increased loyalty and customer lifetime value.

**Accomplished**:
- Calculated metrics: `Tenure`, `Average Order Value`, `Average Order Frequency`, `Average Customer Value`, `Average Customer Lifetime`, `Customer Lifetime Value`;
- List of customers that will purchase in the next period.
- Top 10 customers expected to make the most purchases in the next period (Week, Month, 6 Months).
- Top 10 most valuable customers by average transaction value
- CLV Customer Segmentation
- Average CLV (3 months) per Segment (A,B,C)
- RFM Segmentation (Scores and Labeling)
- CLV + RFM analysis
- Crosstab Results & Recommendations (marketing tips on targeting specific clusters of customers)
- Revenue at risk: Number of Customers and amount of CLV (3 months) in the Risk groups.
