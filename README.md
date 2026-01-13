# Ray-Ban Reviews ETL Pipeline

This project implements a local ETL (Extract, Transform, Load) pipeline
for processing Amazon product reviews of Ray-Ban Meta glasses.

## Overview
The pipeline ingests raw CSV review data, cleans and normalizes fields,
adds derived metrics, and outputs an analytics-ready dataset.

## Pipeline Stages

### Extract
- Reads raw CSV files using pandas

### Transform
- Parses and normalizes review dates
- Cleans HTML from review text
- Handles missing and malformed numeric fields
- Adds derived columns (review length, processed timestamp)
- Enforces basic data integrity rules

### Load
- Writes cleaned data to a processed CSV file

