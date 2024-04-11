# Amazon-Product-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/9fdfd694-7647-41bc-8b47-1f1061ec9176?ctid=7f3046c6-5b21-4b0b-ae7c-9e74c8b66d89&pbi_source=linkShare


**Power BI Dashboard: Amazon Product Analysis**

**Introduction:**
This Power BI dashboard provides a comprehensive analysis of Amazon product sales data for the year 2022. It offers valuable insights into product performance, sales trends, and customer behavior on the Amazon platform.

**Key Features:**
- Interactive visuals for exploring sales data by category, product, and month.
- Dynamic filters for refining the data based on user preferences.
- Drill-down capabilities for detailed analysis of specific product categories or time periods.

**Data Sources:**
The dashboard is powered by sales data sourced from Amazon's internal database. The data is extracted, transformed, and loaded into Power BI using a combination of SQL queries and ETL processes.

**User Interface:**
Users can interact with the dashboard by selecting different filters, clicking on visuals for detailed insights, and exploring various data points. The dashboard is designed to be intuitive and user-friendly, allowing users to quickly grasp key trends and patterns.

**Insights:**
- Top-selling product categories and their revenue contributions.
- Monthly sales trends and seasonality effects.
- Customer sentiment analysis based on product reviews and ratings.

**Usage Instructions:**
1. Open the dashboard in Power BI Desktop or Power BI Service.
2. Use the filters on the right-hand side to select specific categories, products, or time periods.
3. Click on visuals to drill down into more detailed information.
4. Hover over data points to view tooltips with additional context.

**Technical Details:**
- Developed using Power BI Desktop (version X.X.X).
- Custom visuals and DAX calculations implemented for enhanced analytics.
- Requires a Power BI Pro license for full interactivity and sharing capabilities.

Dashboard Calculations:

    Sale Icon On - SalesOn: Determines the URL for the sales icon based on the selected option.

    Units Icon On - SalesOn: Determines the URL for the units icon based on the selected option.

    Seller Count: Calculates the count of sellers, filtering out any orders with the "Delivered" status.

    Filter Sale: Calculates either the total sales amount or total units sold based on the selected option.

    Return Units: Calculates the number of units returned.

    Reviews: Counts the number of reviews for Amazon products.

    Sale Amount: Calculates the total sales amount.

    Sale Units: Calculates either the total sales amount or total units sold based on the selected option.

    Sale Option: Defines the options for selecting either sales or units.

    All Sale: Calculates the total sales or units sold for all product categories.

    Order Counts: Calculates the count of orders with the "Delivered" status.

**Feedback:**
I welcome your feedback on the dashboard! If you have any comments, suggestions, or questions, please feel free to reach out to me.
