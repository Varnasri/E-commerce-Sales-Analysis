# E-commerce Sales Analysis

## Project Background
This project involves Toys story data analysis database, including information, product details, Revenue and order details. The aim is to gain insights into sales patterns and chart and interpretation behaviour.

## Objectives
Perform analyse sales data and answer various business questions.

Certainly, here's a summary of each analysis conducted in this project, along with the key findings and insights:

### Analysis 1:  Total units of toys sold (Q.1)

**Query Description**: This query calculates the Product (Categorical) and total Product count (Outcomes/frequency of the categorical) 

**Key Findings**:
- 8 Products of Toys available in their Stores (i.e: Action Figure, Colorbuds, Dart Gun, Deck Of Cards, Gamer Headphones, Lego Bricks, Nerf Gun, Rubik's Cube)

**Insights**:
- Identifying top-sold product can help the store to restock in market.
- Use Frequency Table (Bar Chart) or Pie chart to represent in percentage
   
### Analysis 2: Total units of toys sold by each store (Q.2)
Query Description: This query retrieves store orders where the total store product amount is higher than the average total amount of all other product store orders.

**Key Findings**:
- Orders of Deck Of Cards in store 1 have above-average total sales.

**Insights**:
- Focusing on high-value orders can inform targeted market store or upselling strategies. (Used Multiple Bar Diagram)
- If need to present the data in percentage use Stack subdivide bar diagram
   
### Analysis 3: Quarterly revenue generated between all the stores (Q.3)
Query Description: This analysis calculates the total Revenue and subtotal for each Stores per day.

**Key Findings**:
- Data of Toy store has starting from 2017 Qtr 1 to 2018 Qtr3 
- Store 3 has the highest total quantity sold and subtotal (Rs: 3,76,343)
- On 2017 Qtr 3 every stores falls on depression 

**Insights**:
- Understanding product performance over time is essential for inventory management and marketing decisions.
- Using Line chart is prefer whenever the time or periods comes to discussion `
 
### Analysis 4: Give me a range of how much revenue can be generated in a day (Q.4)
Query Description: This query categorizes orders as high, medium, or low based on predefined total amount ranges.

**Key Findings**:
- On a day the range of amount can be expected is between Several orders fall into the "High" and "Medium" categories, indicating substantial sales.
- On Average a day the store can earn between the range starting from Rs: 2,150 to Rs: 8,150 on the bases of past 300 days 

**Insights**:
- Categorizing intervals orders can help identify trends and segment customers for targeted promotions.
- Use Histogram chart (Bar chart without gap), it will divide automatically into class intervals 
- You can also find Average Revenue per day 
 
### Analysis 5: Check five number summary of daily revenue (Q.5)
Query Description: This analysis ranks sales based on the total number of orders they have processed 

**Key Findings**:
- Found outliers in toy stores dataset using Box plot visualization
- Identified the Mean, Median, Q1, Q3, IQR, Upper bound, lower bound, Max and Min limit of the dataset

**Insights**:
- Recognizing outlier performers by considering the outliers leads consider might active special offers might gone to boost sales.
 
### Analysis 6: Find the relationship between no. of units placed on a daily basis and the revenue generated (Q.6)
Query Description: This query lists products units, date and revenue per day across all products.

**Key Findings**:
- Products trends to move forward with dependence to each other in positive direction.

**Insights**:
- The more units it sales the more revenue it will generate.
- Identifying the business moves in positive direction can guide inventory and marketing efforts.
 
### Analysis 7: Identify highest selling products that generated maximum revenue (Q.7)
Query Description: This analysis calculates the total quantity sold price for each product category.

**Key Findings**:
- Provides a linkage between revenue, product, and cumulative revenue tracking.
- Using Pareto Principle by selling Lego Bricks, Colour Buds, Rubik’s Cube and Action Figure we can generate 80% revenue then selling less profitable products (Revenue should be in Largest to Smallest order)
- 80% of the outcomes come from 20% of the actions.

**Insights**:
- Understanding the customer-buying products can be valuable for customer satisfaction.
- Knowing category performance can inform pricing and marketing strategies.
