# -Vendor-Sales-Summary-Project
"Python &amp; SQL project to analyze vendor sales data and generate summary reports."  "Power BI &amp; SQL project for vendor performance and sales analysis."  "Data analysis project summarizing vendor sales, profit, and stock metrics."

EXPLORTORY DATA ANALYSIS INSIGHT


<img width="1283" height="664" alt="Image" src="https://github.com/user-attachments/assets/e004d0e5-4a62-4045-9cbe-b026a33875c2" />

<img width="1002" height="622" alt="Image" src="https://github.com/user-attachments/assets/a94cf088-20d8-4242-aeec-06bbf723544d" />

Negative & Zero Values:
Gross Profit: Minimum of -52,002.78, indicating potential losses due to high costs or heavy discounts. This could be due to selling products at lower prices than their purchase costs. 
Profit Margin: Has a minimum of -o, which suggests instances where revenue is zero or even lower than the total cost, leading to extreme negative profit margins.
Total Sales Quantity & Sales Dollars: Some products show zero sales, indicating they were purchased but never sold. These may be slow-moving or obsolete stock, leading to inventory inefficiencies

Outliers Detected by High Standard Deviations.

Purchase & Actual Prices:The maximum values(5681.81 & 7,499.99) are sgnificantly higher than the mean(24.39 & 35.64,indicataing premimum product offerings

Freight Cost: Extreme variation from 0.09 to 257,032.07 suggests logistics
inefficiencies, bulk shipments, or erratic shipping costs across different
products.

Stock Turnover: Ranges from 0 to 274.5, suggesting some products sell
rapidly while others remain unsold for long periods. A value greater than 1
indicates that sales for a product exceed the purchased quantity due to
older stock fulfilling orders.

Data Filtering
to enhance reliability of the insight we removed inconsistent data point where:

*Gross Profit <= 0 (to exclude transctions leading to losses)
*Profit Margin <= 0(to ensure analysis fouces on profitable transactions)
*Total Sales Quantity = 0 (to eliminate inventory that was never sold

<img width="1238" height="682" alt="Image" src="https://github.com/user-attachments/assets/a08a87fd-f760-4928-b43f-3e471d638e74" />

Purchase Price vs. Total Sales Dollars & Gross Profit: Weak corelation (-0.012 and -0.016), indicating that price variations do not significantly impact sales revenue or profit.
Total Purchase Quantity vs. Total Sales Quantity: Strong correlation (0.999), confirming efficient inventory turnover. Profit Margin vs. Total Sales Price: Negative correlation (-0.179), suggesting increasing sales prices may lead to reduced margins, possibly due to competitive pricing pressures. 
Stock Turnover vs. Gross Profit & Profit Margin: Weak negative correlation (-0.038 & -0.055), indicating that faster stock turnover does not necessarily equate to higher profitability. heat map dekh ke bolo sahi he


Research Questions & Key Findings

1.Brands for Promotional or Pricing Adjustments

<img width="503" height="414" alt="Image" src="https://github.com/user-attachments/assets/1d9d570e-b115-45d3-b517-49c12c7a6e08" />

1043 brands exhibit lower sales but higher profit margins,which could benefit from targeted marketing,promotions, or price optimizations to increase volume without compromising profitability

<img width="983" height="550" alt="Image" src="https://github.com/user-attachments/assets/ec8b07f7-537d-49c2-be8e-680192a39130" />

The top 10 vendors contribute 65.69% of total purchases, while the
remaining vendors contribute only 34.31%. This over-reliance on a few
vendors may introduce risks such as supply chain disruptions, indicating a
need for diversification.

2. Top Vendors by Sales & Purchase Contribution

 The top 10 vendors contribute 65.69% of total purchases, while the
remaining vendors contribute only 34.3%. This over-reliance on a few
vendors may introduce risks such as supply chain disruptions, indicating a
need for diversification.

 <img width="1053" height="614" alt="Image" src="https://github.com/user-attachments/assets/3a35414c-fc13-4388-9862-f90aa2c2820a" />

 3. Impact of Bulk Purchasing on Cost Savings
Vendors buying in large quantities receive a 72% lower unit cost ($10.78
per unit vs. higher unit costs in smaller orders).

Bulk pricing strategies encourage larger orders, increasing total sales while
maintaining profitability.
OrderSize UnitPurchasePrice

<img width="235" height="181" alt="Image" src="https://github.com/user-attachments/assets/579ebae8-b7bb-4419-b7bc-a333a644d045" />

4. Identifying Vendors with Low Inventory Turnover
Total Unsold Inventory Capital: $2.71M
Slow-moving inventory increases storage costs, reduces cash flow
efficiency, and affects overall profitability.
Identifying vendors with low inventory turnover enables better stock
management, minimizing financial strain.

<img width="458" height="326" alt="Image" src="https://github.com/user-attachments/assets/8971e9a5-5a96-4baa-aed9-d87d680bf13d" />

5. Profit Margin Comparison: High vs. Low-Performing Vendors
Top Vendors' Profit Margin (95% CI): (30.74%, 31.61%), Mean: 31.18%
Low Vendors' Profit Margin {95% CI): (40.48%, 42.62%), Mean: 41.24%
Low-performing vendors maintain higher margins but struggle with sales
volumes, indicating potential pricing inefficiencies or market reach issues.
Actionable Insights:
. Top-performing vendors: Optimize profitability by adjusting
pricing, reducing operational costs, or offering bundled
promotions.

<img width="1063" height="563" alt="Image" src="https://github.com/user-attachments/assets/6a9f8fff-0da1-4016-97a8-15056c58ab5e" />

6. Statistical Validation of Profit Margin Differences
Hypothesis Testing:
Ho (Null Hypothesis): No significant difference in profit margins between top
and low-performing vendors.

H1 (Alternative Hypothesis): A significant difference exists in profit margins between the two vendor groups

Result: The null hypothesis is rejected, confirming that the two groups
operate under distinctly different profitability models.

Implication: High-margin vendors may benefit from better pricing
strategies, while top-selling vendors could focus on cost efficiency.



Final Recommendations 

.Re-evaluate pricing for low-sales,high-margin brands to boost sales volume withoiut sacrificing profitability

. Diversify vendor partnerships to reduce dependency on a few
suppliers and mitigate supply chain risks.

· Leverage bulk purchasing advantages to maintain competitive pricing
while optimizing inventory management.

. Optimize slow-moving inventory by adjusting purchase quantities,
launching clearance sales, or revising storage strategies.

. Enhance marketing and distribution strategies for low-performing
vendors to drive higher sales volumes without compromising profit
margins.

. By implementing these recommendations, the company can achieve
sustainable profitability, mitigate risks, and enhance overall
operational efficiency.



<img width="1322" height="735" alt="Image" src="https://github.com/user-attachments/assets/3ee7e41e-7c66-42d2-ace6-7dfe49bebbff" />

The Vendor Performance Dashboard provides a complete overview of sales, purchases, profitability, and inventory efficiency across major vendors and brands in the alcoholic beverages category. Total Sales amount to $441.41M, Total Purchases to $307.34M, resulting in a Gross Profit of $134.07M and a Profit Margin of 38.72%. Unsold Capital stands at $2.71M, indicating the value of slow-moving inventory.
DIAGEO North America contributes the highest share of purchases at 24.81%, followed by Martignetti Companies, Pernod Ricard USA, and Jim Beam Brands. DIAGEO also leads in total sales with $68M, with other strong performers including Martignetti, Pernod Ricard, Jim Beam, and Bacardi.
Top-selling brands include Jack Daniel’s ($8.0M), Tito’s Handmade Vodka ($7.4M), Grey Goose ($7.2M), Captain Morgan ($6.4M), and Absolut 80 Proof ($6.2M), highlighting strong consumer demand for premium spirits.
Stock turnover analysis shows Dunn Wine Brokers, Circa Wines, and Park Street Imports as the most efficient vendors in inventory movement. A scatter plot identifies low-performing brands based on low sales and low profit margins, helping highlight areas needing strategic improvement.
Overall, the dashboard supports data-driven decisions in vendor management, brand prioritization, inventory optimization, and profitability enhancement


