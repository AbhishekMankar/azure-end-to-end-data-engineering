# Azure End-to-End Data Engineering Project

## Architecture
ADF (Lookup + ForEach + Dynamic Copy) → ADLS Gen2 (Bronze) → Databricks (Silver) → Synapse Serverless SQL (Gold Views) → Power BI

## Tech Stack
Azure Data Factory, ADLS Gen2, Azure Databricks, Azure Synapse (Serverless SQL), Power BI, Azure AD (Service Principal/IAM)

## What this repo contains
- ADF pipeline export (JSON)
- Databricks notebook(s) for transformations
- Synapse SQL scripts (schema + views)
- Architecture diagram + setup steps
