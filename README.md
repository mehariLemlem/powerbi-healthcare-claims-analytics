# Healthcare Claims Financial Analytics

End-to-end healthcare claims and financial analytics solution built with **Microsoft Fabric, SQL, Power BI, and dimensional data modeling**.

## Project Overview

This project demonstrates how to build a production-style healthcare analytics platform from raw source data through data engineering, dimensional modeling, semantic modeling, and Power BI reporting.

The solution analyzes:

- Healthcare claims
- Member demographics
- Provider performance
- Billed vs. allowed vs. paid amounts
- Claim status
- Claim utilization
- Financial trends
- Provider and member-level analytics

> **Disclaimer:** All datasets in this repository are synthetic and created exclusively for demonstration and educational purposes. They do not contain real patient, member, provider, or claims information.

## Architecture

```text
CSV Source Files
      |
      v
Microsoft Fabric
      |
      v
Bronze Layer
      |
      v
Silver Layer
      |
      v
Gold / Dimensional Model
      |
      v
Power BI Semantic Model
      |
      v
Claims & Financial Analytics Dashboard

