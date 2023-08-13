# dataform-practice
This repository contains sample code to work with Dataform to transform and load the Data into BigQuery. We use a combination of SQLX and Javascript to transform the data and run data quality tests on top of it.

# Install Dataform 
npm i -g @dataform/cli@^2.3.2

# Dataform Setup
dataform init bigquery --default-database project_id --default-location project_location