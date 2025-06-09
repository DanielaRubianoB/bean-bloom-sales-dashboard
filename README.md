# ☕ Bean & Bloom Sales Dashboard

Tools Used: Excel <br>
Project Type: Exploratory Data Analysis (EDA), Dashboard Development

### Project Background
Bean & Bloom, founded in 2016, is a specialty coffee retailer that offers ethically sourced beans and customizable roast subscriptions. Operating across North America and parts of Europe, the company sells popular coffee varieties through its online store and local distributors. <br>
The company has collected a large volume of data on sales performance, product preferences, regional demand, and loyalty program usage. I’m partnering with the Sales & Marketing Analytics Team to analyze the data and uncover actionable insights and improve Bean & Bloom’s commercial strategy. <br>
Insights and recommendations are provided on the following key areas:
- Sales Trends Analysis: Evaluation of historical sales data over time by coffee type, identifying seasonal trends and performance spikes.
- Top Customer Analysis: Identification of the highest-value customers to tailor retention strategies and personalized marketing.
- Product Category Performance: Comparative analysis of roast types and package sizes to understand sales drivers and product popularity.
- Loyalty Program Impact: Assessment of how the loyalty card program influences purchasing behavior and customer lifetime value.
- Regional Sales Distribution: Geographic breakdown of total revenue, helping prioritize marketing and distribution efforts by country.

## Relevant Resources
The raw dataset used for analysis can be accessed [here](https://github.com/DanielaRubianoB/bean-bloom-sales-dashboard/blob/main/Raw_coffeeOrdersData.xlsx). <br>
The final cleaned dataset and Excel dashboard can be downloaded [here](https://github.com/DanielaRubianoB/bean-bloom-sales-dashboard/blob/main/BeanBloom_Dashboard.xlsx). <br>
A presentation slide deck prepared for stakeholders can be viewed here. <br>

## Data structure and initial checks
The Bean & Bloom dataset, as seen below, consists of three structured tables: Customers, Orders, and Products, with a total of over 50,000 records. <br>
Prior to beginning the analysis, a variety of checks were conducted for quality control and to gain familiarity with the data structure. These checks included schema validation, relationship consistency and data type integrity. <br>
No cleaning was required. Instead, a set of stakeholder-aligned questions was developed to clarify assumptions and define the scope. After aligning on these needs, calculated fields and aggregations were introduced to support further analysis. These can be reviewed here.

## Executive summary
From 2019 to 2022, Bean & Bloom showed steady growth, with monthly revenue peaking at $856 in February 2021 and dipping to a low of $38 in October 2020, reflecting strong seasonality in performance. Arabica led product-level revenue, outperforming other roasts by 25–40% on average. Loyalty members generated 30% more orders and had an average revenue per user (ARPU) $58 higher than non-members. Regionally, the U.S. accounted for $35,639 (85%+) in total revenue. Key opportunities for growth and optimization will be addressed in the following sections. <br> 
Below is the overview page of the dashboard, and the full interactive version can be downloaded here.

## Insights Deep-Dive 
### Sales Trends
- In February 2021, sales reached their peak at $856, driven by seasonal promotions and post-holiday buying behavior. Another spike occurred in November 2021 at $847, likely tied to holiday demand.
- The lowest sales occurred in October 2020, with revenue dropping to just $38, indicating a gap in marketing or engagement during that period.
- Over the three-year span, total annual revenue increased by approximately 20%, reflecting long-term growth despite month-to-month variability.
- Arabica consistently led in sales, often outperforming other roasts by 25–40%, affirming its position as the company’s most popular product.
### Top Customers
- The top customer, Allis Wilmore, spent $317, and the top 5 customers together contributed $1,473, making up more than 10% of total revenue.
- Three of the top 5 customers made purchases across at least four different months, showing strong engagement and repeat behavior.
- While ranked fifth, Don Flintiff placed frequent mid-value orders, showing loyalty through consistency rather than large single transactions.
### Product Category Performance
- Arabica peaked at $842 and maintained a leading position across most months, showing strong customer preference and product-market fit.
- Excelsa ranked second with reliable performance and periodic spikes, reinforcing its role as a strong secondary offering.
- Robusta frequently generated under $100/month, while Liberica spiked to $859 in November 2021, suggesting that lower-performing blends can still be boosted through targeted promotions.
### Loyalty Program Impact
- Loyalty card holders placed 30% more orders than non-members, showing higher engagement and purchase frequency.
- Their average spend was $58 greater, highlighting the program’s effectiveness in increasing customer value.
- With only 38% of customers enrolled, there is significant potential to expand the program and unlock more revenue through wider adoption.
### Regional Sales Distribution
- The United States led with $35,639 in sales, accounting for over 85% of total revenue and reflecting a mature, well-established market presence.
- In comparison, Ireland and the UK generated $6,697 and $2,799, respectively—highlighting underutilized growth opportunities.
- The 5x revenue gap between the US and other markets underscores the need to expand product visibility and marketing in international regions.

## Recommendations & Opportunities
- Capitalize on Seasonal Highs: Run targeted promotions during Q1 (February) and Q4 (November), where historical data shows peak revenue. Use bundles, discounts, and loyalty boosts to drive engagement during these periods.
- Reward High-Value Customers: Introduce VIP perks for top spenders and frequent buyers, such as early access to new products or exclusive discounts. Consider a tiered loyalty system to nurture both high spend and frequent purchase behaviors.
- Prioritize Best-Selling Products: Focus marketing and inventory planning around Arabica and Excelsa, the top-performing coffee types. Feature them in featured product sections, paid ads, and curated bundles.
- Reposition Underperforming Roasts: Reevaluate the role of Robusta and Liberica in the product line. Explore limited-edition releases, flavor rebranding, or bundled promos to reignite interest or phase them out.
- Increase Loyalty Program Adoption: Boost visibility of the loyalty program at checkout with clear benefits like “Earn free shipping” or “Unlock exclusive deals.” Use post-purchase emails to encourage sign-up among non-members.
- Grow International Markets: Expand brand presence in Ireland and the UK by increasing localized campaigns, offering free regional shipping thresholds, or running limited-time offers tailored to those markets.
- Enhance Performance Tracking: Extend the dashboard to include cost, profit margins, and marketing ROI. Create a recurring monthly insights tracker to monitor KPIs like revenue, repeat rate, and loyalty conversion.

## Key Questions for Stakeholders Prior to Project Advancement
These are some questions I asked stakeholders/project leads early on to better understand business goals, clarify assumptions, and ensure data interpretation aligned with operational context:
- How is a “top customer” internally defined? By total spend, purchase frequency, or lifetime value?
- Are there known promotional periods or marketing campaigns that could explain sales spikes?
- Should performance across coffee types be evaluated equally, or are certain roasts considered flagship products?
- How important is the loyalty program to the company’s strategy? should it be analyzed as a primary growth lever?
- Regional sales should be analyzed at the country level or city-level segmentation?
- Is this dashboard meant for one-time strategic use, or will it support ongoing performance tracking and reporting?

## Assumptions and Caveats
The following assumptions and limitations were made during the course of this project due to gaps in context, incomplete metadata, or missing documentation:
- It is assumed that all transaction records in the dataset reflect completed and paid orders, with no cancellations or returns unless explicitly stated.
- Customer names were used as unique identifiers; duplicates were assumed to reflect repeat purchases rather than different individuals with similar names.
- Loyalty card status was treated as binary (Yes/No), with no further distinction between levels or benefits, as that data was not provided.
- Regional sales were analyzed at the country level (U.S., Ireland, U.K.) without detailed city-level segmentation, as specified by the Stakeholder.
- Sales dips and spikes were interpreted based on observed time patterns and typical seasonal behavior.
- The dataset does not include cost data, so profitability and margin analysis were not part of this scope.




