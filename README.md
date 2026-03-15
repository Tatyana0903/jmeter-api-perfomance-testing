# API Performance Testing with JMeter

This project demonstrates API functional and load testing using Apache JMeter.

## Tested API
https://jsonplaceholder.typicode.com

## Implemented tests
- GET users
- GET posts
- GET single post
- GET post comments
- POST create post
- PUT update post
- PATCH partial update
- DELETE post

## Features
- Response assertions
- JSON Extractor (correlation)
- Data-driven testing using CSV
- Load testing with Thread Group
- Performance monitoring using JMeter listeners

## Tools
Apache JMeter

## Load Test Results

### Summary Report
![Summary Report](results/summary-report.png)

### Active Threads Over Time
![Threads](results/threads-over-time.png)

### Throughput
![Throughput](results/throughput.png)
