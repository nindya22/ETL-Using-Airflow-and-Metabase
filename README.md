# Data Transformation for Business Success : Building an efficient Data Infrastructure in a US Retail Company
## Task Detail
![task_detail](https://github.com/nindya22/ETL-Using-Airflow-and-Metabase/assets/139938347/b102f035-7b3a-402d-bfba-eaddc0b1eecd)
---
## How To Run
- Extract dibimbing_km_final_project-main
- In order to spin up the containers, first you have to build all the Docker images needed using 
    ```sh
    make build
    ```
- Once all the images have been build up, you can try to spin up the containers using
    ```sh
    make spinup
    ```
- Once all the containers ready, you can try to
    - Access the Airflow on port `8081`
    - Access the Metabase on port `3001`, for the username and password, you can try to access the [.env](/.env) file
    - Since we have 2 Postgres containers, you can use `dataeng-warehouse-postgres` container as your data warehouse and ignore the `dataeng-ops-postgres` container since it is only being used for the opetrational purposes.

![ETL](https://github.com/nindya22/ETL-Using-Airflow-and-Metabase/assets/139938347/0b02510e-15bb-42ef-8da2-3d8941c10fcd)
---
## Data Visualization with Metabase
![dasboard](https://github.com/nindya22/ETL-Using-Airflow-and-Metabase/assets/139938347/98183134-3417-41ed-8008-c790b75d00c9)
---

