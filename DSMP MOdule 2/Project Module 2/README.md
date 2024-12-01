# E-Commerce Sales Analysis Analysis
![sales](https://github.com/user-attachments/assets/0e47c958-5990-4a45-932a-5924711cafff)

This project is an in-depth analysis of e-commerce transactional data to extract meaningful insights using SQL and Pandas, and to visualize key metrics using Matplotlib and Seaborn. The findings and the entire workflow have been documented in this repository.

## Project Overview  
This project aims to:  
1. **Analyze sales data**: Using SQL to extract insights such as monthly revenue, top products, and customer behavior.  
2. **Data Cleaning and Exploration**: Leveraging Pandas to clean, explore, and prepare data for analysis.  
3. **Visualization**: Represent key insights through intuitive visualizations.  
4. **Version Control**: Use GitHub for collaboration and documentation.  

## Dataset  
The dataset includes four tables:  

1. **Orders**: Transaction details (Transaction ID, Order Date, Customer ID, Product ID, Quantity, Total Amount).  
2. **Products**: Product details (Product ID, Product Name, Category, Price).  
3. **Customers**: Customer details (Customer ID, Name, Region, Segment).  
4. **Sales**: Sales details (Order ID, Revenue, Discounts, Taxes).  

Dataset link: [E-commerce Dataset](https://github.com/dataseekho/sql-basics-beyond/tree/main/dataset)  

## Key Steps  

### 1. SQL Analysis  
- **Objective**: Store and analyze data using SQLite.  
- **Tasks Performed**:  
  - Created a relational database and loaded the dataset into tables.  
  - Performed the following SQL queries:  
    - Monthly sales revenue.  
    - Top 5 best-selling products.  
    - Revenue contribution by customer segments.  
    - Top regions for sales.  

- **Results Exported**: Query results were exported to CSV for further analysis.  

### 2. Data Cleaning and Exploration (Pandas)  
- **Objective**: Prepare data for analysis and exploration.  
- **Steps**:  
  - Handled missing values and duplicates.  
  - Conducted exploratory data analysis (EDA) on trends, behaviors, and product performance.  
  - Created new features like revenue per product and customer lifetime value.  

### 3. Data Visualization  
- **Objective**: Visualize insights using Matplotlib and Seaborn.  
- **Visualizations**:  
  - Line chart: Monthly sales revenue.  
  - Bar chart: Top 5 best-selling products.  
  - Bar chart: Revenue contribution by customer segments.  
  - Bar chart: Revenue contribution by regions.  

### 4. Version Control with GitHub  
- **Repository Structure**:  
  ├── data/
  │   ├── Orders_Large.csv
  │   ├── Products_Large.csv
  │   ├── Customers_Large.csv
  │   ├── Sales_Large.csv
  ├── sql/
  │   ├── queries.sql
  ├── notebooks/
  │   ├── analysis.ipynb
  ├── README.md
  ├── requirements.txt
  └── results/
      ├── revenue_by_month.csv
      ├── best_selling_product.csv
      ├── revenue_by_segment.csv
      ├── revenue_by_region.csv

- **Documentation Included**:  
  - **README.md**: Explanation of the project and results.  
  - **Requirements.txt**: Libraries and tools required.  

## Key Insights  

1. **Monthly Revenue**:  
   - Identified trends in monthly sales performance.  

2. **Top Products**:  
   - Determined top 5 best-selling products by revenue.  

3. **Customer Segments**:  
   - Analyzed revenue contribution from each segment.  

4. **Regional Performance**:  
   - Highlighted top-performing regions in terms of revenue.
     
## Technologies Used  
- **Database**: SQLite  
- **Data Analysis**: Pandas  
- **Visualization**: Matplotlib, Seaborn  
- **Version Control**: GitHub  

## How to Use  
1. Clone the repository.  
   ```bash
   git clone <repository-link>
   ```
2. Install the required libraries.  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the SQL scripts in the `sql/` directory.  
4. Explore the analysis and visualizations in the Jupyter notebooks (`notebooks/`).  

## Future Work  
- Incorporate advanced predictive modeling using machine learning.  
- Expand the dashboard to include real-time data visualization.  

## Acknowledgments  
- [Data Seekho](https://github.com/dataseekho/sql-basics-beyond) for the dataset.  
