# Kafka Age Filter

This is an Apache Beam application that consumes messages from a Kafka topic, processes them to filter by age, and republishes them to two separate Kafka topics based on whether the age is even or odd. All processed messages are persisted to both a local CSV file and a SQL database.
