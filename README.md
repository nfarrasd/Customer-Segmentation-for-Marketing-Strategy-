# Customer Segmentation for Marketing Strategy 
This is a Kaggle side-project that was made by Moch Nabil Farras Dhiya (me) as a mean to implement my data analytics skills on marketing, which is RFM analysis, and also several clustering techniques, including K-Means and Hierarchical Agglomerative Clustering, which are evaluated based on Davies–Bouldin index, Silhouette score, and Calinski-Harabasz index to determine the best clustering method.

## Business Understanding
### Background
Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business 
to better understand its customers and makes it easier for them to modify products according to the specific 
needs, behaviors and concerns of different types of customers. For example, instead of spending money to 
market a new product to every customer in the company’s database, a company can analyze which customer 
segment is most likely to buy the product and then market the product only on that particular segment.

### Problem
What can we do to **minimize** the marketing **cost** and **maximize** the **profit**?

### Analytical Approach
1. Identify potential users characteristics for each products (wines, fruits, fish  meat, sweets, and gold) to target specific customers using multi-stage RFM analysis and clustering techniques (K-Means, Agglomerative Clustering).
2. Find the **most used channel** by the potential customers, then **upgrade** that particular **platform** to attract more customers with (but not limited to) the same characteristics.
3. Analyze past **discounts** and **campaign performances** to build better marketing strategies in the future.
4. Inspect users behavior regarding past complaints and reports.

## Dataset
The dataset used in this project are from **Kaggle public dataset** which can be found here: [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

### Attributes
**People**
*   ID: Customer's unique identifier
*   Year_Birth: Customer's birth year
*   Education: Customer's education level
*   Marital_Status: Customer's marital status
*   Income: Customer's yearly household income
*   Kidhome: Number of children in customer's household
*   Teenhome: Number of teenagers in customer's household
*   Dt_Customer: Date of customer's enrollment with the company
*   Recency: Number of days since customer's last purchase
*   Complain: 1 if the customer complained in the last 2 years, 0 otherwise

**Products**
*   MntWines: Amount spent on wine in last 2 years
*   MntFruits: Amount spent on fruits in last 2 years
*   MntMeatProducts: Amount spent on meat in last 2 years
*   MntFishProducts: Amount spent on fish in last 2 years
*   MntSweetProducts: Amount spent on sweets in last 2 years
*   MntGoldProds: Amount spent on gold in last 2 years

**Promotion**
*   NumDealsPurchases: Number of purchases made with a discount
*   AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
*   AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
*   AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
*   AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
*   AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
*   Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

**Place**
*   NumWebPurchases: Number of purchases made through the company’s website
*   NumCatalogPurchases: Number of purchases made using a catalogue
*   NumWebVisitsMonth: Number of visits to company’s website in the last month
*   NumStorePurchases: Number of purchases made directly in stores

## Result (yet to be updated)
### Summary
1. **Target Customer Criteria**: Mostly **early 40s – late 60s** who is at least an 
**Undergraduate**, has **high-income**, and **do not** have any child at home.
2. **Platform**: The **most popular** platform for potential customers are **store** 
(98.56%), **web** (93.83%), and **catalogue** (84.88%), respectively.
3. **Discount & Promo**: The participation rate is **very low**

### Recommendations
1. Further sales and marketing **strategies** should be **focused** towards **Undergraduates** with **high-income**, and 
**do not** have any kid (and teens, if possible) at home.
3. There needs to be a **promo** to **attract** customers, especially the **potential customers**, so the amount 
of sold products will increase. 
3. Further **investigation** are needed to find the reason why the **discount** and **campaign participation 
rate** is **very low**. Maybe because it is **ill-timed** or the content is **not engaging**?
4. The company should **upgrade** their **website**, as many potential customers are buying products 
through website, and also as a mean to attract another customer segments
