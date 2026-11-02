# Cymbal Trucks — Cube Cloud Semantic Layer

Semantic layer connected to Google BigQuery (`cymbal-trucks`, `US` multi-region) on Cube Cloud (`https://mattturner.cubecloud.dev`).

## Structure
- `model/cubes/truck_telemetry.yml` — Fleet & vehicle IoT telemetry (`CymTruckTelemetry.JSON_Data_Parsed`)
- `model/cubes/fin_accounts.yml` — Chart of accounts (`cymbal_financial_reporting.fin_accounts`)
- `model/cubes/fin_transactions.yml` — General ledger transactions (`cymbal_financial_reporting.fin_transactions`)
- `model/views/fleet_operations.yml` — Curated Fleet Operations view for BI & AI agents
- `model/views/financial_overview.yml` — Curated Financial Reporting view joining transactions & accounts
