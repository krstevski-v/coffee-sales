# Coffee Shop Performance & Customer Analysis
**Tools:** Excel, Tableau

## 1. Project Overview
This project analyzes customer, product and orders data from a coffee shop to address the following key business questions:
   1. **Product Mix Optimization**: Which specific combinations of coffee types, roast profiles, and package sizes are the primary revenue drivers, and how should this influence our inventory and procurement strategy?
   2. **Growth & Seasonality Intelligence**: How do sales and profit margins fluctuate annually and monthly, and what specific windows offer the greatest opportunity for high-impact seasonal promotions?
   3. **Customer Value & Geographic Footprint**: Where is our customer base most concentrated geographically, and how many high-value customers do we have?

You can view the dashboard on my Tableau Public account by clicking on [this link](https://public.tableau.com/views/CoffeeShopDashboard_17615084777500/SalesDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).


## 2. Data
The dataset consists of three different tables:
<img width="766" height="247" alt="image" src="https://github.com/user-attachments/assets/c45a5569-136c-42c0-8607-c54cc2684b04" />



## 3. Analysis & Insights
The analysis is divided into two main areas: Sales Performance and Customer Behaviour.
### A.  Sales
  Based on the most recent full year of data(2024) we observe the following:

  <details>

  * Total sales and quantities sold are have increased compared to the previous year. Both peaked in March and reached their lowest point in August.
<img width="663" height="342" alt="image" src="https://github.com/user-attachments/assets/b9d4ae1f-5ff8-4d5a-a283-c31e16d5a4a9" />

<img width="663" height="346" alt="image" src="https://github.com/user-attachments/assets/b210adac-109b-4a1e-aa43-49922389360d" />

---

  * Liberica is the most popular coffee type and Light Roast is the most popular roast type. Conversely, Arabica and Dark are least in demand.
  
<img width="431" height="437" alt="image" src="https://github.com/user-attachments/assets/11067fde-771f-463d-9717-dfaca619a65b" />

---

   * Bulk sizes(1kg and 2,5kg) dominate the sales:

<img width="432" height="441" alt="image" src="https://github.com/user-attachments/assets/d7022996-061b-4116-aac2-95ddf3219680" />

</details>

### B. Customers
Key findings regarding customer demographics and ordering habits(2024):

<details>

* Total order volume has increased significantly compared to the previous year, even though the customer count has remained relatively stable.
<img width="663" height="342" alt="image" src="https://github.com/user-attachments/assets/a92684aa-e623-45f6-9d53-142e99f5f6e6" />
<img width="663" height="344" alt="image" src="https://github.com/user-attachments/assets/649766c5-6b59-43bb-b08d-c6039e90edb7" />

---

* The vast majority of the customers are located within the United States:

 <img width="569" height="573" alt="image" src="https://github.com/user-attachments/assets/0f221a8b-008b-48a0-a2a1-7c7a1965ac78" />

---

* A high percentage of the customers were one-time buyers:

<img width="569" height="573" alt="image" src="https://github.com/user-attachments/assets/dea4b959-cc31-43e7-9489-dbdfa2c9e5da" />

---

### RFM Analysis

The RFM model segments customers based on their buying behavior from 2019 to 2024. The total RFM score(ranging from 3 to 15) is the sum of three metrics:
   * Recency(R): Days since last purchase. Higher scores indicate recent activity.
   * Frequency(F): Total number of orders placed. More frequent buyers receive higher scores.
   * Monetary(M): Total lifetime spend. Customers with higher total investment receive higher scores.

The table below displays the distribution of the historical customer base across five segments, from Tier 5(worst) to Tier 1(best). For detailed calculations and individual scores, refer to the Excel workbook.

<img width="376" height="208" alt="image" src="https://github.com/user-attachments/assets/7558e4a8-b1d7-4594-9278-ac96e6ae36d8" />


   
</details>


## 4. Conclusions & Recommendations
 ### Key Conclusions
 
1. Liberica coffee and Light Roasts are the most consistent profit-makers. Large package sizes (1kg+) are the preferred choice for the majority of our revenue.
2. Despite a brief dip in 2020, annual sales have trended upward for four consecutive years. While March and June are peak months, the lack of extreme monthly volatility suggests a steady, non-seasonal demand.
3. The United States remains our primary market. While the majority of the customer base is healthy, a small portion (50 customers) is currently classified as "At Risk" based on RFM scores.


### Business Recommendations

1. Since a large share of customers only purchase once, implement a second-purchase discount code to convert these individuals into repeat buyers.
2. Given that 80% of revenue comes from 1kg and 2,5kg bags, consider offering bulk-buy incentives such as "Subscribe & Save" options for these sizes to secure predictable, recurring revenue.
3. Launch marketing campaigns aimed at retaining Tier 4 and Tier 5 customers to prevent permanent churn.


