# 📉 Customer Churn Analysis

## 📁 Project Overview  
In today’s competitive telecom industry, retaining customers is just as vital as acquiring new ones. With easy switching and numerous service providers, customer churn can significantly impact growth if not managed. This project explores data from 6,418 telecom customers in India to understand churn patterns and uncover key reasons behind customer loss. By analyzing demographics, service usage, payments, and contracts, the goal is to help telecom companies identify at-risk customers and implement targeted strategies to improve retention and long-term growth.

## 🛠️ Tools & Techniques
- **SQL (MySQL)**: Used for data cleaning, transformation, and analysis (ETL).
- **Power BI**: For building dynamic, insightful, and interactive dashboards.

---

## 🎯 Analysis Agenda
The dataset was explored across the following key dimensions:
1. **Demographics** – Age, gender, and personal attributes  
2. **Geography** – Customer distribution by state  
3. **Service Usage** – Internet, phone, add-ons, tenure  
4. **Billing & Payment** – Method, monthly charge, total charges  
5. **Churn Patterns** – Contract type, loyalty, service preferences.
---

## 🔍 Key Insights & Findings

### 🧍 Customer Metrics
- Total Customers: **6,418**
- Active vs Churned: **4,275 stayed**, **1,732 churned**
- New Joiners: **411**
- Churn Rate: **~27%**

  ### Customer Demographics & Behavioral Trends
- **Gender**: Female customers experience a higher churn rate compared to their male counterparts.  
- **Age**: Senior citizens are more likely to churn than younger customers.  
- **Tenure**:  
  - On average, customers who later churn spent around 18 months with the company.  
  - Notably, 26.37% of the churned customers had stayed for less than six months.  
- **Contract Details**:  
  - Customers with two-year contracts are very stable, showing a churn rate of only about 3%.  
  - In contrast, almost 47% of customers on a month-to-month plan decide to leave.  
- **Referral Count**: Customers with fewer than four referrals tend to have higher churn rates.

  ### Impact of Service Types
- **Phone Services**: Appear to have a smaller impact on churn compared to Internet services.  
- **Service Preference by Age**:  
  - A larger percentage of senior citizens opt for both services, indicating that old people have a stronger desire for more telecom services.  
- **Internet Types**:  
  - Fiber Optic users are more prone to churn, potentially due to issues like poor connectivity or outdated infrastructure.  
  - DSL vs. Fiber Optic: A higher churn rate is observed with fiber optic customers.  
- **Multiple vs. Single Lines**:  
  - Around 1.4K adult customers prefer using multiple lines, whereas 2.2K customers use a single line.

### Payment Behavior Observations
- **Payment Methods**:  
  - Customers using bank withdrawals and credit card payments are more consistent.  
  - Those relying on mailed checks tend to have a higher churn rate.  
- **Monthly Payment Insights**:  
  - Customers paying between 80 and 100 currency units face a high churn rate of 33.28%.  
  - In contrast, customers paying less than 20 units per month are generally more stable.  
- **Link Between Payment & Services**:  
  - The higher-paying group predominantly subscribes to Fiber Optic services, which may explain their higher churn rate.

### Geographic Trends
- **Regional Churn Patterns**:  
  - **High Churn States**: Jammu & Kashmir, Assam, and Jharkhand emerge as the top states for customer churn—with Jammu & Kashmir alone contributing to 57% of the overall churn.  
  - **Low Churn States**: Gujarat, Madhya Pradesh, and Uttarakhand exhibit significantly lower churn rates.

### Reasons for Churn
The top reasons customers are leaving include:  
- Better devices offered by competitors  
- More attractive offers from competitors  
- Poor attitude of support staff

---

## ✅ Recommendations

### • Revamp Promotional Offers
Since "competitors making better offers" is the top reason customers are leaving, it's crucial to update our promotional strategy. More than half of our customers aren't aware of any current offers. By boosting advertising efforts and highlighting new promotions, we can better capture their attention and keep them interested.

### • Enhance Customer Support
About 12% of customers left because they were dissatisfied with the attitude of our support staff. Offering additional training for our support teams can help improve customer satisfaction and ensure our service feels welcoming and responsive.

### • Improve Fiber Optic Service
Customers using our Fiber Optic internet have a higher likelihood of leaving, probably due to device issues and the higher price compared to other types of internet services. Since many of these customers rely on streaming services, boosting the connection quality and rethinking our pricing strategy could make Fiber Optic more attractive and reduce churn.

### • Offer Flexible Contract Options
Our current contract choices—month-to-month, yearly, and 2-year plans—offer little price variation, which may discourage long-term commitments. Introducing discount rates for long-term contracts and adding options like 3-month and 6-month plans could provide the flexibility customers seek and encourage longer commitments.

### • Retain At-Risk Customers
Even among our loyal customers, around 65% are at high risk of churning. To keep these customers engaged and satisfied, consider introducing measures like exclusive discounts on monthly bills, a points-based loyalty program, or personalized incentives based on their usage patterns. These targeted efforts can make customers feel valued and encourage them to stay with the company for the long term.

### • Recommendation for Senior Citizens
Senior citizens often face difficulties with complex plans and tech support, which can lead to frustration and higher chances of leaving. To better serve this group and improve retention, the company should introduce “family bundles” where senior citizens can be added to their family members’ plans at a discounted rate. This adds value while keeping them connected with loved ones. Offering regular feedback or check-in calls, and a dedicated support team trained to assist elderly users with patience and clarity can significantly enhance their overall experience and build long-term trust with the brand.

---

By adopting these strategies, we can improve customer satisfaction and reduce churn rates effectively.

  
