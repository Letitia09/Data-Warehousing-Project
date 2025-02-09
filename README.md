# Data-Warehousing-Project
<pre>
<b>Data Warehousing Project : Real Estate Sales - Demo</b> 
In this project, I utilized a sample dataset of real estate sales and employed dimensional modeling using Vertabelo.  
  1) Setting Up the Environment: 
      Created an S3 bucket and an IAM user with the necessary permissions. 
      Mounted the S3 bucket in Databricks and organized it for the medallion architecture.
  2) Data Preparation: 
      Established a database and created an external bronze CSV table. 
      Transformed the data into a bronze Delta table and performed initial data cleaning. 
  3) Data Cleaning and Transformation: 
      Split and renamed columns, converted data types, and standardized formats. 
      Created a cleaned DataFrame and saved it as a Delta table in the silver layer. 
  4) Dimensional and Fact Tables: 
      Divided the silver Delta table into two parts and created eight dimension tables and three fact tables using first part of the silver table. 
      Conducted unit testing to ensure data integrity. 
  5) Merging dimensions and facts:
      With the second part of the silver Delta table,  the merging of dimensions and fact tables is done by creating views and merged accordingly.
      After merging, I displayed the updated dimensions and fact tables. Conducted unit testing on gold table to ensure data integrity.
  6) Analysis Phase: 
      Analyzed total revenue generated by different types of residential properties. 
      Examined proportions of total revenue by property type. Analyzed annual sales revenue by residential type over the years.
</pre>
