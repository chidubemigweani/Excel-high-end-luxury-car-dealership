# Car Dealership Analysis

### Project Overview

This report aims to aid this dealership company using data driven insights to stock the right inventory, optimize pricing and improve customer satisfaction. As business is growing fast these questions are key to knowing which decisions to make to further improve sales and pricing.

### Data Source

Week 3 Data Challenge: The primary dataset used for this analysis was the "Week 3 Data Challenge.xlsx" containing detailed information about the company's sales

### Tools

- Excel - Data Cleaning & Transformation
- Excel - Data Analysis
- Excel - Visualization

### Data Cleaning/Preparation

In the initial data preparation phase, I performed the following tasks:
1. Data loading & Inspection
2. Handling missing values
3. Removing duplicates
4. Data cleaning and formatting

### Exploratory Data Analysis (EDA)

EDA involved exploring the data to answer key questions such as:
- Who is the most popular car manufacturer?
- What is the least popular car color?
- What is the average price by ownership category?
- Between automatic and manual cars, which type was sold more?
- Which manufacturing country is most represented?

### Data Analysis

I used Pivot tables to find the COUNT of the manufacturing comapany, color, prefered transmission. I also used Pivot tables to find the AVERAGE of the price by ownership category.
To find the most represented country, I used VLOOKUP to lookup the values from the "Manufacturing Company" sheet to find what company each car brand originates from. Then auto filled it to see the value for each row in the data set

```excel
=VLOOKUP([@[Manufacturing Company]],Table5[#All],2,FALSE)
```

### Results/Findings

The analysis results are summarized as follows:
1. BMW dominates the dealership company's sales
2. Red is the most popular car color
3. 80,152.5647 is the average price by ownership category
4. Manual transmission is most sold
5. Germany is most represented

### Recommendations

Based on the analysis, I recommend the following actions:
- Since there are more of BMW sales, less of BMW can be stocked in the dealership company’s inventory, the price too can be increased to draw the attention of customers to lesser bought cars
- The company can decide to deal in German cars only since thefy already have a good reputation in sales of German car products
- Customers prefer manual transmissions over automatic transmission, acquire and stock automatic cars only if they are high-demand models where it won’t be a drawback

### Limitations

I did not encounter any limitations from this dataset. There were no missing values

### References

None
