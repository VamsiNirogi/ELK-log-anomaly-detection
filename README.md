# Real-time Log Analytics & Anomaly Detection (ELK Stack + Python)
This repository contains a real-time ETL pipeline leveraging the ELK Stack (Elasticsearch, Logstash, Kibana) and Python for detecting anomalies in SSH system logs.

## Overview

- **Data Pipeline:** Logstash → Elasticsearch → Kibana
- **Anomaly Detection:** Python (Isolation Forest)
- **Visualization:** Kibana Dashboards, Python matplotlib

## Features

- Real-time log ingestion and parsing with Logstash.
- Structured log storage and search capabilities using Elasticsearch.
- Automated anomaly detection with Isolation Forest in Python.
- Clear visualization of detected anomalies.

## Quick Start

### Requirements
- Docker Desktop
- Python 3.x

### Installation

Clone this repository:
```bash
git clone https://github.com/VamsiNirogi/elk-log-anomaly-detection.git
cd elk-log-anomaly-detection
