# AI FinOps-Analyst-Agent
An AI-powered analytics system that analyzes cloud infrastructure cost data and detects cost anomalies.
This project simulates a FinOps environment where engineers analyze cloud resource consumption across multiple services and regions.

## Problem Statement
Cloud infrastructure cost data is complex and difficult to analyze manually.
FinOps engineers frequently need to analyze:
- service-level cost distribution
- regional infrastructure usage
- resource utilization patterns
- cost anomalies

This project aims to automate cloud cost analysis using AI-powered data analytics.

## Dataset
This project uses a simulated Google Cloud Platform (GCP) usage dataset.
The dataset contains:
- resource usage metrics
- infrastructure utilization
- cost information

### Dataset Columns
| Column | Description |
|------|-------------|
| Resource ID | Cloud resource identifier |
| Service Name | GCP service (BigQuery, Pub/Sub, Dataproc) |
| Usage Quantity | Amount of resource usage |
| Region | Cloud region |
| CPU Utilization (%) | CPU usage |
| Memory Utilization (%) | Memory usage |
| Network Inbound Data | Incoming traffic |
| Network Outbound Data | Outgoing traffic |
| Rounded Cost ($) | Calculated cost |

## Project Structure
ai-finops-cost-analysis
│
├── data
│   └── gcp_dataset.csv
│
├── notebooks
│   └── eda_analysis.ipynb
│
├── app
│   └── streamlit_app.py
│
├── requirements.txt
└── README.md

## Methodology
The project performs the following analysis:
- Service cost distribution analysis
- Regional cost comparison
- Resource utilization analysis
- Network traffic analysis
- Cost anomaly detection

## Results
Key findings:
- BigQuery generated the highest cost among services.
- Some resources showed high CPU utilization.
- Several cost anomalies were detected in the dataset.
- 
The project demonstrates how AI-powered analytics can simplify cloud cost monitoring.

## Installation
Clone the repository
git clone https://github.com/username/ai-finops-analyst-agent.git
cd ai-finops-cost-analysis
pip install -r requirements.txt
