# Walmart Customer Retention Analytics — Power BI Project

## 🏢 Company
**Walmart**

## ❓ Problem Statement
Walmart needed to understand **why customers churn, which loyalty tiers are most at risk, and how store performance and promotions affect customer retention**. This project uses Power BI to model customer, transaction, loyalty, and store data into an interactive dashboard that surfaces retention issues and drives data-backed business recommendations.

## 🎯 Objective
- Analyze customer churn behavior and loyalty tier performance
- Understand purchase frequency and repeat-buying patterns
- Evaluate promotion effectiveness and loyalty points redemption
- Compare store performance and retention across store age/type
- Calculate Customer Lifetime Value (CLV)
- Build an interactive multi-page dashboard for management

## 🛠️ Tools Used
- Microsoft Power BI
- Power Query
- Data Modeling
- DAX
- Interactive Dashboards
- Slicers

## 📂 Dataset Overview
- ~300 customers
- ~1,000 transactions
- 5 connected tables (Customer, Transaction, Loyalty, Store, and related data)

## 🔧 Process (8 Tasks)

**1. Data Modelling**
- Built a data model connecting 5 tables via `Customer_ID` and `Store_ID`
- Used one-to-many relationships to support accurate DAX calculations and visuals

**2. Customer Churn Analysis**
- Calculated overall churn rate and compared churn across loyalty tiers and customer segments

**3. Purchase Behaviour Analysis**
- Segmented customers by purchase frequency (low/mid/high-tier buyers)

**4. Loyalty & Promotion Impact**
- Measured promotion usage rate vs. resulting revenue lift
- Analyzed loyalty points redemption rates across tiers

**5. Store Performance Analysis**
- Compared retention across store types and store opening years

**6. Customer Lifetime Value (CLV)**
- Calculated average CLV and compared CLV across loyalty tiers

**7. Dashboard Build**
- Built a 4-page interactive Power BI dashboard:
  - Page 1: KPIs (churn rate, repeat purchase rate, CLV)
  - Page 2: Loyalty & promotion analysis
  - Page 3: Store performance & retention trends
  - Page 4: Customer segmentation & behavioral insights
- Added slicers for loyalty tier, store type, and customer category

**8. Business Recommendations**
- Translated findings into actionable retention strategy

## 📊 Key Insights
- **Overall churn rate is ~49.67%** — nearly 1 in 2 customers has stopped purchasing
- **Elite tier customers have the highest churn rate**, despite being the premium segment
- **~57.5% of customers are low-frequency buyers**, creating a repeat-purchase challenge
- Promotions were applied to **almost half of all transactions but showed close to zero revenue lift** — acting as discounts rather than growth drivers
- **Loyalty points redemption is low across all tiers**, suggesting the rewards program isn't engaging enough
- **Stores opened after 2015 retain customers significantly better** than stores opened before 2000
- **Average CLV is ~₹489**, but **Elite tier has the lowest CLV** of all segments — confirming the loyalty program underperforms for its most premium customers

## ✅ Recommendations
1. Redesign Elite tier benefits with more personalized engagement to reduce churn
2. Shift promotion strategy toward increasing basket size rather than blanket discounts
3. Simplify the loyalty points redemption process to boost engagement
4. Run targeted campaigns to convert low-frequency buyers into repeat customers
5. Modernize older stores to improve customer experience and retention

## 🧠 Skills Demonstrated
Power BI • Power Query • Data Modeling • DAX • Interactive Dashboard Design • KPI Development • Customer Segmentation • Churn Analysis • Customer Lifetime Value (CLV) • Business Intelligence

## 📈 Business Impact

The analysis identified key drivers of customer churn, loyalty program inefficiencies, and store performance trends, enabling data-driven recommendations to improve customer retention, optimize promotional strategies, and enhance long-term customer value.
