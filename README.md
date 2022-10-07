# School_District_Analysis
## Module 4 Challenge
 
### Overview of Project: Maria, the cheif data scientist for a school district, needs an analysis on student funding and standardized tests scores to help make informed and strategic decisions for each school. 

 - Software: Python 3.7.6   ~ Jupyter Lab  
 - Resource: 'new_student_data.csv'


#### Deliverables for this Project
  - Collect student data into a DataFrame: Creating path and properly importing data using code 'pd.read_csv()" 
  - Prepare a cleaned version of the DataFrame: Checking and dropping Null values with 'student_df = student_df.dropna()'
  - Summarize key pieces of the data: Using describe method 'student_df.describe()' as well as mean functions to display
  - Drill down into the data to analyze specific subsets: Using loc and iloc including with conditionals to display data 'student_df.loc[:, "grade"]' 
  - Compare and contrast the data through grouping and aggregation functions: Using Groupby, count and mean compare Charter and Public schools 'student_score_group_df =     student_df.groupby(by= "school_type").mean()'


### Conclusion
Using Pandas and all its functions there are many more possiblilty for visualizing the data contained in this file, helping Maria make an informed decisions.


  

