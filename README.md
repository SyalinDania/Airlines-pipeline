# Airlines-pipeline

Using Azure Data Factory as my ETL service in this case study (Q1 & Q2)

1) I clean the data from the link on a Jupyter Notebook using Python -> airports_cleaned_dataset.csv.
   
   Data Cleaning 
     - Rename columns
     - Drop Columns
     - Change Data Types for DB storage purpose

3) I set up the Azure Services (ETL pipeline) -> Azure Data Factory as the main gate, with Azure Blob Container & Azure SQL Database.
4) In the blob container, I insert the clean dataset.
5) I create table in Azure SQL Database as per screenshot.
6) In Azure Data Factory, I copy data from a blob container to SQL datbase through a Copy-Data pipeline.

For Question 3, I used the Havenise Function to calculate the distance between Malaysian airports based on the 
airports_cleaned_dataset.csv.





