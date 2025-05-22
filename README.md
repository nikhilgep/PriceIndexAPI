# FRED API Flask App

A simple Flask app to fetch Federal Reserve Economic Data (FRED) series observations and metadata.

## Endpoints

- `/observations?series_id=SERIES_ID[&observation_start=YYYY-MM-DD][&observation_end=YYYY-MM-DD]`
- `/series?series_id=SERIES_ID`

## Deployment

1. Set the environment variable `FRED_API_KEY` in your Render dashboard.
2. Deploy this repo as a web service on Render.
