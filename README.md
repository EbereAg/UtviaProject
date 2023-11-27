# Market Basket Analysis
Market Basket Analysis is a powerful data science tool that is used by retailers and businesses to uncover associations 
and relationships between items purchased together by customers to directly benefit businesses.

Ever observed how some items are in close proximity in the grocery store, for example items like pasta and pasta sauce 
or bread and jam. 
This method reveals hidden correlations, using statistical rules to detect frequently occurring product combinations
in transactions, uncovering associations that might not be seen by the human eye.


# Objectives
The goal of this project is to perform market basket ana;ysis to uncover patterns in customer purchasing behavior. By 
identifying which products tend to be bought together, the company can make informed decision s to improve sales 
and customers satisfaction.

# Data Preparation
checked for null values
Changed my date to date-time-format
Set the 'Date' column as the index to simplify plotting trends overtime.

# Data Eploration
Generated summary statistics to gain foundational understanding of data.
Created visual representations.

# Analysis
Utilized Apriori Algorithm to identify frequent itemsets and generates association rules based on the concept of support, confidence, and lift.

# Insights
There are 38,765 rows and 3 columns recorded.
We have the top 10 most frequently sold items, whole milk, other vegetables, rolls/buns, soda, yoghurt, root vegetables,
tropical fruit, bottled water, sausage and citrus fruit. With whole milk leading with the sum of 2502 while citrus fruit
had the least with only 812 orders made.
There was a major sale in 2015, August to be precise with over 1900 purchase, while for 2014, the month of May had the most with 1600 purchase.

This result shows that the products that are tend to be bought together are:

Berries and Pork
Oil and Pork
Citrus fruit and Specialty chocolate
Long life bakery product and Meat
Oil and Sausage
Bottled beer and Other vegetables
Meat and Other vegetables
Bottled beer and Root vegetables
Berries and Soda


