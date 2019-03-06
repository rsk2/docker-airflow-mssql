# docker-airflow

In this repository, I have modified the **Dockerfile** of [apache-airflow](https://github.com/apache/incubator-airflow) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/puckel/docker-airflow/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/). It is now ready to connect to Azure SQL Server as the metadata backend. 

NOTE: You do need to add an appropriate SQL Alchemy connection string on line 58 in the airflow.cfg file which is present in the config folder.

