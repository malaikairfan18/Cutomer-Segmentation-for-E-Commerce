[Customer Segmentation for E-Commerce.docx](https://github.com/user-attachments/files/19028369/Customer.Segmentation.for.E-Commerce.docx)
# Customer Segmentation for E-commerce

## Introduction
Customer segmentation is a crucial technique in e-commerce that helps businesses understand their customers by grouping them based on purchasing behavior. This project utilizes **Recency, Frequency, and Monetary (RFM) Analysis** to classify customers into segments such as **Big Spenders, General Customers, One-Time Buyers, and Lost Customers**.

## Dataset
We used the **Online Retail Dataset** from Kaggle, containing transactional data like invoice details, product descriptions, quantity, unit price, customer IDs, and purchase dates.

## Features Used for Segmentation:
- **Recency** – Days since the customer's last purchase  
- **Frequency** – Total number of purchases  
- **Total Spent** – Amount spent by the customer  
- **Quantity** – Total items purchased  

## Data Preprocessing:
✔ Removed missing **CustomerID** values  
✔ Filtered **positive quantity** transactions  
✔ Created **TotalSpent = Quantity × Unit Price**  
✔ Converted **InvoiceDate** to datetime format  

## Segmentation Approach
We applied **RFM Analysis** and categorized customers based on predefined business logic:

| **Segment**           | **Description**  |
|----------------------|-----------------|
| **Big Spenders**     | High spending, low frequency |
| **General Customers** | Regular buyers with moderate spending |
| **One-Time Buyers**  | Customers who made only one purchase |
| **Lost Customers**   | Customers who haven’t purchased in a long time |

## Data Visualization  
To understand customer distribution and spending patterns, we used **Matplotlib** and **Seaborn** for:
- 📊 **Bar Chart** – Count of customers per segment  
- 📈 **Scatter Plot** – Recency vs. Total Spending  
- 🥧 **Pie Chart** – Segment proportions  

## Results & Insights
✔ **Big Spenders** contribute significantly to revenue but are rare.  
✔ **General Customers** make frequent purchases and drive steady sales.  
✔ **One-Time Buyers** need engagement strategies to become repeat customers.  
✔ **Lost Customers** require reactivation campaigns.  

## Future Improvements
🔹 Implementing **K-Means or DBSCAN** for automated segmentation  
🔹 Using **demographic data** for personalized insights  
🔹 Integrating **Power BI** for interactive dashboards  

## Conclusion
This project successfully segmented customers based on shopping behaviors, providing actionable insights to enhance business marketing strategies.

