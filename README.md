<img width="1182" height="660" alt="Image" src="https://github.com/user-attachments/assets/5a091d3a-12dc-4ddc-a131-3f7c33761c9c" />

# 🌍 Global Inflation and Cost of Living Analysis
## 📌 Introduction
The Global Inflation and Cost of Living Analysis project explores inflation rates and cost-of-living patterns across countries and regions.

## Business Questions
1.What is the overall trend of inflation across countries overtime?

2.Which countries have the highest and lowest inflation rates?

3.What is the relationship between inflation and cost of living?

4.Which countries have experienced the greatest increase in cost of living?

5.How does Nigeria compare with other selected countries in terms of inflation and cost of living?

6.How does inflation and cost of living vary by region?

## Analysis and Findings
### Question 1. What is the overall trend of inflation across countries overtime
Method: Cleaned Dataset, Pivot Table Analysis and Line Chart

Findings: The analysis indicates that inflation is a global but uneven phenomemon, the overall trend indicates significant variation in inflation rates across countries which suggests that the impact of inflation on the cost of living differs substantially across countries.												

### Question 2. Which countries have the highest and lowest inflation rates
Method:      Cleaned Dataset, Pivot Table Analysis and Column Chart

Findings:   The countries with the highest inflation are likely to face greater cost of living pressures, particular for essential items as food, housing, transportation and energy while countries with lower inflation generally have price stability, although a low inflation rate does not necessarily mean that the country has a low cost of living - it only mean that prices are increasing slowly. 	

 ### Question 3.What is the relationship between inflation and cost of living
 Method:   Cleaned Dataset, Correlation Analysis and Scatter Plot Chart
 
Findings:  The correlation analysis produced a pearson correlation coefficient of -0.3212, indicating a weak negative relationship between inflation rate and cost of living.Inflation and cost of living are related, but the relationship is not necessarily positive or strong across countries. Therefore a country with high inflation does  not automatically have the highest cost.

####  Correlation Matrix		

<img width="1433" height="499" alt="image" src="https://github.com/user-attachments/assets/332a015f-997a-4690-a02d-9dd1a9758867" />

 ### Question 4. Which countries have experienced the greatest increase in cost of living
  Method:   Cleaned Dataset, Pivot Analysis and Column Chart
 
Findings:   The countries with the highest cost of living increases in the dataset indicate the greatest deterioration in purchasing power and the strongest pressure on household budgets.

### Question 5.How does Nigeria compare with other selected countries in terms of inflation and cost of living?
 Method:   Cleaned Dataset, Pivot Analysis and Column Chart
 
Findings:  The comparison indicates that Nigeria faces a much stronger inflationary challenge than the selected countries. This can contribute to higher living costs, reduced real income,and increased difficulty for households to maintain their standard of living.

<img width="455" height="238" alt="image" src="https://github.com/user-attachments/assets/176910a1-0c97-4410-a941-92fc6db5dccf" />

### Question 6.How does inflation and cost of living vary by region
Method: Cleaned Dataset, Pivot Table Analysis and Combo Chart

Findings:      The analysis shows that inflation and cost of living vary across regions. Some regions record relatively high average inflation but do not necessarily have the highest cost of living index e.g. Sub - saharan Africa has 15.54% inflation rate with average cost of living index of 45.5% .  This indicates that a high current inflation does not automatically mean that a region has the highest overall cost of living.  Regional differences may be influenced by factors such as housing costs, food prices,  transportation costs, purchasing power and other  economic condition. 																			
## Analysis of Steps
### Cleaning of Dataset using Power Query
Go to Data > Table Range

Confirm my table has headers

Click 'OK to open Power Query Editor

#### To remove unnecessary columns
Identify columns not needed 'n select the column

Right click 'n remove columns

#### To Remove duplicate records
Select columns that identify a unique record, such  as Country + Year

Go to Home 'n Remove Rows 'n Remove Duplicates

#### To clean text columns
Select the column 

Go to Transform 'n Format 'n Trim

Select Transform 'n Format 'n Trim

#### To check errors
Go to Home 'n Remove Rows 'n Remove Errors

### Creating Pivot Table
Go to Data > 'Insert' on excel ribbon

Click pivot table 'n choose from table/range

Select New Worksheet 'n click Ok

### Performing Pivot Analysis
Go to pivot table > pivot table field

 Drag the variables for Rows 'n column 'n filer 'value
 
 Sort from pivot table to analyse the variables
 
### Performing Correlation Analysis
Go to 'Data' > 'Data Analysis'

Select 'Correlation'

Input the ranges for dependent and independent variables

Check the label if included and choose the output range

Click 'OK' to get the results

### Creating Charts and Scatter Plot
 Click inside the pivot table
 
 Go to insert 'n pivot chart
 
 Choose an appropriate chart
 
 Click 'OK'

