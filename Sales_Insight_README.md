# 📊 Sales Insight Dashboard

This Power BI dashboard provides an interactive overview of sales performance, revenue trends, and customer insights. It helps users explore key metrics like total revenue, sales quantity, revenue by market, and top-performing products.

---

## ✨ Key Features

✅ Revenue Analysis: Visualizes total revenue by customer, date, and product.  
✅ Sales Quantity: Displays total sales quantity by customer and product.  
✅ Revenue by Market: Highlights revenue distribution across different markets.  
✅ Top Products: Shows sales amounts and trends by product category.  
✅ Dynamic Year Filter: Allows users to filter visuals by year for easy comparison.

---

## 📁 Files Included

- `sales_insight.pbix` — The Power BI dashboard file.  (https://drive.google.com/file/d/1ZBPR2Uu3OyCfJvv_io2nTrQxCWjQpd3y/view?usp=drive_link)
- `README.md` — This documentation file.  
- `sales_dinsight_Relationship` — (https://drive.google.com/file/d/1FPWVVCpciNXvqjGYiObcwMCx7tQ_RssD/view?usp=sharing)

---

## 🔗 Data Source

This project uses a sample SQL dataset consisting of the following tables:

- CUSTOMER — Customer details (ID, name, region, etc.).  
- DATE — Date details (year, month, day, etc.).  
- MARKET — Market information.  
- PRODUCT — Product information (ID, name, category).  
- TRANSACTION — Transaction data with references to the above tables.

🗂️ **Data Download:**  
Download the sample SQL file from Google Drive:  
📥 [Download sales_data.sql from Google Drive](https://drive.google.com/file/d/1HiV4McN4M5fdo5h8rfEdM53biniBnL1m/view?usp=drive_link)

---

## 🚦 How to Import the Data

### Step 1. Import the SQL Data into MySQL

1. Download the file from the link above and place it on your desktop 
2. Open MySQL Workbench (or any MySQL client).  
3. Create a New Database:  
   - For example: `sales_db`.  
4. Run the Script:  
  - Using MySQL Workbench:  
  - Open the `.sql` file.  
  - Execute the script to create tables and insert data.  
### Step 2. Connect Power BI to MySQL

1. Open Power BI Desktop.  
2. Click **Home > Get Data > MySQL database**.  
3. Enter the server name (e.g., `localhost`).  
4. Enter the database name you created (e.g., `sales_db`).  
5. Select the relevant tables: CUSTOMER, DATE, MARKET, PRODUCT, and TRANSACTION.  
6. Click **Load** to import the data.  
7. Define relationships between the tables if needed.  
   ![Power BI connect to MySQL](images/powerbi-connect-mysql.png)

---

## 💡 Notes

- Make sure your MySQL server allows connections from Power BI (ensure the MySQL ODBC driver is installed).  
- If you plan to share this project with others, ensure the `.sql` file download link is accessible.  
- Anonymize any sensitive data in your `.sql` file before sharing publicly.

---

## 🚀 Future Improvements

- Add drill-through pages for customer and product-level insights.  
- Include dynamic tooltips and additional filters.  
- Integrate real-time data refresh using DirectQuery (if needed).  
- Enhance visuals with custom DAX measures.

---

## 📬 Contact

For questions or suggestions, please open an issue on GitHub or contact 
Email:[bmedhivyasrini@gmail.com]
Linkedin:www.linkedin.com/in/dhivyapriya30

---


**Happy Exploring! 🚀**


