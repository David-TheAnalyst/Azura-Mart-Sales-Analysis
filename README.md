# Azura-Mart-Sales-Analysis

<div align="center">
  <img src="https://github.com/David-TheAnalyst/Azura-Mart-Sales-Analysis/blob/main/Azura%20Illusion.png" alt="Flowpal Sales Dashboard Additional View" width="1000" height="600">
</div>
 
## **Introduction**

The leadership of Azura Mart deserves commendation for its impressive market engagement, which has delivered a top-line performance and 25,355 units sold over the last two years. This metric, traditionally celebrated as a sign of success, has unfortunately masked a severe underlying financial crisis.
 
This report reveals that Azura Mart has been operating under an "Illusion of Victory." Despite the high sales volume, a detailed log of commercial activities across Food, Furniture, Electronics, and Clothing exposes a catastrophic negative 83% profit margin. The company is, in effect, paying customers to take its products, thereby rendering its growth unsustainable.

The primary objective of this data-driven audit is to move past this deceptive headline, pinpoint the exact structural and provide a definitive, custom-tailored Strategic Recovery Blueprint. The ultimate value of this project is to arm the Sales Management, Marketing, Finance, and Operations teams with the knowledge to immediately cap the discount freefall and strategically deploy resources to build a profitable, sustainable empire.

## **Key Datasets and Methodologies:**

The analysis utilizes a single, comprehensive dataset of the company's detailed daily commercial activity log from 2023 to 2024. The methodologies employed in Microsoft Excel include me:

-	generating the critical Profit and Discount Percentage fields to quantify the financial crisis.

- visualizing the relationship between Discount Percentage and Profit per transaction, 

-	Utilizing pivot tables to measure performance (Sales, Quantity, Profit) across key independent variables like Region, Sales Rep, and Product Category.

## **Story of Data:**

The dataset was acquired from a publicly available repository on Kaggle, detailing the logs of the company's daily commercial activities for the period 2023−2024. 
 
It is structured with rows representing each transaction and columns providing both the context (who, where, when, how) and the financial outcomes (cost, sales, quantity).

- **Independent Variables (Context):** Product_ID, Region, Sales_Rep, Sales_Channel, and Customer_Type are the drivers used to segment performance.

-	**Dependent Variables (Outcomes):** Sales, Quantity, and the derived Profit are the key metrics for measuring financial health. 

The analysis relies heavily on the interaction between the derived Discount Percentage and the resulting Profit to diagnose the core financial problem.

However, While the Customer Type column is present, the absence of a long-term customer ID prevents the calculation of Customer Lifetime Value, which is essential for determining if high initial discounts for new customers are recouped over time. The data does not include competitor pricing or promotional activities, which could be skewing the necessity for deep discounts.


## **Pre-Analysis:**

This part of the project was focused on capturing the core narrative of the dataset. It gave me a high-level view of the data quality, the industry context, and what success looks like for stakeholders. I then listed every potential analysis/ question I wanted to explore, pairing each with the expected pre-insight and potential insight. 
 
The result was a clear roadmap that guided the Azura Mart Sales Analysis.    

-	**Category One (Independent):** It details the areas where strategy must be adjusted. It includes the Region, Sales_Rep, Sales_Channel, Product_Category.

-	**Category Two (Dependent):** It details the metrics that are to be optimized such as Sales, Quantity, Unit_Cost, and the derived Profit. 

**Industry Context:** A Retail Industry whose mandate is to maximize profitable revenue growth. 

**Stakeholders:** The **Finance Team** and **Operations/Supply Chai**n have the most urgent need for this report, as the negative margin directly impacts cash flow and inventory efficiency.

## **In-Analysis:**

The in-analysis phase focused on Identifying the key trend and pinpointing the financial damage and operational weaknesses buried with the company’s data.

1.	Top-Line Success: The company achieved $5.01 million in sales and 25,355 units sold, validating market demand and sales team activity.

2.	Financial Disaster: The initial calculation revealed a devastating −83% profit margin implying that for every $1 of sales, the company loses $0.83, which is further confirming the 'Illusion of Victory' problem statement.

3.	Channel Dominance: The Retail Sales channel is the primary revenue driver ($2.56 million) and is marginally outperforming the Online channel ($2.45 million).

4.	Performance Skew: Sales Rep David is the clear top performer, and the North region is the undisputed revenue leader, suggesting successful localized strategies that must be studied and replicated.
 
5.	The scatter plot analysis using Discount Percentage vs. Profit validated that discount over 12% consistently push transactions into a loss, and deeper discounts result in massive negative profit. This establishes the immediate cap required irrespecgt5ive of the condition.
 
6.	Product Line Profitability Audit: The strong volume of Clothing and Furniture sales, combined with the extreme negative profit, immediately suggested a high negative correlation between sales of these categories and profitability, pointing to these categories as the likely source of the deepest discounts. This necessitates an immediate audit and discontinuation for the worst offenders.
 
7.	Channel and Day Performance: The overall sales leader is Thursday, but segmentation showed the Retail channel peaks on Friday while Online peaks on Thursday. This detail is crucial for optimizing staffing and promotion timing by channel.
 

## **Post-Analysis and Insights**

**Key Findings/Observation:**

1.	The critical discount cap is 12%. Any promotion exceeding this limit is guaranteed to erode profit.

2.	The Retail Sales Channel is the primary revenue engine and should be prioritized for resource allocation and seamless customer experience, while the Online channel requires urgent investigation into its lower performance.

3.	Clothing and Furniture are confirmed as the most deeply unprofitable categories. An immediate granular audit is required to discontinue specific SKUs being sold at the greatest loss.

4.	The performance of Sales Rep David and the North Region must be standardized and scaled. The gap between them and the South/East regions indicates localized training and strategy failures.

5.	The January post-holiday slump and the distinct mid−year lull in September are recurring, predictable events that can be mitigated with proactive marketing campaigns.

The analysis conclusively transformed the initial perception of the $5.01 million sales figure from a source of pride to a clear warning sign. The success of the Retail channel over Online was confirmed, and the high-volume categories (Clothing/Furniture) were precisely identified as the financial culprits.


## **Data Visualizations & Charts:**
<div align="center">
  <img src="https://github.com/David-TheAnalyst/Azura-Mart-Sales-Analysis/blob/main/Azura%20Mart%20Dashboard.png" alt="Flowpal Sales Dashboard Additional View" width="1300" height="auto">
</div>
 
A high-level, drillable dashboard for the Chief Executive and Finance Department that can be further filtered  by Sales Channel.

Key Metrics Displayed (KPIs): 

-	Total Sales $5.091,265.23

-	Quantity Order:25355

-	Profit Margin: −83% 

-	Average Order Value: $442,828.13

**Charts and Graphs:**

**Scatter Plot:**

-	Discount Percentage vs. Profit: This mandatory visualization provides the irrefutable evidence of the 12% "discount cliff" and the negative 83% margin.

**Pie Chart:**

•	Sales by Transaction Method

**Line Chart:** 

-	Day of Week by Quantity Ordered: Visually confirming the sharp Dec-Jan drop and the September lull for seasonal planning

-	Sales Trend by Month: Visually confirming the sharp Dec-Jan drop and the September lull for seasonal planning.

**Column Chart:** 

-	Top 4 Sales Rep by Sales

-	Sales by Region: Highlighting the substantial gap between the North region (leader) and the South/East regions for resource allocation.

-	Sales by Product Category: Displaying the high sales for Clothing and Furniture versus other categories to guide immediate product audits.

## **Specific Recommendations:**

1.	Immediately initiate a hard cap of 12% on all discounts store-wide and launch a full-scale audit of all pricing and discount policies to ensure they do not erode profitability.

2.	Prioritize the Retail Sales Channel by allocating more resources, ensuring a seamless customer experience, and investigating the specific factors (e.g., website UX, shipping costs) causing the Online channel's underperformance.

3.	Conduct an in-depth analysis of David's and the North region's sales strategies to create a targeted training and best-practices program for lower-performing reps in the South/East regions.

4.	Strategically schedule promotions and marketing campaigns to counteract the post-holiday slump in January and the mid-year lulls in September.

5.	Perform a granular profitability analysis of every Clothing and Furniture SKU to determine the most unprofitable product lines that are immediately due for discontinuation.

6.	Focus heavy promotions on the high-demand days of Thursday and Friday, while testing new strategies on lower-performing Tuesdays and Wednesdays to stabilize the weekly sales pipeline.

In all. the most critical unexpected outcome is the lack of correlation between sales volume and financial health. The high sales numbers ($5.01 million) were masking an internal financial collapse, underscoring the danger of optimizing for top-line revenue without accounting for unit cost and discount impact.

## **Conclusion:**

This project has transformed raw transaction records into a strategic imperative. I successfully moved past the deceptive headline of $5.01 million in sales to expose an unsustainable −83% profit margin driven by reckless discounting. Furthermore, it provides a definitive, data-driven solution for achieving the stakeholder expectation of maximizing profitable revenue by establishing a non-negotiable 12% discount cap and initiating surgical audits of the most unprofitable product lines.

However, The primary limitation is the inability to calculate Customer Acquisition Cost and Customer Lifetime Value due to the absence of a unique customer identifier across transactions. This prevents a full assessment of whether high initial discounts used to acquire new customers are offset by long-term, full-price purchases.

## **Future Research:**

1.	A necessary deep-dive to determine the exact profit/loss of every Clothing and Furniture product to guide item-level discontinuation decisions.
2.	Future data collection must be revised to include a persistent Customer ID to enable the modeling of CLV and fully justify any acquisition-based discounting.

## **References:**

-	Azura Mart Daily Commercial Activity Log from 2023−2024  [(Kaggle)](https://github.com/David-TheAnalyst/Azura-Mart-Sales-Analysis/blob/main/Azura%20Mart%20Raw%20Data.csv)
-	Microsoft Excel 


<h3 align="left">Connect with me on Socials:</h3>
<p align="left">
<a href="https://linkedin.com/in/david ojo" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="david ojo" height="30" width="40" /></a>
<a href="https://twitter.com/david_ojo_1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="david_ojo_1" height="30" width="40" /></a>
<a href="https://medium.com/@davidojo2214" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="@davidojo" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/davidojo-j3v" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="davidojo-j3v" height="30" width="40" /></a>
</p>

Thanks for stopping by!
