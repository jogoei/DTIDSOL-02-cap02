# DTIDSOL-02-cap02

## Background and aim

Amazon Web Services (AWS) is a well-known SaaS company that sells software for sales and marketing to other companies (B2B). The product is a cloud computing platform powered by Amazon, which provides an end-to-end service for business users to build and run applications efficiently.
 
AWS is accessible over the internet and can be reached by anyone worldwide. To date, the company has sold 14 types of products to 42 countries and engaged 99 customers from various industries and segments, including Small and Medium-Size Business (SMB), Strategic, and Enterprise. This market dominance is predicted to be around 30% of the global cloud infrastructure, making AWS a mature cloud computing platform. 


The data set provided by the company describes order details from January 2020 to December 2023. It contains market distribution and segmentation, sales performance, quantity, profit, and discount for each customer transaction. As a data analyst, we have performed and analyzed: 

(1) Data preprocessing 

(2) AWS's sales performance : (a) identify sales trend, profit, and discount overtime; (b) identify the association between profit and discount, which results in a negative relationship; (c) focus the analyses on a product that has a negative profit

(3) AWS's market distribution: including sales performance from each region, subregion, country, and city

(4) AWS's customer segmentation: based on the purchasing recency, frequency, and monetary

The company wants to understand factors that affect the negative profit of a product; **thus we aim to analyze what factors contribute towards negative profitability in the AWS SaaS product. Subsequently, we will provide recommendations based on the findings.**


# Key summaries:

1. From 2020-2023, negative profit was identified for the Marketing Suite product ($-3473), with a median profit margin of $1.18

2. There is a very strong negative relationship between discount and profit as well as profit margin, suggesting the higher the discount, the smaller the profit. This challenge requires strategy re-assessment. 

3. Based on the geographical distribution, Marketing Suite struggles in the EMEA and APJ regions, as well as at the country and city levels. Meanwhile, it performs well in the AMER region and its subordinates. 

4. SMB has the highest proportion of business segments; however, the total profit has turned negative. Also, there is no median profit difference between SMB, Strategic, and Enterprise, suggesting that discount impacts are similar to those of the three segments.

5. A significant difference exists between median profit for low, medium, and high discounts. Moreover, we hypothesize that to get a positive discount or at least BEP, the optimum discount should be between 15-20%, and a discount greater than 20% could result in negative profit. 

6. The company has been suspected of giving a higher discount to top customers to maintain engagement.

# Conclusion 

The Marketing Suite product has a negative profitability, which is correlated with an excessive discount. This finding is identified primarily in the EMEA and APJ regions, particularly countries like France, Russia, Japan, Mexico, and Chile, as well as across business segments and industries. 

Thus, there is a need for immediate action and strategy to prevent further loss.

## Recommendation

**1. Implement Discount Optimization and Governance**
* It is suggested that a discount cap of 15–20% should be set for the regions and countries with negative profits, including the customer segments.
* If the country representatives want to give a discount of>20%, they have to implement a centralized discount approval from the headquarters. This procedure is created to ensure oversight and reduce high discrepancy in discounting. 
* The company can create a tiered discounting model based on the RFM score, ensuring the top consumers receive competitive and stable pricing without causing financial harm to the company. 

**2. Regional and city sales strategy reassessment**
* Perform in-depth market analysis for underperforming countries (e.g., France, Japan, Russia) to evaluate the local challenges (eg. Competitor, customer pricing expectations, and whether the product fits the business operation.
* Research alternative pricing and bundling package strategies instead of relying on discount
Empower country representatives with a localized marketing approach.

**3. Evaluating SMB segments**
* Considering segmenting SMB customers for differentiating pricing and engagement strategy, e.g., small business owner vs start-up 
* Upselling strategy after the customer used AWS products
* Implement a subscription plan-based model. 

**4. Review Customer category using RFM vs discounting** 
* Audit the top and high-value customers' discount program and evaluate whether a discount improves retention and frequency of purchase. 
* Alter broad/high discounting patterns to a loyalty-based discounting strategy and evaluate the sales.

**5. Revamping Marketing suite value of sales**
* Provide training to the sales team and use different angles for marketing. 
* By leveraging customer success stories from the AMER region, sellers can sell the product using value-based technology and show the superiority of this product and how it significantly increases the sales traffic of the business.
