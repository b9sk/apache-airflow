# apache-airflow in Docker-compose.yaml

## Requirments
* 4GB of RAM
* docker-compose >=1.29

## Init
* copy `.env.example` to `.env`
* set `AIRFLOW_UID`, `_AIRFLOW_WWW_USER_USERNAME`, `_AIRFLOW_WWW_USER_PASSWORD` variables if needed
* run `docker-compose up airflow-init`

## Run
`docker-compose up`

After start go to `localhost:8080`

## Airflow CLI usage example
`./airflow.sh info`

## More info
Docker Reference: https://airflow.apache.org/docs/apache-airflow/stable/start/docker.html
