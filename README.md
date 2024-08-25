# Adventure Works Analytics

## Overview
The Adventure Works Analytics project is a comprehensive analysis of sales data using a multi-step process involving Python, PostgreSQL, and Power BI. The project aims to uncover key insights into sales trends, customer behavior, and product performance.

## Project Workflow
1. **Data Analysis with Python**:
   - **Data Cleaning & Transformation**: Using Python libraries like `pandas`, `numpy`, and `matplotlib`, the raw sales, product, and customer data were cleaned, transformed, and explored.
   - **Exploratory Data Analysis (EDA)**: Key metrics were visualized to understand sales patterns, identify high-performing products, and segment customers.

2. **Database Management with PostgreSQL**:
   - **Data Storage**: Cleaned data was stored in a PostgreSQL database for efficient querying and further analysis.
   - **Advanced Queries**: SQL was used to extract deeper insights, such as regional sales performance and customer demographics.

3. **Visualization with Power BI**:
   - **Interactive Dashboards**: Power BI was utilized to create dynamic visualizations, allowing stakeholders to explore the data interactively.

## Key Steps in the Analysis

### Data Cleaning & Transformation
The raw data was first imported into Python and underwent several cleaning and transformation steps:

- **Merging Data**: Sales data from 2020 to 2022 was consolidated into a single dataset.
- **Date Handling**: Date columns were converted to datetime formats to facilitate time series analysis.
- **Product Data Enhancement**: New columns, such as `SKUType`, were created for better categorization.

![Data Transformation](https://github.com/Anandhuvimalan/AdventureWorks-Analytics-with-Python-PostgreSQL-and-Power-BI/blob/main/images/data_transformation.png)

### Exploratory Data Analysis (EDA)
Key aspects of the sales data were explored using Python, revealing important trends and insights:

- **Sales Trends**: Analyzed sales trends over time to identify peak periods.
- **Product Performance**: Identified top-performing products and categories.
- **Customer Segmentation**: Grouped customers based on demographics and purchasing behavior.

![Sales Trends](https://github.com/Anandhuvimalan/AdventureWorks-Analytics-with-Python-PostgreSQL-and-Power-BI/blob/main/images/sales_trends.png)

### Database Integration with PostgreSQL
The cleaned and processed data was then stored in a PostgreSQL database:

- **Table Creation**: Tables were created to store sales, product, and customer data.
- **SQL Queries**: Advanced SQL queries were used to extract and analyze data directly from the database.

### Visualization with Power BI
The final step involved creating interactive dashboards in Power BI:

- **Sales Performance Dashboards**: Visualized sales data, allowing for dynamic exploration of trends.
- **Customer Insights**: Dashboards that provide a deeper understanding of customer behavior.

![Power BI Dashboard](https://github.com/Anandhuvimalan/AdventureWorks-Analytics-with-Python-PostgreSQL-and-Power-BI/blob/main/images/powerbi_dashboard.png)

## How to Reproduce the Analysis
### Prerequisites
- **Python 3.x** with libraries: `pandas`, `numpy`, `matplotlib`
- **PostgreSQL** for database management
- **Power BI** for visualization

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Anandhuvimalan/AdventureWorks-Analytics-with-Python-PostgreSQL-and-Power-BI.git
   ```
2. **Install Required Python Packages**:
   ```bash
   pip install pandas numpy matplotlib
   ```
3. **Run the Jupyter Notebook**:
   Execute the `AdventureWorks.ipynb` to perform data analysis and transformation.

4. **Load Data into PostgreSQL**:
   - Use the provided SQL scripts to create tables and load data.
   - Execute queries to replicate the analysis.

5. **Visualize with Power BI**:
   - Open the Power BI dashboard file and connect it to your PostgreSQL database.

## Results and Insights
Through this analysis, several key insights were discovered:
- **Seasonal Sales Trends**: Certain times of the year show a significant spike in sales.
- **Product Success**: Identified which products drive the most revenue.
- **Customer Demographics**: Segmentation revealed key customer groups that contribute to sales growth.

## Conclusion
This project showcases the integration of Python, PostgreSQL, and Power BI to conduct a thorough data analysis. It highlights the power of combining programming, databases, and visualization tools to extract valuable business insights.