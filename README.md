# Airlines-pipeline

Question 1 & 2 :

1) Data Cleaning -> airports_cleaned_dataset.csv.
   
   Data Cleaning 
     - Rename columns
     - Drop Columns
     - Change Data Types for DB storage purpose

2) Set up the Azure Services -> Azure Data Factory as the main gate, with Azure Blob Container & Azure SQL Database.

![Piepline](/Images/AzurePipeline.png | width=100)

   Azure Blob Storage
     - Container - 'input'
     - Blob (airports_cleaned_dataset.csv)
   
   Azure SQL Database
     - Create dbo.airports table
     - With this command -> db-create.sql
   
   Azure Data Factory
     - Create two linked services
     - Create two datasets
     - Use Copy Data feature -> 'Blob to SQL' 
     
Question 3 :

For Question 3, used the Havenise Function to calculate the distance between Malaysian airports based on the 
airports_cleaned_dataset.csv.

    - Add another column that shows the coordination based on latitude and longitude





