# bigdata-sandbox-minio-aistor
A local Big Data sandbox environment using Docker Compose — includes MinIO AIStor, Trino, Dremio, Airflow, and PostgreSQL for learning and experimentation.

<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/dd1f41b6-f198-4324-832d-5c8aa5b90517" />


# Big Data Sandbox 🚀

A local Big Data sandbox environment using Docker Compose for learning and experimentation.

## Stack
| Service | Port | Description |
|---|---|---|
| MinIO AIStor | 9100 / 9101 | Object Storage (S3-compatible) |
| Trino | 8180 | Distributed SQL Query Engine |
| Dremio | 9147 | Data Lakehouse Platform |
| Airflow | 8190 | Workflow Orchestration |
| PostgreSQL | 5537 | Relational Database |

## Getting Started

### Prerequisites
- Docker
- Docker Compose
- MinIO AIStor Free License from [min.io/pricing](https://min.io/pricing)

### Run
```bash
git clone https://github.com/<Marwahamada22>/bigdata-sandbox-minio-aistor
cd bigdata-sandbox
cp /path/to/minio.license .
docker compose up -d
```

## Access
| Service | URL | Credentials |
|---|---|---|
| MinIO Console | http://localhost:9101 | minioadmin / minioadmin |
| Trino | http://localhost:8180 | - |
| Dremio | http://localhost:9147 | - |
| Airflow | http://localhost:8190 | - |
