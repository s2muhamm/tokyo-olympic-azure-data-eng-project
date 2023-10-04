# tokyo-olympic-azure-data-eng-project

Used Microsoft Azure to create an end-to-end project that analyzes the Tokyo Olympics data (pulled from Kaggle). 

Here is an overview of what i have built in this lab.
![image](https://github.com/s2muhamm/tokyo-olympic-azure-data-eng-project/assets/47164032/8501c83c-001a-4059-880c-96e198e38d37)


-Azure Data Factory to ingest raw data into Azure Data Lake Gen2. 
![image](https://github.com/s2muhamm/tokyo-olympic-azure-data-eng-project/assets/47164032/e8d43c13-c6f3-4151-a71c-5f145550d6ee)
![image](https://github.com/s2muhamm/tokyo-olympic-azure-data-eng-project/assets/47164032/afcdc8b2-8fbe-42d5-9ea1-6b91c9dd3bbf)


-Databricks to import the data from the storage container and then use Spark to transform the data and drop it in another storage container in Azure Data Lake Gen2. 
(Refer to the notebook)

-Synapse Analytics to write some SQL queries to test some use cases on the transformed data. 
![image](https://github.com/s2muhamm/tokyo-olympic-azure-data-eng-project/assets/47164032/e7dc0e7e-3f65-495b-8d80-2544f4fa4c8d)
