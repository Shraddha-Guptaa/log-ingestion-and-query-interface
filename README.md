# log-ingestion-and-query-interface
Log Ingestor and Query Interface
Overview
This project is a log ingestor system with a query interface that allows efficient handling of vast volumes of log data. It provides a simple interface for querying data using full-text search and specific field filters.

Table of Contents
Installation
Usage
Features
Advanced Features (Bonus)
Sample Queries
Evaluation Criteria
Submission
Tips
Installation
Clone the repository:

git clone https://github.com/Shraddha-Guptaa/log-ingestion-and-query-interface
Navigate to the project directory:

cd log-ingestor
Install dependencies:

npm install
Usage
Log Ingestor
Run the log ingestor server:

node log_ingestor.js
The log ingestor runs on port 3000 by default.
Use the provided script to populate logs into the system:

curl -X POST -H "Content-Type: application/json" -d @logs.json http://localhost:3000
Query Interface
Run the query interface:

node query_interface.js
CLI interface

Features
Log Ingestor
Ingest logs in the provided format.
Scalability to handle high volumes of logs efficiently.
Mitigation of potential bottlenecks such as I/O operations and database write speeds.
Log ingestion via an HTTP server on port 3000 by default.
