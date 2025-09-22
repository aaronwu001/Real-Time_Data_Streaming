# Real-Time_Streaming

This project sets up a real-time data streaming pipeline using Apache Kafka, Apache Airflow, Apache Spark, and Cassandra, all containerized with Docker.

Airflow (supported by Postgres) extracts userdata from randomuser.me API, sending them to Kafka (supported by Zookeeper, Control Center, Schema Registry). Spark then receive messages from Kafka brokers and send data to Cassandra. 

**Credit**: This project is based on a YouTube tutorial by [Yusuf Ganiyu](https://www.youtube.com/channel/UCy8VZ3xj9s).
