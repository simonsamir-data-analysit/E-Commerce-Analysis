# E-Commerce-Analysis

Five years of revenue, and it never grew.

That is what our E-commerce Analytics project in Power BI showed us. Here is how it came together.

The data covers 2021 to 2025 for an Egyptian online retailer: 5,000 customers, 10,000 orders, 16,600 order lines, 1,200 products, plus payments, shipments, returns, reviews and 15,000 marketing events. I modeled it as a star schema with a custom calendar table and built a 34-page report on top of it.

What’s inside:

Executive Summary
Sales: channels, governorates, devices, YoY growth
Customers: churn, retention, CLV
Products: margin, price elasticity, supplier country
Marketing: funnel, ROAS, CAC, campaign ROI
Shipping: on-time rate by carrier and warehouse
Payments, Returns and Reviews
Strategies and a two-quarter roadmap

DAX measures we are proudest of:

Churned Customers: no purchase in the last 90 days of the data
Attributed Revenue: sales tied to marketing purchase events
On-Time Delivery %: actual delivery date against the promised date
Also in the model: Gross Margin, Net Profit, YoY Sales Growth, Retention Rate, CAC, ROAS, NPS, Return Rate

I also set up page-level security with USERPRINCIPALNAME(), so each person only sees the dashboards for their department.

What the data showed:

Delivered revenue stayed between EGP 3.9M and 4.2M every year
42% of customers who bought once never came back
VIP customers spend about the same as new ones (EGP 5,368 vs 5,054), so the tiers aren’t changing behavior
Only 57.7% of shipments arrive by the promised date, and every carrier is close to that number
Returns are 7.4% of orders, about EGP 1.54M in refunds
78.6% of reviews are positive, so the weak points are operations, not the product
Meta and TikTok bring customers in at a lower cost than affiliate and email

From this I wrote a 0 to 180 day roadmap: fix delivery date estimates first, push the second purchase, rebuild loyalty tiers, move 10 to 15% of affiliate and email budget to Meta and TikTok, and find out why Cairo underperforms.


