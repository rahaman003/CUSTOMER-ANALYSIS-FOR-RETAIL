Business Context

The retail industry is becoming highly competitive, and companies must rely on data-driven decision making to retain customers and improve profitability. Customer data not only reflects current performance but also provides opportunities to forecast trends, optimize product placement, and improve marketing strategies.
For this case, the retail store wants to analyse day-to-day transactions, customer demographics, and product sales/returns across multiple categories and locations. The insights will help the business to:

•	Track customer behaviour and preferences (spending, frequency, demographics).

•	Understand product category performance and gender-based buying patterns.

•	Identify store performance in terms of value and volume.

•	Measure the impact of age, location, and store type on sales.

•	Support strategic decisions like promotions, product focus, and inventory planning.

________________________________________

Available Data

The dataset is provided in Retail Data.xlsx, which has three sheets:

1.	Customer – Customer demographics and attributes
   
	Customer ID, Gender, Age, City Code, Date of Registration, Store Type, etc.

2.	Transaction – Detailed transaction records
   
  Transaction ID, Customer ID, Date of Transaction, Product ID, Quantity, Amount, etc.
  
3.	Product Hierarchy – Product categorization
   
	Product ID, Category, Sub-Category, Department, etc.

After merging, the consolidated dataset (Customer_Final) links customer details with their transactions and purchased product categories.

________________________________________

Expectations

The analysis and reporting are expected to deliver:

1.	Data Preparation & Profiling
	
	Merge datasets into a single master table (Customer_Final).

	Provide summary statistics (column names, data types, five-number summary, top/bottom observations).

	Generate frequency distributions for categorical variables.

2.	Exploratory Data Analysis (EDA)
   
	Histograms for continuous variables, bar plots for categorical distributions.

	Time coverage of available transaction data.

	Identify negative transactions and clean accordingly.

3.	Customer Insights
   
	Popular product categories across male vs. female customers.

	City codes with maximum customers and their share.

	Customer segmentation by transaction frequency (e.g., >10 unique purchases).

	Spending analysis for customers aged 25–35, including category and time-bound spend.

4.	Store & Product Insights
   
	Store type contributing maximum sales (by value and quantity).

	Revenue contribution from Electronics and Clothing categories in Flagship stores.

	Revenue from male customers in Electronics.

5.	Business Value
   
	Helps retailers identify profitable customers and categories.

	Optimizes marketing strategies for gender/age/location-based targeting.

	Improves inventory and store-level planning.

	Provides a foundation for predictive analytics in retail.

