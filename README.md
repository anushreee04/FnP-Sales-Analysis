
# FnP Sales Analysis
________________________________________

# 1.	Introduction
The dataset is from FNP (Ferns and Petals) that specialises in sending gifts for various occasions like Diwali, Raksha Bandhan, Holi, Valentine's Day, Birthdays, and Anniversaries. 

The dataset contains details about the products, orders, customers, and relevant dates. The project aims to analyse this dataset to uncover key insights related to sales trends, customer behaviour, and product performance.

This report presents a detailed analysis of the sales data for Ferns N Petals (FnP), focusing on revenue trends, consumer behavior, product performance, and regional market penetration. The goal is to derive insights that can support strategic business decisions, marketing initiatives, and inventory management.
________________________________________

# 2.	Objectives
•	To evaluate the total revenue generated during the given period.
•	To analyze consumer spending behavior.
•	To examine revenue distribution across product categories and special occasions.
•	To identify high-performing products and regions.
•	To recommend strategic actions based on data-driven insights.
________________________________________

# 3.	Data Cleaning and Transforming 
•	Removing Duplicates- Customer Id, Order Id, Product id
•	Contact Number- Convert from Whole Number/ Decimal to Text
In Orders Tables
•	New Column- Extracting Order Month- Name of Month
•	New Column- Difference between Order Date and Delivery Date, Convert into just Days format
•	Extract Price Column from Products table to Orders tables- Joining Both Order and Product Table by Product_ID column
•	New Column- Revenue- Quantity*Price

________________________________________

# 4.	Data Overview
•	Total Revenue: ₹35,20,984.00
•	Average Consumer Spending: ₹3,520.98
•	Time Frame: Sales data spans from August 2023 to December 2024, covering major occasions and peak sales months.
________________________________________

# 5.	Revenue Analysis
   
5.1. Revenue by Occasion
The sales analysis highlights that festivals and special occasions significantly boost revenue. Key occasions contributing to high revenue include:
•	Raksha Bandhan
•	Valentine's Day
•	Birthday
•	Anniversary
•	Diwali and Holi (moderate contribution)
Insight: Occasion-based sales dominate the revenue chart. Raksha Bandhan and Valentine's Day especially generate substantial spikes, indicating strong consumer sentiment around gifting during cultural and romantic events.

5.2. Revenue by Category
Top-performing categories include:
•	Cakes
•	Flowers
•	Mugs
•	Plants
•	Soft Toys
•	Sweets
Insight: The emotional and consumable nature of these items resonates with gift-giving occasions. There is consistent demand across edible products (cakes, sweets) and keepsakes (mugs, soft toys).

5.3. Revenue by Month
Revenue analysis over months shows clear seasonality. High-sales months include:
•	August to November (festival season)
•	February (Valentine’s month)
Insight: Seasonality influences purchasing decisions. Timely inventory buildup and promotional campaigns can enhance performance in these months.
________________________________________

# 6.	Product Performance
Top 5 Products by Revenue:
1.	Deserunt Box
2.	Dolores Gift
3.	Harum Pack
4.	Magnam Set
5.	Quia Gift
Insight: Bundled and premium gift sets tend to outperform individual products. This aligns with customer preferences for ready-made gift solutions during peak occasions.
________________________________________

# 7.	Regional Insights
Top 10 Cities by Orders:
1.	Bhatpara
2.	Bidhannagar
3.	Bilaspur
4.	Dhanbad
5.	Dibrugarh
6.	Guntakal
7.	Haridwar
8.	Imphal
9.	Kavali
10.	North Dumdum
Insight: The majority of sales are generated from Tier-2 and Tier-3 cities, highlighting FnP’s successful market penetration beyond metropolitan hubs. These regions represent potential growth centers and deserve localized campaigns.
________________________________________

# 8.	Consumer Spending Behavior
•	Average order value is approximately ₹3,520.98, reflecting mid-range gifting.
•	The absence of extremely low or high-value outliers suggests a well-balanced product mix catering to mass-market tastes.
Insight: There is scope to introduce loyalty programs, bulk order discounts, or personalization options to enhance consumer satisfaction and repeat sales.
________________________________________

# 9.	Strategic Recommendations
•	Occasion-Based Promotions: Invest in targeted marketing before and during occasions. Giving discounts on products, gift cards, or complementary goodies. 
•	City-Specific Campaigns: Leverage regional insights to craft offers tailored to high-performing cities.
•	Product Strategy: Continue focusing on bundled gift packs and explore new combinations based on buying patterns.
•	Customer Retention: Introduce loyalty rewards, festive combos, and membership benefits to boost recurring revenue.
•	Inventory Planning: Align procurement with monthly revenue trends and seasonal demand peaks.
________________________________________
# 10.	Conclusion
FnP has shown robust sales performance across varied occasions, product categories, and cities. With strategic alignment in marketing, product development, and regional targeting, the brand can further enhance its market share and consumer loyalty. Data-driven decisions based on this analysis can significantly optimize operations and drive future growth.________________________________________
End of Report



# Dashboard Preview
https://github.com/anushreee04/FnP-Sales-Analysis/blob/main/Fnp%20Sales%20Analysis%20Preview.pdf
