# RFM Customer Segmentation and Customer Retention Analysis

## Project Overview

This project applies Recency, Frequency, and Monetary (RFM) analysis to segment e-commerce customers based on their historical purchasing behaviour. The goal is to identify high-value customers, understand customer engagement, and highlight opportunities for customer retention and reactivation.

## Business Objectives

- Identify valuable and loyal customers.
- Segment customers using RFM scoring.
- Identify customers who may be at risk of becoming inactive.
- Recommend targeted customer-retention and reactivation strategies.
- Present key findings through a Power BI dashboard.

## Tools and Technologies

- **Python:** Data cleaning, transformation, and analysis
- **Pandas and NumPy:** Data manipulation and RFM calculations
- **Jupyter Notebook:** Analysis workflow
- **Power BI:** Interactive business dashboard
- **GitHub:** Project documentation and version control

## Dataset

The analysis uses the UCI Online Retail II dataset, which contains e-commerce transaction records covering two annual periods.

The data includes invoice identifiers, product information, quantities, prices, transaction dates, customer identifiers, and countries.

## Methodology

1. Combined the two annual datasets.
2. Cleaned transaction records and handled missing customer identifiers.
3. Validated quantities, prices, and non-product transaction entries.
4. Calculated sales values and prepared customer-level transaction data.
5. Calculated Recency, Frequency, and Monetary values for each customer.
6. Assigned five-point RFM scores using quantile-based scoring.
7. Classified customers into eight segments.
8. Analyzed segment revenue contributions and customer reactivation opportunities.
9. Developed a Power BI dashboard to communicate the findings.

## Key Results

| Metric | Result |
|---|---:|
| Customers analyzed | 5,881 |
| Orders | 36,975 |
| Unique products | 4,631 |
| Total revenue | £17,374,804.27 |
| Average order value | £469.91 |

## Customer Segmentation

The analysis identified eight customer segments:

- Champions
- Loyal Customers
- Can't Lose Them
- At Risk
- Potential Loyalists
- Needs Attention
- Hibernating
- New Customers

Champions contributed approximately 68.13% of historical revenue, making them an important group for retention and loyalty initiatives.

## Customer Reactivation Opportunity

The Can't Lose Them and At Risk segments together contained 613 customers associated with approximately £1.50 million in historical revenue.

These customers represent a potential reactivation opportunity. The analysis recommends prioritizing outreach based on historical customer value and testing targeted campaigns to measure actual results.

Historical revenue does not guarantee that this amount can be recovered.

## Business Recommendations

- Reward high-value customers through loyalty benefits and personalized offers.
- Encourage repeat purchases from Loyal Customers and Potential Loyalists.
- Prioritize targeted win-back campaigns for At Risk and Can't Lose Them customers.
- Use cost-effective engagement strategies for Hibernating customers.
- Track repeat purchases and campaign performance to evaluate retention efforts.

## Project Files

- **Notebook:** Python analysis and RFM calculations
- **Dashboard:** Power BI customer segmentation and sales analysis
- **Documentation:** Detailed project methodology, findings, and recommendations

## Limitations

This analysis is based on historical transactions. RFM scores describe past purchasing behaviour and do not guarantee future customer activity or campaign success. Transactions without usable customer identifiers cannot be reliably assigned to customer segments.

## Conclusion

This project demonstrates how customer transaction data can be transformed into actionable business insights using Python and Power BI. RFM segmentation helps distinguish valuable customers, identify potential retention risks, and support more focused marketing decisions.
