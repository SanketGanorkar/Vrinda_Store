<div align="center">
  <h1>Vrinda Store Analysis</h1>
</div>

# Objective :- 
Vrinda store wants to create an annual sales report for 2023. So that , they can understand their customersand grow more sales in 2024.

# About this project :-
This project showcases a data visualization dashboard created using Microsoft Excel. 
The dashboard analyzes a dataset containing information about orders, including:

1) Order ID
2) Customer ID
3) Gender
4) Age
5) Date
6) Month
7) Status
8) Channel
9) SKU
10) Category
11) Size
12) Quantity
13) Currency
14) Amount
15) Shipping Details (City, State, Postal Code, Country)
16) B2B Flag 

# Key Features:

1) Visually Appealing Dashboards: The dashboard utilizes various charts and graphs to present data in an easy-to-understand and visually engaging format. This allows for quick identification of trends and patterns.
2) Data Insights: By leveraging pivot tables and filters, the dashboard provides insightful visualizations that can be used to analyze:
    1) Order trends over time
    2) Customer demographics (age, gender)
    3) Performance by channel (online, store)
    4) Popular product categories and SKUs
    5) Geographical trends (top selling states/countries)
    6) Order fulfillment status (completed, pending, cancelled)

# User Interaction:
The dashboard may include interactive elements like filters that allow users to explore specific data subsets. This functionality empowers users to focus on areas of particular interest, facilitating deeper analysis.

# Work done :-
- Data cleaning , data processing , data analysis , data visualization and gathering insights.
- Issue in Gender column - 4 categories ( Male , Female , M , F )
- Issue in Size column - ( 1 , 2 , 3 , 4 , 5 , One , Two )
- Created a new column ( Age group , for categorizing the age groups )
- Formula used for the above column - IF( E2 >= 50 , "Senior" , IF(E2 >= 30 , "Adult" , "Teenager") )
- Formula used for extracting the month from date - TEXT( (G2), mmm)
- In the pivot table we were having large values , so to increase the readability , we convert it into millions ( M ).
  (0.00 ,, "M") [ 0.00 , for getting the value upto 2 decimal places ]
# My Skills:
This project demonstrates my proficiency in:
  1) Microsoft Excel: Utilizing advanced features like pivot tables, charts, and filters to create impactful data visualizations.
  2) Data Presentation: Communicating complex information through clear and visually engaging dashboards.

# Sample Insights :-
- Women are more likely to buy compared to men ( ~ 65% )
- Maharashtra , Karnataka & Uttar Pradesh are the top 3 states ( ~ 35% )
- Adult age group ( 30 - 49 years ) is maximum contributing ( ~ 50% )
- Amazon , Flipkart & Myntra channels are maximum contributing ( ~ 80% )

# Final Conclusion to improve store sales :-
 Target women customers of agr group ( 30 - 49 years ) living in Maharashtra , Karnataka & Uttar Pradesh by showing advertisements/offers/coupons available on Amazon , Flipkart & Myntra.
![Project outcome ](https://github.com/SanketGanorkar/Vrinda_Store/blob/main/Vrinda%20sales.png)
