# BuildMate Rentals

## Project Overview
BuildMate Rentals is an end-to-end data engineering project built using Microsoft Fabric and Apache Spark. It transforms rental operational data into a Gold-layer star schema for business analysis.

## Architecture
- **Bronze:** Raw data ingestion.
- **Silver:** Data cleaning, standardization and validation.
- **Gold:** Dimensional modelling and analytical tables.
- **Business Analysis:** Six Spark SQL queries covering rental duration, fleet utilisation, payer revenue, depot revenue, rental mix and currently-out machines.

## Technology Stack
- Microsoft Fabric
- Fabric Lakehouse
- Apache Spark / Spark SQL
- Delta Lake
- GitHub

## Repository Structure
- `notebooks/` — Bronze, Silver, Gold and business-analysis notebooks.
- `html_files/` — Bronze, Silver, Gold and business-analysis notebooks.
- `screenshots/` — Execution evidence and query results.
- `README.md` — Project documentation and business findings.

## Validation
Document the actual query results, total revenue reconciliation, currently-out reconciliation and null-handling checks after running the notebooks.

## Business Findings
Add four to six sentences based on the verified query outputs.

## Evidence
See the `screenshots/` directory for notebook execution and query results.
