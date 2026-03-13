☕ Maven Cafe: Rewards Strategy Analysis

Role: Senior Marketing Analyst
Tool: Power BI (Power Query, DAX, Data Modeling)

📋 Project Overview
Maven Cafe conducted a 30-day test by sending various promotional offers (BOGO, Discounts, Informational) to rewards members. The goal of this analysis is to identify key customer segments and develop a data-driven strategy for future promotional messaging and targeting.

🎯 Business Objectives:
Identify which offer types (BOGO vs. Discount) drive the highest conversion.

Determine the most effective communication channels (Email, Web, Social, Mobile).

Segment customers based on demographics (Age, Income, Gender) to optimize targeting.

🚀 Key Insights
Top Performer: Discount offers emerged as the most successful, achieving a 53% redemption rate.

Channel Efficiency: Social Media and Web channels showed a significantly higher "View-to-Completion" correlation than Email alone.

Demographic Sweet Spot: Female customers with an income bracket of $60k - $80k showed the highest average transaction value when responding to BOGO offers.

Engagement Lag: Informational offers have high view rates but require a stronger "Call to Action" or secondary reward to drive actual transactions.

🛠️ Technical Implementation
1. Data Modeling
Built a Star Schema connecting three primary tables: Offers, Customers, and Transcript (Events).

Handled many-to-many relationships between offers and transactions using a bridge table logic to ensure accurate attribution.

2. Advanced DAX Measures
Conversion Rate: Calculated the percentage of Viewed offers that resulted in a Completed transaction.

Attributed Revenue: Isolated revenue generated specifically during an active offer window versus organic spending.

Offer Velocity: Measured the average time from "Offer Received" to "Offer Completed."

3. Power Query (ETL)
Cleaned and formatted JSON-style strings in the Transcript table to extract Offer IDs and Transaction amounts.

Filtered out "ghost" completions (where a user completed an offer they never actually viewed).

📊 Dashboard Preview
![Maven Cafe Dashboard](images/customer.png)
![Maven Cafe Dashboard](images/offer.png)

💡 Recommendations
Double down on Social: Prioritize BOGO offers through social media channels for the 18–35 age demographic.

Reward Loyalty: Shift the "Discount" strategy to focus on long-term members (3+ years) to maintain high retention.

Refine Informational Content: Use informational ads primarily for new product launches, following up with a discount code 48 hours later to close the sale.
