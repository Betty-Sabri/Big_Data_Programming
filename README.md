# Big Data Programming 

This repository contains all four assignments from the Big Data Programming module, covering SQL databases, MongoDB, Apache Spark (DataFrames, SQL, GraphFrames), and Structured Streaming.

---

# Overview

The project demonstrates end-to-end big data engineering skills:

* Relational databases (MySQL)
* NoSQL document databases (MongoDB)
* Distributed processing (Apache Spark)
* Graph analytics (GraphFrames)
* Real-time streaming (Structured Streaming)

---

# Assignment 1: MySQL (Relational Data Engineering)

## Key Focus

* Database schema design with primary and foreign keys
* Bulk data loading using LOAD DATA INFILE
* SQL analytics on real datasets

## Datasets

* Bike sharing stations and trips
* Global weather and air quality data

## Core Tasks

* Create normalized tables (STATIONS, TRIPS)
* Load CSV data into MySQL
* Query longest bike ride
* Perform JOIN analysis on stations and trips
* Identify max temperature locations
* Analyze air quality (PM10 in Dublin)

## Skills

SQL DDL/DML, data cleaning, relational modeling

---

# Assignment 2: MongoDB (NoSQL Document Processing)

## Key Focus

* Working with nested JSON documents
* Aggregation pipelines
* Complex filtering, updates, and deletes

## Datasets

* Financial transactions (Amazon, eBay)
* Retail sales data (supplies)

## Core Tasks

* Aggregate total quantity and revenue (Amazon)
* Compare buy vs sell totals (eBay)
* Multi-condition queries on sales data
* Update and delete operations based on conditions

## Skills

Aggregation pipeline, $unwind, $group, $cond, document querying

---

# Assignment 3: Apache Spark (DataFrames & SQL)

## Key Focus

* Distributed data processing with Spark DataFrames
* SQL-based analytics on large datasets
* Schema definition using StructType

## Datasets

* Air Quality Health Risk Assessments
* CO2 emissions from vans

## Core Tasks

* Load CSV into Spark with inferred schema
* Compute health impact (Dublin analysis)
* Identify highest pollution contributors
* SQL queries for max CO2 emissions
* Grouped emissions analysis by manufacturer

## Skills

PySpark, aggregation, filtering, Spark SQL

---

# Assignment 4: Apache Spark (GraphFrames & Streaming)

## Key Focus

* Graph analytics on transportation networks
* Real-time streaming data processing

## Datasets

* Bay Area bike sharing network
* Human activity recognition sensor stream

## Graph Analytics Tasks

* Longest bike ride detection
* Triangle counting in station graph
* PageRank to find most important station
* Triangle motif pattern analysis

## Streaming Tasks

* Count sitting activity events
* Tumbling window analysis (bike activity)
* Hopping window analysis (stairs activity)
* Event-time stateful processing

## Skills

GraphFrames, PageRank, motif finding, Structured Streaming, windowing

---

# Summary

This portfolio demonstrates a full big data pipeline covering:

* Relational databases (MySQL)
* NoSQL systems (MongoDB)
* Distributed computation (Spark)
* Graph analytics (GraphFrames)
* Real-time streaming (Spark Streaming)

Together, these assignments showcase practical skills in data engineering, analytics, and scalable processing systems.
