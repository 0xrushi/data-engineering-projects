## ETL Assignment

Make sure you have docker and docker compose installed.

Then run,

```sh
docker-compose up
```

Login into airflow: http://localhost:8080/admin with credentials

**username**: airflow
**password**: airflow

Then set the connections as shown in the image.

![image](/images/connections.png)

## Output

#### 1) Grid View of Dags

![image](/images/grid.png)

#### 2) Graph View of Dags

![image](/images/graph.png)

#### 3) Output Result in database

![image](/images/sqldata.png)

#### 4) Xcom variables during execution

![image](images/xcom%20variables%20in%20databse.png)
____

Q1) 