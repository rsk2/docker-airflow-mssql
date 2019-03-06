# docker-airflow
[![CircleCI](https://circleci.com/gh/puckel/docker-airflow/tree/master.svg?style=svg)](https://circleci.com/gh/puckel/docker-airflow/tree/master)
[![Docker Build Status](https://img.shields.io/docker/build/puckel/docker-airflow.svg)]()

[![Docker Hub](https://img.shields.io/badge/docker-ready-blue.svg)](https://hub.docker.com/r/puckel/docker-airflow/)
[![Docker Pulls](https://img.shields.io/docker/pulls/puckel/docker-airflow.svg)]()
[![Docker Stars](https://img.shields.io/docker/stars/puckel/docker-airflow.svg)]()

In this repository, I have modified the **Dockerfile** of [apache-airflow](https://github.com/apache/incubator-airflow) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/puckel/docker-airflow/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/). It is now ready to connect to Azure SQL Server as the metadata backend. 

NOTE: You do need to add an appropriate SQL Alchemy connection string on line 58 in the airflow.cfg file which is present in the config folder.

