# SMIP - Smart Manufacturing Intelligence Platform - architecture

A platform that ingests machine telemetry continuously, stores it as time series, and puts an analytics and alerting layer on top. Operators get live floor state; supervisors get trends and comparisons. Thresholds and anomaly signals drive alerts so problems surface while they are still cheap to fix.

## Components

### Ingestion

Real-time telemetry intake from floor devices

### Time-series storage

Historical readings for trend and comparison

### Analytics layer

Anomaly and threshold evaluation

### Dashboard

Live floor state and historical views

### Alerting

Notification on threshold and anomaly conditions

## Stack

| Layer | Technology |
| --- | --- |
| Frontend | TypeScript, React |
| Backend | Node.js services |
| Data | Time-series telemetry store |
| IoT | Device telemetry integration |
| Analytics | Anomaly and threshold detection |

Designed and implemented by Muhammad Tanveer - Full-Stack AI Automation Engineer.