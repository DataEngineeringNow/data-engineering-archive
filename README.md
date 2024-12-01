# Data Engineering Archive
The world of data engineering is constantly evolving. This repository aims to consolidate data technologies and concepts into a single resource. Let's build a comprehensive resource that captures the latest trends and technologies. Feel free to open a pull request if you spot any missing pieces.


<details open>
  <summary>Table of Contents</summary>

  1. [Data Storage](#data-storage)
  2. [Databases](#databases)
      - [Relational](#Relational-databases)
      - [Document](#document-databases)
      - [Key Value](#key-value-databases)
      - [Graph](#graph-databases)
      - [Timeseries](#timeseries-databases)
  3. [Data Batch Processing](#data-processing)
  4. [Data Stream Processing](#data-streaming)
  5. [Data Lakehouse](#data-lakehouse)
  6. [Data Formats](#data-formats)
  7. [Data Quality](#data-quality)
  8. [Orchestration](#orchestration)
      - [Open Source](#orchestration-open-source)
      - [Closed Source](#orchestration-closed-source)
  9. [Data Warehouse](#data-warehouse)
      - [Realtime data warehouse](#realtime-data-warehouse)
  10. [Query Engine](#query-engine)

</details>


--------------------------------------------------------
### Data Storage

* [Amazon s3](https://aws.amazon.com/pm/serv-s3/) - Object storage built to store and retrieve any amount of data from anywhere.
* [Google Cloud Storage](https://cloud.google.com/storage/?hl=en) - Google Cloud Storage is a managed service for storing unstructured data.
* [Azure blob storage](https://azure.microsoft.com/en-us/products/storage/blobs) - Massively scalable and secure object storage for cloud-native workloads, archives, data lakes, high-performance computing, and machine learning.

--------------------------------------------------------
### Databases

### Relational databases

* [PostgreSQL](https://www.postgresql.org/)
* [MySQL](https://www.mysql.com/)
* [MariaDB](https://mariadb.org/)
  * [MariaDB Galera Cluster](https://mariadb.com/kb/en/galera-cluster/)
* [Oracle](https://www.oracle.com/in/database/)
* [IBM Db2](https://www.ibm.com/db2)
* [SQLite](https://www.sqlite.org/)
* [GCP Cloud SQL](https://cloud.google.com/sql?hl=en)
* [GCP Cloud Spanner](https://cloud.google.com/spanner?hl=en)
* [AWS RDS](https://aws.amazon.com/rds/sqlserver/)
* [AWS Aurora](https://aws.amazon.com/rds/aurora/)
* [Azure SQL](https://azure.microsoft.com/en-in/products/azure-sql/database/)

### Key value databases
* [Redis](https://redis.io/)
* [AWS DynamoDB](https://aws.amazon.com/dynamodb/)
* [GCP Bigtable](https://cloud.google.com/bigtable?hl=en)

### Document databases
* [MongoDB](https://www.mongodb.com/)
* [Couchbase](https://www.couchbase.com/)
* [GCP Firestore](https://cloud.google.com/firestore)

### Graph databases
* [Neo4J](https://neo4j.com/)

### Timeseries databases 
* [Timescale](https://www.timescale.com/)


--------------------------------------------------------
### Data Processing

* [Apache Spark](https://spark.apache.org/) - Apache Spark™ is a multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.
* [ibis](https://github.com/ibis-project/ibis)

---------------------------------------------------------
### Data Lakehouse

* [Delta Lake](https://delta.io/) - Open-source storage framework that enables building a Lakehouse architecture with compute engines including Spark, PrestoDB, Flink, Trino, and Hive and APIs for Scala, Java, Rust, Ruby, and Python.

* [Apache Hudi](https://hudi.apache.org/) - Open-source transactional data lake platform that brings database and data warehouse capabilities to the data lake.

* [Apache Iceberg](https://iceberg.apache.org/) -
Open-source table format designed for large-scale analytics. Iceberg brings the reliability and simplicity of SQL tables to big data, while making it possible for engines like Spark, Trino, Flink, Presto, Hive and Impala to safely work with the same tables, at the same time.

--------------------------------------------------------
### Data Formats

* [Apache Parquet](https://parquet.apache.org/) - Open source, column-oriented data file format, initially developed by Twitter.

* [Apache ORC](https://orc.apache.org/) - Open source, column-oriented data file format, initially developed by Facebook.

--------------------------------------------------------
### Data Streaming

* [Apache Kafka](https://kafka.apache.org/) - Most popular distributed event streaming platform

* [Apache Storm](https://storm.apache.org/) - Open source distributed realtime computation system.Makes it easy to reliably process unbounded streams of data, doing for realtime processing what Hadoop did for batch processing

* [Apache Flink](https://flink.apache.org/)
--------------------------------------------------------
### Data Quality

* [Apache Griffin](https://griffin.apache.org/) - Open source Data Quality solution for Big Data, which supports both batch and streaming mode.

--------------------------------------------------------
### Orchestration


### Orchestration Open Source

* [Apache Airflow](https://airflow.apache.org/) - Open-source platform used to programmatically author, schedule, and monitor workflows.Airflow allows you to define workflows as Directed Acyclic Graphs (DAGs), which specify the sequence of tasks and their dependencies.
* [Apache oozie](https://oozie.apache.org/)
* [Azkaban](https://azkaban.github.io/)

### Orchestration Closed Source

* [Astronomer](https://www.astronomer.io/) - Astro is a unified data platform built on Apache Airflow® that ensures data is delivered on time, securely, and accurately.
* [Mage](https://www.mage.ai/)
* [dbt](https://www.getdbt.com/product/what-is-dbt)
* [Dagster](https://dagster.io/)
* [Perfect](https://www.prefect.io/)
* [Hamilton](https://github.com/dagworks-inc/hamilton)




### Data Warehouse

* [GCP Bigquery](https://cloud.google.com/bigquery?hl=en)
* [AWS Redshift](https://aws.amazon.com/pm/redshift/)
* [Azure Synapse Analytics](https://azure.microsoft.com/en-us/products/synapse-analytics)
* [Firebolt](https://www.firebolt.io/)
* [Snowflake](https://www.snowflake.com/en/data-cloud/workloads/data-warehouse/)
* [Panoply](https://panoply.io/)
* [SAP Data warehouse](https://api.sap.com/package/sapdatawarehousecloud/overview)

#### Realtime data warehouse
* [Druid](https://druid.apache.org/)
* [Apache Pinot](https://pinot.apache.org/)

### Query Engines
* [Apache Drill](https://drill.apache.org/)
* [Presto](https://prestodb.io/)
* [Trino](https://trino.io/)
