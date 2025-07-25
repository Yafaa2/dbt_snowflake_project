
# End-to-End Data Engineering Project: dbt, Snowflake & Apache Airflow
![](/screenshots/system_diagram.png)

## Overview
This is simple data pipleine using dbt, Snowflake, and Apache Airflow using docker. Loading CSV files into snowflake then trasnforming it using dbt scheduled by Airflow .

### Tech Stack
- dbt Core – For data transformation and modeling
- Snowflake – Cloud-based data warehouse
- Apache Airflow – Workflow automation and orchestration
- Python – Scripting and automation
- Git – Version control

### Setup
#### Clone repo:
```
git clone https://github.com/Yafaa2/dbt_snowflake_project.git
cd your-repo-name
```

#### Set Up a Virtual Environment:
```
python -m venv venv
venv\Scripts\activate
```
#### Run dbt models:
```
dbt run
dbt test 
```

#### Start Apache Airflow:
```
cd \snowflake_data_project
docker-compose up --build
```

## Data lineage

![](screenshots/data_lineage.png)

## Airflow Graph

![](screenshots/airflow_graph.png)

## SnowFlake

![](screenshots/snowflake.png)