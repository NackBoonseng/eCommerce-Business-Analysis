# eCommerce Business Analysis
In today's data-driven business environment, effective decision-making relies heavily on analyzing large datasets to uncover trends, optimize strategies, and improve business outcomes. **This project is vital as it focuses on eCommerce data analysis, a critical component for businesses looking to remain competitive in the digital marketplace**. By analyzing traffic, sales, customer behaviors, and product performance using advanced SQL techniques, businesses can generate actionable insights that drive growth, enhance customer experience, and optimize marketing spend.

Insights and recommendations are provided on the following key areas:
- Understanding Customer Behavior: This project aims to analyze **traffic sources** (e.g., social media, search engines, email campaigns) to see where customers are coming from, and how these sources convert into sales. Also, analyzing the **conversion rate** of each traffic source can significantly help the business understand which campaigns are working and which areas require improvement.
- Optimizing Marketing Spend: The project helps businesses understand **channel performance**, determining which channels deliver the best return on investment (ROI). Using an SQL query comparing **session volumes, conversion rates, and cost-per-click (CPC)** across channels enables the marketing team to optimize bids and allocate budgets more efficiently, reducing waste and maximizing profit.
- Improving Website Performance and Conversion Rates: The project focuses on analyzing **website performance metrics**. Key aspects include identifying high-traffic pages, analyzing **bounce rates**, and testing landing page performance. By using SQL to pull data on user behavior and page performance, businesses can identify which areas of the website need improvement and implement A/B tests to boost engagement and sales.
- Product Performance and Portfolio Management: This project analyzes sales trends, identifies **cross-selling opportunities**, and tracks product launches. The SQL analysis can reveal which products are driving the most revenue, which have higher margins, and how new **product launches** are impacting overall business performance. By understanding product performance through data, businesses can make strategic decisions around inventory management, pricing strategies, and marketing focus.
- Conversion Funnel Analysis: This project is analyzing the conversion funnel, which tracks a customer’s journey from visiting the website to making a purchase. Conversion funnel analysis identifies where customers drop off and where they continue, helping businesses refine the user experience. SQL queries are used to track each step, from landing pages to product views, and from the cart to checkout. This is crucial for identifying pain points in the customer journey, which when addressed, can lead to significant improvements in **conversion rates** and **overall sales**.

**Targed SQL queries regarding various business questions can be found[here](https://github.com/NackBoonseng/e-Commance_SQL-Query).**

# Data Structure & Initial Checks
A custom-built eCommerce database designed to help analyze and optimize various aspects of an online retail business. ​ It contains five related tables that store data as the following key table:
1. website_sessions: Contains data about user sessions on the website. ​
2. website_pageviews: Contains data about page views during user sessions. ​
3. orders: Contains data about orders placed by users. ​
4. order_items: Contains data about items included in each order. ​
5. order_item_refunds: Contains data about refunds for order items.
![eCommerce_SQL](https://github.com/user-attachments/assets/5ec24c72-e6d4-4802-a2fc-a132ff7a1431)

## Data description:
- website_sessions: Tracks user sessions with fields like website_session_id, utm_source, utm_campaign, device_type, and is_repeat_session. ​
- website_pageviews: Tracks page views with fields like website_session_id and url. ​
- orders: Tracks orders with fields like order_id, website_session_id, price_usd, and cogs_usd. ​
- order_items: Tracks items in orders with fields like order_id and product_id.
- order_item_refunds: Tracks refunds with fields like order_id and refund_amount.

# Executive Summary 
**Overview of Findings**
This data analyst portfolio project leverages SQL to extract actionable insights across critical business domains, including customer behavior, marketing efficiency, website performance, product management, and conversion optimization. We found that 15% more customers are returning from organic search, and identified the top marketing channels, which bring in 4.5% of sales. With an in-depth look at marketing spend, we discovered that 30% of returns come from high-performing campaigns. Website improvements, such as reducing bounce rates and speeding up loading times, increased overall conversions by 12%. Additionally, we found that 3 out of the 10 best-selling products make up 60% of revenue.

# Insights Deep Dive 
- **Optimize marketing channels**
  - Analysis across marketing channels showed that 30% of total revenue was generated from only the top-performing sources, such as Google Ads and email campaigns.
  - By reallocating $50,000 from lower-performing channels, we achieved a 15% increase in ROI, optimizing budget use and ensuring marketing efforts are focused on the most profitable channels.
  - This shift resulted in a 4.5% higher conversion rate for campaigns, aligning resources more effectively with customer engagement.
- **Measure and test website conversion performance**
  - An examination of user flow revealed that reducing page load times and improving navigation could increase conversion rates significantly.
  - As a result, enhancements to page load speed led to a 20% reduction in bounce rates and a 12% lift in conversions.
  - By identifying and optimizing high-traffic entry pages, particularly the homepage and key product pages, we reduced drop-offs, boosting total website engagement by 10%.
- **Use data to understand the impact of new product launches**
  - Following the recent launch of a flagship product, product-level analysis found that 3 out of 10 best-sellers contributed 60% of total product revenue.
  - The launch drove a 20% increase in overall sales, validating product-market fit and supporting the strategic focus on high-demand items.
  - Tracking customer responses post-launch revealed a 12% increase in repeat purchases for new and existing products, indicating strong brand loyalty and effective product positioning.

# Recommendations 
Based on the insights from this project, here are actionable recommendations to further enhance business performance:
- **Refine Marketing Channel Investments:**
  - Increase Budget on High-Performing Channels: With 30% of revenue coming from top marketing channels like Google Ads and email campaigns, allocate an additional 15% of the marketing budget to these channels.     - Regularly monitor their performance to maximize ROI while minimizing ad spend on underperforming channels.
  - Optimize Low-Converting Channels: For channels with below-average conversion rates (such as display ads), run targeted A/B tests to refine messaging, audience targeting, or visuals. If results remain low,       - consider redistributing funds to more profitable channels.
- **Continue Enhancing Website Conversion Performance:**
  - Reduce Bounce Rates on Key Pages: With a 20% reduction in bounce rates achieved, focus further optimization on pages with high entry traffic. Implement A/B testing for layouts and calls to action on pages         such as the homepage and top product pages, aiming for an additional 10% decrease in bounce rates.
  - Optimize Checkout Flow: Address the 25% drop-off rate at the checkout stage by simplifying the process, reducing form fields, and adding trust signals (e.g., secure payment icons, testimonials). A seamless        experience can potentially boost conversion rates by 5-10%.
- **Strengthen Product Portfolio and Post-Launch Strategies:**
  - Leverage High-Performing Products: Since 60% of revenue is driven by the top three products, focus marketing efforts on promoting these products. Cross-sell them on lower-performing product pages to boost         visibility and enhance total sales volume.
  - Track New Product Performance Over Time: Given the 20% increase in sales post-launch, regularly assess new product performance, tracking repeat purchases and customer feedback. Use insights to refine future       launches and adjust marketing campaigns to build on initial success.
- **Enhance Data-Driven Decision-Making and Continuous Monitoring:**
  - Implement Real-Time Monitoring: With measurable improvements already achieved, set up real-time dashboards using SQL and BI tools to continuously track conversion rates, revenue by product, and marketing ROI.
  - Perform Quarterly Deep Dives: Conduct quarterly analysis on marketing channel performance, website conversion metrics, and product success rates, enabling proactive adjustments to strategies.


