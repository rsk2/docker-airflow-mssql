# docker-airflow

In this repository, I have modified the source code of  [Puckel's airflow docker](https://github.com/puckel/docker-airflow). It is now ready to connect to Azure SQL Server as the metadata backend. 

NOTE: You do need to add an appropriate SQL Alchemy connection string on line 58 in the airflow.cfg file which is present in the config folder.
 
Tested: Built and ran this on my local machine using [Docker for windows](https://docs.docker.com/docker-for-windows/install/)

Commands (would be the same as mentioned in the readme file here https://github.com/puckel/docker-airflow):
1. Build
    
    docker build -t mssql-airflow .
    
 2. Run 
 
     docker run -d -p 8080:8080 mssql-airflow webserver


