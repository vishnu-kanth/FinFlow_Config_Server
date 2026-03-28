# FinFlow Config Repository

This repository stores the centralized Spring Cloud Config files used by the FinFlow services.

## Files

- `application.yml`: shared defaults such as DB credentials, Eureka client settings, RabbitMQ settings, JWT defaults, and tracing.
- `ADMIN-SERVICE.yml`, `APPLICATION-SERVICE.yml`, `AUTH-SERVICE.yml`, `DOCUMENT-SERVICE.yml`, `API-GATEWAY.yml`, `EUREKA-SERVER.yml`: service-specific overrides.

## Local usage

Run the config server with:

```powershell
$env:CONFIG_REPO_URI = "file:///C:/Users/HP/OneDrive/Desktop/FinFlow/FinFlow_Config_Server"
```
