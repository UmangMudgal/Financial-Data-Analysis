# Financial-Data-Analysis

# Tools Used:
1. Excel : As a data cleaning and manipulation tool.
2. AWS  : As a Data Source Provided by the Client.
3. Snowflake : Datawarehouse used to perform the need full data transformation based on clients requirements, and data cleaning as necessary.
4. Power BI : Providing Insights to the stakeholders.

# Data Ingestion 
1. AWS 
     1. Create S3 Bucket : Data Source
     2. Create Role : For the authentication purpose during connection with the snowflake.
     3. Create Policy : To provide the necessary permissions.
     4. Attach Policy to Role.
2. Snowflake
     1. Table Creation
        1. Create Table Command
        2. Primary Key and Foregin Key Concept
     3. File Format Creation : CSV FILE/ Other file
     4. Create Storage Integration
          1. Role ARN
          2. Bucket URL
     5. Create Stage
          1. Bucket URL
          2. File Fomat
     6. Create Pipe : Provide SQS ARN to S3 Bucket Event Notification
   
# Data Transformation
1. Year Updation
   1. Use of Update Command
2. Age Column Creation
   1. Use of Alter Command
   2. Use of Update Along with Sub-Query.
3. Checking Null Values
    1. Use of IS NULL Value
4. Null Value Treatement as per Requirements
   1. USe of Update
5. For other exploration Task
   1. Group By
   2. Having Clause
   3. Case When Statement
# Ad-Hoc Analysis
1. Demographic Variation in the data

# KPI Creation
# Dashboard Creation
