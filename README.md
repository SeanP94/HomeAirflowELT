This project is an airflow ELT pipeline that I am developing for my home network.

The purpose of this project, and the solution I am solving is that I love working with data, and I would prefer to work with realtime data I am familiar with and collected.
  For most data projects, users just use preconfigured datasets, and I would like to avoid doing that if at all possible 


--- 
Some Notes:

- Before you run Airflow, please configure your image and volume like this link:
   https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html

- I added a port 5436 forward to my local machine so that I can access the Airflow database in PGadmin.