Wikimedia to OpenSearch via Kafka

This project demonstrates a pipeline where Wikimedia data is streamed using Apache Kafka as a producer and consumed by OpenSearch. The data is visualized using OpenSearch Dashboards, enabling real-time insights.


Overview

This project streams real-time Wikimedia data to an OpenSearch database via Apache Kafka. The pipeline consists of the following components:

Wikimedia Producer: Streams real-time data from Wikimedia using Kafka.

Kafka Consumer: Processes and indexes the data into OpenSearch.

OpenSearch Dashboards: Visualizes the data with customizable dashboards.

Features

Real-time data streaming from Wikimedia.

Integration with Apache Kafka for robust message handling.

Data indexing and querying in OpenSearch.

Interactive visualization using OpenSearch Dashboards.

Technologies Used

Apache Kafka: Message broker for real-time data streaming.

Wikimedia Event Streams: Source of real-time data.

OpenSearch: Search and analytics engine.

OpenSearch Dashboards: Visualization platform for OpenSearch.

Docker: Containerization for seamless deployment.

Architecture

+----------------+          +----------------+          +----------------+          +-------------------+
| Wikimedia Data |   --->   | Kafka Producer |   --->   | Kafka Consumer |   --->   | OpenSearch Index  |
+----------------+          +----------------+          +----------------+          +-------------------+
                                                                       |
                                                                       v
                                                        +---------------------------+
                                                        | OpenSearch Dashboards     |
                                                        +---------------------------+

Setup Instructions

Prerequisites

Docker and Docker Compose installed.

Basic understanding of Kafka and OpenSearch.


