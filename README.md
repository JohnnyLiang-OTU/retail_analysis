# Retail Data Analysis
Dataset source: https://www.kaggle.com/datasets/sahilprajapati143/retail-analysis-large-dataset?resource=download

Dataset that contains transactions. <br>
The columns include: age, gender, income, customer segment, totla purchases, amount spent, product category, product brand, product type, shipping method, payment method, and others.

## Objectives to Explore:

1. Customer Level
- Of the customers, which gender dominates the different income categories. ✅
- Age Distribution. ✅
- Age Average. ✅
- Consumption per gender. ✅
- Consumption per gender average. ✅
- Consumption per income category. ✅
- Consumption per income category average. ✅
- Consumption per income category and gender (AKA. Which Gender consumes the most within their Income Category. It answers wheter rich women / men spend most). ✅
- Consumption per income category and gender average. ✅


2. Country Level
- Which country consumes the most on average. ✅
- Which country consumed the most. ✅
- Greatest country consumer  in 2023 by month. ✅
- Why is there such strange results in February regarding monthly consumption?

3. Product Level
- ProductCategory purchase distribution (How much times product category was bought) ✅
- ProductCategory purchases by Gender ✅
- ProductCategory gross sales (How much money worth by product category) ✅
- Brand gross sales ✅
- Brands sales count by Gender ✅
- Clientele Distribution among Companies by Gender ✅
- Gender Ratio per Brand ✅

4. Prediction and Inferences
- Machine Learning Model

## Results
### 1. Customer Related
#### - Of the customers, which gender dominates the different income categories.
![image](images/1a_gender_distribution_income.png)<br>
There are more females in the Low and Medium income category than males.
And there are more males in the High income category than females.
#### - Age Distribution. 
![image](images/1b_age_distribution.png)
A lot of retail customers in their early 20s and some interesting high counts for customers of age 34, 46, and 55.
#### - Age Average. 
The average age of the customers in the retail dataset is 35.
#### - Consumption per gender. 
![image](images/1d_consumption_per_gender.png)<br>
Men clients purchased a total of $249,891,824.48. <br>
Women clients purchased a total of 152,086,424.42
#### - Consumption per gender average. 
![image](images/1e_average_consumption_per_gender.png)<br>
On average, women and men purchased an average 1368.34 and 1367.29, respectively. This are very similar values, meaning, men and women have similar both contribute equally economically in a retail context.
#### - Consumption per income category. 
![image](images/1f_consumption_by_income_cat.png)
#### - Consumption per income category average. 
![image](images/1g_consumption_per_income_category_avg.png)
#### - Consumption per income category and gender (Which category consumed most)
![image](images/1h_total_consumption_gender_incomecategory.png)
#### - Consumption per income category and gender average. 
![image](images/1i_avg_consumption_gender_incomecategory.png)

### 2. Country Level
#### - Which country consumes the most on average. 
![image](images/2a_country_average_consumption.png)
On average, a customer from the UK will consume the most.
#### - Which country consumed the most. 
![image](images/2b_country_total_consumption.png)
In total, the country that spends the most is the USA.
#### - Greatest country consumer  in 2023 by month. 
![image](images/2c_max_monthly_spending.png)
Usually, the USA spends the most each month, but surprisingly, on February there was a huge dip and Australia leaded consumption despite the low value it displays.
#### - Why is there such strange results in February regarding monthly consumption?
![image](images/2d_why_of_the_february_dip.png)
The reason why there is such a dip in February regarding monthly consumptions is because in the dataset, in February 2023, there is few transactions. <br>
The number of transactions was low for every country and Australia happened to have more than any other country, hence why such low consumption and Australia being the greatest consumer in that month and year.

### 3. Product Level
#### - ProductCategory purchase distribution (How much times product category was bought) 
![image](images/3a_purchase_category.png)
Electronics and Groceries were the most bought categories.
#### - ProductCategory gross sales (How much money worth by product category) 
![image](images/3b_sales_category.png)
#### - ProductCategory purchases by Gender 
![image](images/3c_category_gender_distribution_purchases.png)
#### - Brand gross sales 
![image](images/3d_sales_per_brand.png)
#### - Brand sales count by Gender
![image](images/3e_purchase_count_distribution_by_gender.png)
#### - Cliente Distribution among Companies by Gender
Percentage of men and women that purchase for that specific brand.
![image](images/3f_clientele_distribution_companies_gender.png)<br>
#### - Gender Ratio per Brand
![image](images/3g_gender_ratio_brand.png)
How many transactions come from men and how many come from women per brand.

### 4. Predictions and Inferences
# WORK IN PROGRESS! - Dec 29