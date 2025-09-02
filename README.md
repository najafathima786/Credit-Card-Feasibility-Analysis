
# Mitron Bank – Credit Card Feasibility Analysis

## 📌 Project Goal
Mitron Bank, based in Hyderabad, plans to launch a new set of credit cards.  
The objective of this project is to analyze **4000 customer profiles** and their **864K online transactions**  
to understand customer behavior, spending trends, and feasibility of new credit card products.

---

## 📊 Data
- **dim_customers (4,000 rows)** → Customer demographics (age group, gender, occupation, income, city, marital status).  
- **fact_spends (864,000 rows)** → Monthly spend transactions (category, payment type, amount).  

---

## 🔧 Technology Stack
- **SQL (Data Cleaning, Discrepancy Check, Customer_360 & Fact_360 Tables, Metrics)**  
- **Excel / Power BI (Dashboards & Visualizations)**  
- **PowerPoint (Presentation & Business Recommendations)**  

---

## ✅ Key Deliverables
1. **Data Cleaning & Discrepancy Check**  
   - Null check, duplicates, ID mismatches, spend vs income validation.  

2. **360-Degree Views**  
   - `customer_360`: Aggregate customer behavior (income, total spend, payment patterns).  
   - `fact_spends_360`: Aggregate transactions (monthly spend, category spend, spend-to-income ratio).  

3. **High-Metric Analysis**  
   - Total spend, Avg spend per customer, Spend-to-income ratio, Top 10% contribution, Digital adoption, etc.  

4. **Dashboards (4 in Power BI)**  
   - Customer Demographics  
   - Spending Overview  
   - Category Insights  
   - Payment & Income Analysis  

5. **Business Recommendations**  
   - Mass-market card focus (not only premium).  
   - Tiered reward systems.  
   - Category-based offers (Food, Travel, Electronics).  
   - Risk monitoring for overspending customers.  

---

## 📈 Results
- Created **summary tables** reducing 864K rows → 24K profiles for faster dashboarding.  
- Found that **Top 10% customers contribute <20%**, suggesting spending is evenly distributed.  
- Identified strong adoption of **digital payments (UPI & Credit Card)**.  
- Business recommendation → focus on **mass-market tiered credit cards** with category-specific offers.  

---

## 👤 Stakeholders
- **Management & Strategy Team** – Credit card launch decisions  
- **Marketing Team** – Campaign targeting (city, age, category)  
- **Risk & Compliance** – Overspending, income-to-spend ratio monitoring  
- **Product Development** – Reward design & co-branded category cards  
