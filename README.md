# darttestApi

ASP.NET Core Web API targeting .NET 10. The starter endpoint returns sample weather forecasts.

## Run the API

```bash
dotnet run
```

The API is available at `http://localhost:5000` when started with the default launch profile.

## Endpoints

- `GET /WeatherForecast` returns five sample forecast records.
- `GET /openapi/v1.json` returns the OpenAPI document in the Development environment.

## Build

```bash
dotnet build
```
