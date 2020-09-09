# NYC Yellow Taxi Rides
This is a Data Science project with the goal of discovering interesting insights
in the taxi trips record data provided by the NYC's TLC (Taxi & Limousine Commision).

## Report
The overall report of the project is under the Jupyter Notebook file which covers
all the steps in the process including the insights found.

## Technologies
This is a list of the tools used in the development of the process

|**Technology**|**Purpose**|
|---|---|
|Docker|Environment Setup|
|PySpark|Data Processing|
|Jupyter Notebooks|Reporting|

## Run it yourself
If you want to run the project yourself, you can simply
```docker-compose up```
to setup the container cluster composing of the spark cluster
and the jupyterLab container.

Then you can access the jupyterlab instance at *localhost:8888*.
In Jupyter you can upload the .ipynb file and run the entire notebook.
The data will be acquired using the notebook.

## Acknowledgements & Refrences
* The docker-compose.yml file responsible for setting up the environment is
an adaptation of the one provided [here](https://github.com/cluster-apps-on-docker/spark-standalone-cluster-on-docker).
* The data and its documentation were provided by [TLC](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page).