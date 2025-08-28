# 🚀Exploratory Data Analysis Bootcamp Session (part 2) Report:
# 📌Test Case 2 (EDA2) :                    
Product Dataset (product based): The objective of this EDA is to study customer purchase trends and 
patterns using one month of sales data for selected top-selling products in a private retail company.

# 🗃️Datasets Used :
# EDA1 : 
1. 'train.csv' : having Customer purchase records including customer details, product categories and
   purchase amount
3. 'test.csv' : also having Customer purchase records including customer details, product categories
   except purchase amount

# ✅Main Steps :
1. Importing important libraries like numpy, pandas, matplotlib,
   seaborn etc
3. Importing the data i.e. 'train.csv' and 'test.csv'
4. Cleaning the data from duplicates, NULL values and  making sure
   data is in correct datatypes. Converted Product_Category_1 ,Product_Category_2 ,
   Product_Category_3 into categorical columns. Converted 'Gender' column to binary values
6. Data Visualization:
   
   Univariate Analysis & Bivariate Analysis :
   
     -> As all the given numerical columns -> 'User_ID', 'Gender', 'Occupation', 'Marital_Status'
        represent a category, hence statistical analysis cannot be completed on them.
   
     -> Count plots for Gender, Age, Occupation, City_Category, Marital_Status,
        Occupation by Gender, Stay_In_Current_City_Years by Gender, Stay_In_Current_City_Years
        by City

     -> Pie charts for City_Category and Marital_Status distributions
   
8. Insights & Observations :
   
   -> The number of male entries are significantly greater than female entries.
 
   -> Majority of the customers are in the prime working-age group (18–45 years), 
      specially 26–35 years, and least are between 0-17 years old
 
   -> Majority of the customers are from City_Category 1

   -> Majority of the customers are of marital status 0

   -> Gender 1 leads across all occupations, with the highest concentration in
      occupations 4, 7, and 0. Occupations 8, 9, 10, and 18 are negligible.

   -> Across all city categories (A, B, C), the 1-year stay dominates. City B
      attracts and retains the most people across all stay durations, especially at 1 year

# 🚩Challenges Faced:
   1) Missing values in 'Product_Category_2' and 'Product_Category_3' : resolved it by imputing
      both columns with a new category 21
      
   2) Several columns in the dataset (Product_Category_1, Product_Category_2, Product_Category_3,
      City_Category, Stay_In_Current_City_Years) were stored as object datatypes, even though they
      actually represent labels or groups rather than continuous values: resolved this by changing
      datatype to 'category' to reduce memory footprint and allow faster operations such as grouping,
      filtering, and encoding

# 📊Visualizations Included
   
   ->	Countplots (Gender, Age, Occupation, Stay Duration)
   -> Pie charts (City Category, Marital Status)

# 👥 Collaborators

   Special thanks to:

   • Chirag Jhumkawala
   • Pranav Jaipurkar	
   • Sandhya Hinduja
   • Shivani Tripathi

   for their guidance, support and contributions.
