# Intro - Build Images

### Minio
* docker tag minio gitpodregistry20.azurecr.io/minio:latest
* docker push gitpodregistry20.azurecr.io/minio:latest
* docker pull gitpodregistry20.azurecr.io/minio:latest

### Jupyter-Spark

* docker build -t gitpodregistry20/jupyter-spark .
* docker tag gitpodregistry20/jupyter-spark:latest gitpodregistry20.azurecr.io/jupyter-spark:latest
* docker push gitpodregistry20.azurecr.io/jupyter-spark:latest
* docker pull gitpodregistry20.azurecr.io/jupyter-spark:latest

### Postgres
* docker build -t gitpodregistry20/postgres .
* docker push gitpodregistry20.azurecr.io/postgres:latest
* docker pull gitpodregistry20.azurecr.io/postgres:latest

### PGadmin
* docker tag dpage/pgadmin4 gitpodregistry20.azurecr.io/pgadmin4:latest
* docker push gitpodregistry20.azurecr.io/pgadmin4:latest
* docker pull gitpodregistry20.azurecr.io/pgadmin4:latest

### Fastapi
* docker build -t gitpodregistry20/fastapi .
* docker tag tiangolo/uvicorn-gunicorn-fastapi:python3.7 gitpodregistry20.azurecr.io/fastapi:latest
* docker push gitpodregistry20.azurecr.io/fastapi:latest
* docker pull gitpodregistry20.azurecr.io/fastapi:latest

### Superset
* docker build -t gitpodregistry20/superset .
* docker tag wuuker/docker-airflow:latest gitpodregistry20.azurecr.io/airflow:latest
* docker push gitpodregistry20.azurecr.io/superset:latest
* docker pull gitpodregistry20.azurecr.io/superset:latest

### Airflow
* docker build -t gitpodregistry20/airflow .
* docker tag mini-data-lake-main_airflow gitpodregistry20.azurecr.io/airflow:v1
* docker push gitpodregistry20.azurecr.io/airflow:latest
* docker pull gitpodregistry20.azurecr.io/airflow:latest