# Introduction to Telemetry

---

### *“With model-driven telemetry (MDT), routers can stream out large amounts of operational data in a highly efficient, easily consumable way”*

---

## Current Model and Shortcomings

- Pull model to gather Operational stats
- Scaling (e.g. Syslog, SNMP)
- CPU load (e.g. Syslog, SNMP)
- Complex Structure (e.g SMI)
- In other words: **lack of efficiency**
    
---

## New Monitoring Requirements

- High-resolution data (every second)
- big data storage & analysis (store and analyze)
- Dial out model (no polling, CPU-friendly)
- many consuming needs
- Event prediction  & Automated actions (pool allocations)

---

## Telemetry (streaming)

- Data streamed from network elements
- near real-time monitoring
- data on-change functionality
- Get as much data off the box as quickly as possible
- Flexible data serialization (fit own tools and automation procedures)

---

## Early PoCs

- Psalidi (w/ Nucleus)
- Paiania 
  - local ASR streaming IfStats, CPU/MEM, QoS
  - Pipeline to collect
  - InfluxDB as TSDB
  - Grafana as Frontend

---

## Paiania Lab Diagram

![painia lab diagram](http://loco.otenet.gr/telemetry.png)
