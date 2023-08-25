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
     1. File Format Creation : CSV FILE/ Other file
     2. Create Storage Integration
          1. Role ARN
          2. Bucket URL
     3. Create Stage
          1. Bucket URL
          2. File Fomat
     4. Create Pipe : Provide SQS ARN to S3 Bucket Event Notification
# Data Transformation
# Ad-Hoc Analysis
# KPI Creation
# Dashboard Creation
