FROM ghcr.io/mlflow/mlflow:v2.11.1

RUN apt-get update && apt-get install -y \
    libpq-dev \
    gcc \
    && rm -rf /var/lib/apt/lists/*

RUN pip install \
    psycopg2 \
    boto3

WORKDIR /opt/mlflow
