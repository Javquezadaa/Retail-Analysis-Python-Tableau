# Retail Customer Segmentation and Sales Analysis

This project analyzes a large-scale retail dataset to understand customer behavior, identify top-performing brands and countries, perform customer segmentation, and develop actionable business recommendations through data visualization and predictive modeling.

---

## Objective

The main objectives of this project are:

- Understand customer purchasing behavior across segments and regions  
- Identify key product brands driving purchases and revenue  
- Build customer clusters to guide segmentation strategies  
- Uncover time-based revenue trends and seasonality  
- Evaluate predictive models to support marketing and forecasting decisions  

---

## Key Business Questions

### Customer Behavior Patterns

- Which customer segments contribute the most revenue?  
- How do customer ratings vary by segment and spending?  
- Which regions and countries generate the highest revenue?  
- What behaviors and patterns emerge across clusters?

### Product and Brand Insights

- Which brands dominate in terms of purchase frequency and revenue?  
- How do product categories perform across clusters?

### Time Series and Forecasting

- What is the monthly revenue trend over time?  
- Are there repeating seasonal patterns?  
- What do autocorrelation plots and model residuals suggest about forecasting complexity?

### Segmentation and Modeling

- What customer profiles emerge from clustering?  
- How accurately can we predict total spending from the number of purchases?

---

## Tools and Technologies

- **Tableau** – Interactive dashboards and visual storytelling  
- **Python** – Data preprocessing, visualization, clustering, and regression  
- **Libraries:** pandas, matplotlib, seaborn, scikit-learn, statsmodels  
- **Jupyter Notebook** – For analysis and modeling  

---

## Data

- **Dataset Title:** Retail Analysis – Large Dataset  
- **Source:** Kaggle (by Sahil Prajapati)  
- **Link:** Kaggle Dataset  
- **Period Covered:** 2023–2024 (monthly transaction records)  
- **Sample Size Used:** A representative subset of approximately 500,000 rows  
- **Scope:** Includes demographic info, purchase behavior, product and brand data, payment and shipping methods, and ratings.

---

## Final Deliverables

### Tableau Dashboard Featuring:

- Segment-based spending analysis  
- Brand and product purchase visualizations  
- Geographic revenue mapping  
- Time series trends and decomposition  
- Customer clustering visualizations  

### Python Analysis Notebook:

- Clustering (KMeans)  
- Linear regression  
- EDA visualizations  

### Documentation:

- Business recommendations by segment and brand  
- Forecasting limitations and future modeling notes  

---

## Stakeholders

- **Marketing Leadership** – Target campaigns based on customer segments and regions  
- **Sales Directors** – Identify underperforming or high-potential brands and geographies  
- **Data Science Teams** – Use clustering and modeling as inputs for deeper ML work  
- **Business Executives** – High-level strategic insights from customer segmentation  

---

## Key Insights Summary

- **Top Brands:** Pepsi, Coca-Cola, and Harper Collins lead in total purchases  
- **Geography:** USA leads with 32% of customers  
- **Segments:** Regular customers drive most revenue; Premium shows smaller but important contributions  
- **Ratings:** Most customers gave positive feedback (Good or Excellent)  

### Clusters – Potential Business Applications

- **Cluster 3 – Loyalty or VIP Rewards**  
  These customers represent our highest value segment in terms of spending and purchase frequency. Implementing loyalty programs or VIP perks can help retain them and encourage long-term brand commitment.

- **Cluster 1 – Upselling or Premium Offers**  
  This segment is already actively engaged, showing solid purchasing behavior. Offering premium products, bundles, or exclusive upgrades could increase their average spend and enhance customer lifetime value.

- **Cluster 0 – Promotional Campaigns**  
  With moderate spending patterns, these customers may respond well to seasonal promotions, discounts, or limited-time offers that incentivize them to spend more frequently.

- **Cluster 2 – Re-engagement Campaigns**  
  Despite being the largest cluster, these users show the lowest engagement and spend. This group presents an opportunity for growth through reactivation strategies—such as welcome-back campaigns, personalized outreach, or onboarding journeys to drive conversion.

- **Revenue Trend:** Downward trend with clear 6-month seasonal pattern  
- **Regression:** Total purchases predict spending moderately well, with room for model improvement  

---

## Future Use Cases

- Personalized marketing based on clusters  
- Product recommendations driven by segment behavior  
- Campaign strategies for loyalty, upsell, and reactivation  
- Forecasting with external and seasonal variables  

---

## Portfolio and Tableau Links

- **Portfolio:** [Your Portfolio Link Here]  
- **Tableau Dashboard:** [Retail Analysis on Tableau](https://public.tableau.com/views/Achievement6_RetailAnalysis/Story1?:language=en-US&:sid=&:redirect=auth&publish=yes&showOnboarding=true&:display_count=n&:origin=viz_share_link)
