# 📊 Amazon Sales Analysis Project
### Internship Task – InnoByte Services

---

## 📌 Project Overview
This project is an end-to-end Exploratory Data Analysis (EDA) of Amazon sales data.  
The goal is to extract meaningful business insights by analyzing:

- Sales trends  
- Product performance  
- Customer behavior  
- Fulfillment efficiency  
- Geographical order distribution  

The project helps understand how sales are performing over time, which products customers prefer, how effective fulfillment methods are, and which regions generate the most orders.

---

## 📁 Dataset Description
The dataset consists of **Amazon sales transactions**, where each row represents a unique order.  
Important fields include:

- **Order ID** – Unique identifier for each order  
- **Date** – When the order was placed  
- **Status** – Shipped, Delivered, Cancelled, Returned, etc.  
- **Fulfilled By** – Amazon, Easy Ship, Merchant  
- **Category** – T-shirt, Shirt, Saree, Blazer, etc.  
- **Size** – Product size variant  
- **Qty (Quantity)** – Number of units ordered  
- **Amount** – Total order value  
- **ship-city / ship-state** – Customer location  
- **Courier Status** – Shipping stage  
- **B2B indicator** – Business or individual buyer  

This dataset is suitable for understanding product demand, logistics performance, customer behavior, and revenue trends.

---

## 🧹 Data Cleaning & Preparation
To ensure high-quality analysis, several preprocessing steps were applied:

### ✔ Convert Dates  
The `Date` column was converted to `datetime` format for monthly trend analysis.

### ✔ Handle Missing Values  
Missing values were replaced with `"Unknown"` to maintain dataset consistency.

### ✔ Convert Amount to Numeric  
The `Amount` column was cleaned and converted into a numeric format.

### ✔ New Features  
A new column `Month` was created using the order date to analyze monthly sales performance.

### ✔ Standardize Text Fields  
Category and Fulfillment fields were cleaned to avoid duplicates caused by formatting.

These steps ensure that the data is clean, consistent, and ready for analysis.

---

## 🔍 Analysis Performed

### **1. Sales Overview**
- Calculated total revenue  
- Visualized monthly sales trends  
- Identified high and low sales periods  

### **2. Product Analysis**
- Identified top-selling categories  
- Analyzed quantity distribution  
- Compared demand across product types  

### **3. Fulfillment Analysis**
- Determined which fulfillment method is most used  
- Checked potential logistic inefficiencies  

### **4. Customer Segmentation**
- Analyzed order frequency by city  
- Identified major customer regions  
- Detected presence of repeat buyers  

### **5. Geographical Analysis**
- Top-performing states and cities  
- Regional demand variations  
- Customer density patterns across India  

---

## 📊 Visualizations
The project uses various visual tools to present insights clearly:

### 📈 Line Charts
- Monthly sales trend (March–June)

### 📊 Bar Charts
- Best-selling product categories  
- Quantity sold distribution  
- Fulfillment method distribution  
- Top cities and states by orders  
- Order status and courier status  

### 🟠 Pie Charts
- B2B vs Individual buyer share  

Visualization Libraries Used:
- **Matplotlib**
- **Seaborn**

---

## 💡 Key Insights

### 🔹 Sales Insights
- Sales vary significantly across months.  
- April shows the highest sales spike.  
- Total revenue exceeds several crores (based on dataset).

### 🔹 Product Insights
- **T-shirts and Shirts** dominate sales.  
- Most customers order **quantity = 1**.  
- Very few bulk orders are placed.

### 🔹 Fulfillment Insights
- **Easy Ship** is the most commonly used fulfillment method.  
- Some records have "Unknown" fulfillment, indicating missing tracking.

### 🔹 Customer Insights
- Cities like **Bengaluru, Hyderabad, Mumbai, and Delhi** generate the most orders.  
- High customer activity is seen in metro and Tier-1 cities.  
- Very few repeat or B2B buyers.

### 🔹 Geographic Insights
- **Maharashtra, Karnataka, Tamil Nadu, Telangana, and Uttar Pradesh** lead in total orders.  
- These are high-demand regions where businesses should focus sales and logistics efforts.

---

## 🎯 Recommendations

### ✔ Improve Inventory for Top Categories
Stock more T-shirts, Shirts, and fast-moving items.

### ✔ Boost Customer Retention
Introduce loyalty programs, cashback rewards, and personalized recommendations.

### ✔ Enhance Fulfillment Efficiency
Improve tracking for fulfillment fields; expand Easy Ship where possible.

### ✔ Promote Combo Deals
Since most orders are Qty = 1, combo offers can increase order value.

### ✔ Target High-Performing Regions
Run sales campaigns and ads in Bengaluru, Hyderabad, Mumbai, and other top cities.

### ✔ Reduce Cancellations
Provide better delivery communication and flexible delivery slots.

---

## 🛠 Tech Stack

### **Languages & Environment**
- Python  
- Jupyter Notebook  

### **Libraries**
- Pandas – Data cleaning & manipulation  
- NumPy – Numerical operations  
- Matplotlib – Chart plotting  
- Seaborn – Advanced visualizations  

These beginner-friendly tools make the analysis simple, understandable, and efficient.

---

## 📂 Project Structure

