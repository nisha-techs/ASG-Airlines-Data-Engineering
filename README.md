# ASG Airlines – Data Engineering Assessment

## Project Overview

This project focuses on building an end-to-end data engineering pipeline
for ASG Airlines flight, booking, passenger and payment data.

The project includes data ingestion, data quality checking, cleaning,
transformation, PII protection, analysis and Power BI visualization.

## Objectives

- Ingest the supplied airline datasets
- Perform data quality checks
- Handle missing and duplicate records
- Standardize inconsistent values
- Protect passenger PII
- Create analytical datasets
- Calculate business KPIs
- Build an interactive Power BI dashboard
- Document the complete data pipeline

## Datasets

The project uses four datasets:

- Flights
- Bookings
- Payments
- Passengers

The passenger dataset uploaded to this repository is PII-safe.

## Data Pipeline

```text
Raw Excel Data
      ↓
Python / Pandas
      ↓
Data Quality Checks
      ↓
Cleaning & Transformation
      ↓
PII Protection
      ↓
Clean Datasets
      ↓
Power BI
      ↓
Dashboard
