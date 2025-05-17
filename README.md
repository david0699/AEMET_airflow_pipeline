# AEMET Airflow Pipeline

This project uses Apache Airflow to orchestrate the extraction, transformation, and loading of weather forecast data from the AEMET OpenData API.

## Features

- Daily download of weather data from AEMET
- Per-autonomous community data structure
- Modular Python scripts for ingestion
- Docker-based Airflow deployment

## Requirements

- Docker & Docker Compose
- AEMET API Key (free from https://opendata.aemet.es/)

## Usage

1. Create `.env` file with your API key:
   ```env
   AEMET_API_KEY=your_key_here
