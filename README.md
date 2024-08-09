# Customer Segmentation Using RFM Analysis

## Project Overview
This project conducts a comprehensive RFM (Recency, Frequency, Monetary) analysis on customer transaction data to enhance marketing strategies and improve customer engagement. The analysis is performed using Python, NumPy, and Pandas in Google Colab, utilizing transaction and customer data sourced from an Excel file.

## Data Sources
- **Transactions Dataset:** Contains transaction details, including order IDs, product IDs, sales amounts, quantities, discounts, and profit amounts.
- **Customers Orders Returns Dataset:** Includes customer information such as IDs, names, segments, and order details.

## Key Analysis Tasks
- **Average Basket Size:** Calculated by dividing the total quantity of products sold by the number of orders for each customer.
- **Average Basket Value:** Determined by dividing the total sales value by the number of orders for each customer.
- **Length of Stay:** Calculated as the difference between the maximum and minimum order purchase dates for each customer.

## Data Cleaning and Preparation
- Handled duplicate entries and missing values to ensure data integrity and consistency.
- Filtered for delivered orders to focus the analysis on completed transactions.

## Challenges Faced
- **Handling Date Formats:** Standardizing different date formats across datasets for accurate calculations.
- **Calculating Length of Stay:** Identifying the earliest and latest purchase dates while converting string dates to datetime objects.
- **Dealing with Missing Dates:** Implementing logic to manage incomplete transaction histories without skewing the analysis.

## Importance of Filtering for Delivered Orders
- **Relevance to Analysis:** Focuses on completed transactions to avoid skewing customer behavior metrics.
- **Accurate Metrics:** Ensures metrics reflect only successful transactions, preventing inflation or misrepresentation.
- **Focus on Customer Experience:** Enhances understanding of customer satisfaction and engagement related to successful orders.

## Technologies Used
- Python
- Pandas
- NumPy
- Google Colab

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Gajendra-Saini/Customer-RFM-Analysis.git
   ```
2. Install the required packages:
   ```bash
   pip install pandas numpy
   ```
3. Run the Jupyter notebook or Python script to view the analysis results.

---

Feel free to adjust any details or formatting as needed!
