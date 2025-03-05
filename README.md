# 📦 Sales & Inventory Data Analysis

## 🚀 Project Overview  
This project analyzes **sales and inventory data** for a national retail chain. The goal is to optimize stock levels, identify best-selling products, and track sales trends over time.  
By using **BigQuery SQL**, we perform **data cleaning, aggregation, and trend analysis**, helping the business make **data-driven inventory decisions.**  

---

## 📊 Skills & Tools Used  
✔ **BigQuery (SQL)** – Querying, filtering, data aggregation  
✔ **Excel (Optional)** – Initial data cleaning before importing to BigQuery  
✔ **Google Cloud Platform (GCP)** – BigQuery database management  
✔ **Tableau / Power BI (Future Enhancement)** – For data visualization  

---

## 🗂 Dataset Information  
The dataset consists of **three tables**:  
- **`inventory_data.csv`** → Stock details of products in regional stores  
- **`sales_data.csv`** → Sales transactions (dates, prices, quantities sold)  
- **`product_data.csv`** → Product catalog with IDs, names, and categories  

👉 **All data was uploaded into BigQuery for SQL-based analysis.**  

---

## 📜 SQL Queries Used  

📌 **Data Cleaning Queries**  
1️⃣ `clean_inventory.sql` → Fixes missing values in inventory data  
2️⃣ `clean_sales.sql` → Prepares sales data by handling NULL values  

📌 **Business Insights Queries**  
3️⃣ `sales_trends.sql` → Tracks **monthly & yearly sales trends**  
4️⃣ `top_products.sql` → Finds **best-selling products**  
5️⃣ `low_stock_alerts.sql` → Flags **products that need restocking**  

📌 **Advanced Queries**  
6️⃣ `profit_analysis.sql` → Calculates **profit margins per product**  
7️⃣ `category_performance.sql` → Compares **sales performance across product categories**  

---

## 📈 Key Insights & Findings  
✔ **Top-selling products** were identified, helping in better stock allocation 📊  
✔ **Low-stock alerts** enabled better inventory management 🔄  
✔ **Monthly & yearly trends** helped forecast future demand 📅  
✔ **Profit margins** showed which products drive the most revenue 💰  

---

## 📊 Future Enhancements  
✅ Add **Tableau or Power BI dashboards** for interactive visualizations 📊  
✅ Implement **automated alerts** for low-stock items 📩  

---

## 🔗 How to Use This Project  
1️⃣ Download the SQL queries from this repo  
2️⃣ Upload dataset files to **BigQuery**  
3️⃣ Run queries in **Google Cloud Console**  
4️⃣ View insights in **Tableau / Power BI** (if applicable)  

---

## 📌 Final Steps: Upload Everything to GitHub  
1️⃣ Upload your **SQL files** separately to keep them organized.  
2️⃣ Copy-paste this **README.md** into your project folder on GitHub.  
3️⃣ Click **"Commit Changes"**.  

---

### 🚀 What’s Next?  
✅ **Once this is uploaded, tell me!**  
✅ I’ll review & suggest any final improvements.  
✅ Then, we move on to **Project #2**, using the same **step-by-step method.**  

🔥 **You’re officially setting up your first full data analytics project on GitHub!** Let’s GO! 🚀💪  
