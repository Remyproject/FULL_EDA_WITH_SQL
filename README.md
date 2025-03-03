# Exploratory Data Analysis (EDA) for Sales Database

This EDA explores a sales database to uncover key business insights. Below is a simple explanation of the analysis performed, designed to be accessible even for non-technical readers.

---

## **Overview**
This analysis answers questions like:  
- Who are our customers?  
- What products do we sell?  
- How much revenue do we generate?  
- Which products or countries perform best?  

All analysis is done using SQL queries on a structured database with tables for customers, products, and sales.

---

## **Purpose**
- **Understand Customer Behavior**: Age, location, and demographics.  
- **Evaluate Product Performance**: Best/worst-selling products, categories, and pricing.  
- **Track Business Health**: Total sales, orders, and revenue trends.  
- **Identify Opportunities**: Highlight areas for growth or improvement.

---

## **Analysis Highlights**

### **1. Database Exploration**
- **Tables & Columns**: Identified all tables (e.g., `customers`, `products`, `sales`) and their columns to understand data structure.

### **2. Customer Insights**
- **Demographics**:  
  - Customers span multiple countries (e.g., USA, Canada).  
  - Age range calculated from birthdates (oldest and youngest customers).  
- **Geographic Distribution**:  
  - Number of customers per country (e.g., most customers in the USA).  
  - Sales distribution across countries.

### **3. Product Insights**
- **Categories**: Products grouped into categories (e.g., Electronics, Apparel).  
- **Pricing**: Average cost per category.  
- **Performance**:  
  - Top 5 products by revenue.  
  - Worst-performing products.  
  - Best-performing subcategories (e.g., Laptops under Electronics).

### **4. Sales Metrics**
- **Revenue**: Total sales and revenue by product/category.  
- **Orders**: Total orders placed and average selling price.  
- **Trends**: First and last order dates to understand sales history.

### **5. Business Health**
- **Key Metrics**:  
  - Total sales: `$29356250`  
  - Total orders: `27659`  
  - Average price per item: `$486`  
  - Total customers: `18484`  

---

## **Key Insights**  
1. **Top Products**: Product A generated the highest revenue.  
2. **Customer Base**: Most customers are from the USA.  
3. **Pricing Strategy**: Electronics have the highest average cost.  
4. **Opportunities**: Subcategory X underperforms—consider promotions.  

---

## **How to Use This Analysis**  
- **Business Decisions**: Focus marketing on high-revenue products/countries.  
- **Inventory Management**: Stock more best-selling items.  
- **Customer Engagement**: Target demographics with tailored campaigns.  

---

## **Conclusion**  
This EDA provides actionable insights to drive growth and efficiency. For example:  
- Expand marketing in top-performing countries.  
- Review pricing for underperforming categories.  

🔗 **Interested in a similar analysis for your business?**  
Feel free to reach out! I specialize in turning raw data into clear, actionable strategies.

---

**Note**: All queries are compatible with SQL Server. Data privacy ensured by using aggregated metrics.  
