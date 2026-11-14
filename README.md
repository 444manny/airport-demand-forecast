# Airport Demand Forecast

Forecasts terminal passenger demand in 15-minute windows from public flight
schedule and delay data, then converts that demand into a staffing
recommendation.

## Status

Phase 0: project setup (in progress)

## Planned API (v1)

- GET /api/v1/flights?terminal=&date=
- GET /api/v1/forecast?terminal=&from=&to=
- GET /api/v1/staffing?terminal=&from=&to=&serviceTimeSec=
- GET /api/v1/health

## Stack

Java 21, Spring Boot, PostgreSQL, Docker Compose, Flyway

## Data

Public data only. No data from any employer's systems is used.