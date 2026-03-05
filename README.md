# ai-finops-analyst-agent
# AI FinOps Data Analyst Agent

## Overview
This project builds an AI-powered data analyst that analyzes cloud cost data using natural language queries.
Users can upload cost datasets and ask questions such as:
- What service increased cost yesterday?
- Detect cost anomalies
- Show cost trends

## Problem
Cloud cost datasets are complex and difficult to analyze quickly.
FinOps engineers often need to manually analyze:
- service cost increase
- anomaly detection
- cost trends

This project automates these analyses using AI.

## Dataset
Sample AWS cost dataset

Columns
- date
- service
- account
- cost

## System Architecture

User Query  
↓  
OpenAI API  
↓  
Python Code Generation  
↓  
Pandas Data Analysis  
↓  
Result Visualization

## Tech Stack
- Python
- Pandas
- OpenAI API
- Streamlit

## Result
AI-powered data analysis dashboard that answers cost-related questions.

## Future Work
- AWS API integration
- cost prediction
- Slack alert
