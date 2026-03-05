# AI FinOps Analyst Agent

AI-powered analytics system for analyzing cloud infrastructure usage and cost data.

This project simulates a FinOps environment where engineers analyze cloud resource consumption across multiple services and regions.

The goal of this project is to explore how AI-assisted analytics can support cloud cost monitoring, anomaly detection, and infrastructure usage analysis.

---

## Problem Statement

Cloud infrastructure cost data is complex and difficult to analyze manually.

FinOps engineers frequently need to analyze:

- service-level cost distribution  
- regional infrastructure usage  
- resource utilization patterns  
- potential cost anomalies  

Manual analysis of these datasets can be time-consuming and error-prone.

This project explores how AI-assisted analytics can help simplify cloud cost analysis and provide insights from infrastructure usage data.

---

## Dataset

This project uses a simulated **Google Cloud Platform (GCP) infrastructure usage and cost dataset**.

The dataset contains cloud resource usage metrics, infrastructure utilization data, and associated cost information.

It simulates a real-world FinOps scenario where engineers monitor cloud infrastructure usage and cost across multiple services and regions.

Dataset size:

```
1000 records
```

---

## Dataset Columns

| Column | Description |
|------|-------------|
| Resource ID | Unique identifier for each cloud resource |
| Service Name | GCP service (BigQuery, Pub/Sub, Dataproc, etc.) |
| Usage Quantity | Amount of resource usage |
| Usage Unit | Unit of resource usage |
| Region/Zone | Cloud region where the resource is deployed |
| CPU Utilization (%) | CPU usage percentage |
| Memory Utilization (%) | Memory usage percentage |
| Network Inbound Data (Bytes) | Incoming network traffic |
| Network Outbound Data (Bytes) | Outgoing network traffic |
| Usage Start Date | Start time of resource usage |
| Usage End Date | End time of resource usage |
| Cost per Quantity ($) | Cost per unit of usage |
| Unrounded Cost ($) | Raw calculated cost |
| Rounded Cost ($) | Rounded cost value |
| Total Cost (INR) | Total calculated cost |

---

## Project Structure

```text
FINOPS AGENT
│
├── data
│   └── gcp_final_approved_dataset.csv
│
├── notebooks
│   └── eda_analysis.ipynb
│
├── app
│   └── streamlit_app.py
│
├── requirements.txt
└── README.md
```

---

## Methodology

This project performs several analytical tasks on cloud infrastructure data.

Analysis tasks include:

- Service-level cost distribution analysis  
- Regional infrastructure usage comparison  
- CPU utilization analysis  
- Network traffic usage analysis  
- Cost anomaly detection  

The goal is to understand infrastructure usage patterns and identify potential cost issues.

---

## Results

Key insights obtained from the dataset analysis include:

- identification of high-cost cloud services  
- detection of resources with high CPU utilization  
- analysis of network traffic patterns  
- detection of potential cost anomalies  

These findings demonstrate how cloud infrastructure data can be analyzed to support FinOps decision making.

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/ai-finops-analyst-agent.git
cd ai-finops-analyst-agent
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

Run the Streamlit dashboard

```bash
streamlit run app/streamlit_app.py
```

---

## Future Improvements

Potential improvements for this project include:

- integration with real cloud billing APIs  
- automated anomaly detection using machine learning  
- interactive dashboard enhancements  
- natural language query support for cloud cost analysis  

---

## Tech Stack

Technologies used in this project:

- Python  
- Pandas  
- Streamlit  
- Data Analysis  
- FinOps Cost Analytics
