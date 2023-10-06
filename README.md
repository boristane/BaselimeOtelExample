# OpenTelemetry w/ Baselime in Containerized .NET 6 Web API

## Prerequisites

- .NET 6 SDK
- Docker

## Run the project

1. Clone the repo
1. Build the Docker image with `docker build -t baselime-otel .`
1. Edit `otel-collector-config.yaml` with your Baselime API key
1. Run the API and the OTel collector with `docker compose up`
1. You should be able to hit `http://localhost:8080/WeatherForecast`
1. View OTel traces/spans in Baselime
