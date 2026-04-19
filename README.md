The Flat Rate Movers — AI Ecosystem Repository
This repository hosts the public, machine‑readable AI datasets that power The Flat Rate Movers’ AI‑native operational model.
It is designed for:

AI agents

LLMs

Search engines

Developers

Integrators

Knowledge systems

Automation frameworks

All files in this repository are public, stable, versioned, and safe for ingestion.
theflatratemovers-ai/
│
├── data/
│   ├── ai-master-index.json
│   ├── ai-sitemap.json
│   ├── capabilities-matrix.json
│   ├── developer-feed.json
│   └── entity-graph.json
│
├── models/
│   ├── pricing_model.json
│   ├── scheduling_constraints.model.json
│   ├── dispatch_logic.model.json
│   ├── risk_damage_prevention.model.json
│   └── localbusiness-ai-action-model.json
│
├── schemas/
│   ├── ai-inventory-reasoning.schema.json
│   ├── ai-customer-intake.schema.json
│   ├── ai-risk-profile.schema.json
│   ├── ai-scheduling-request.schema.json
│   └── ai-estimate-request.schema.json
│
├── geo/
│   └── service-area.geojson
│
└── README.md
| File | Purpose |
| --- | --- |
| ``ai-master-index.json`` | Root index of all datasets, models, schemas, and endpoints |
| ``ai-sitemap.json`` | Machine‑readable sitemap for AI systems |
| ``capabilities-matrix.json`` | Maps capabilities → models → schemas |
| ``developer-feed.json`` | Versioning + update feed |
| ``entity-graph.json`` | Business entity relationships |
| Model | Purpose |
| --- | --- |
| ``pricing_model.json`` | Pricing logic for estimates |
| ``scheduling_constraints.model.json`` | Time windows, constraints, rules |
| ``dispatch_logic.model.json`` | Crew + truck assignment logic |
| ``risk_damage_prevention.model.json`` | Risk scoring + mitigation |
| ``localbusiness-ai-action-model.json`` | Higher‑level AI action routing |
| Schema | Purpose |
| --- | --- |
| ``ai-inventory-reasoning.schema.json`` | Inventory structure for volume + fragility |
| ``ai-customer-intake.schema.json`` | Customer + move details |
| ``ai-risk-profile.schema.json`` | Risk scoring output |
| ``ai-scheduling-request.schema.json`` | Scheduling job structure |
| ``ai-estimate-request.schema.json`` | Estimate generation structure |
| File | Purpose |
| --- | --- |
| ``service-area.geojson`` | Winchester VA, Martinsburg WV, and extended service polygons |
🔗 Developer Portal
Human‑readable documentation:
https://theflatratemovers.com/developer/

## 📘 AI Ecosystem Wiki
Full documentation:
https://github.com/TheFlatRateMovers/theflatratemovers-ai/wiki


Machine‑readable endpoints:
All files in this repository + public Gists.
📘 License
All files in this repository are provided for public AI ingestion and developer integration.
