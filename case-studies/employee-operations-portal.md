<div align="center">

![FalconExLover — Neon Ops](../assets/neon-ops-header.svg)

# `MISSION FILE // OPS-03`

**EMPLOYEE OPERATIONS PORTAL**

`ENTERPRISE WORKFLOWS` · `OFFLINE RESILIENCE` · `OPERATIONS`

</div>

[← Return to systems profile](../README.md)

## `01 // context`
An internal operations portal was designed to replace fragmented, manual request workflows with a single digital entry point.

## `02 // independent delivery`
- Built a declarative request engine supporting 30 request types across 13 departments.
- Implemented role-based access, role-specific work queues, SLA tracking, escalation, employee communication features, knowledge base, and management dashboards.
- Added PWA offline request queue for unreliable connectivity.
- Built a portable deployment package with Docker and PostgreSQL, automated migrations, backup rotation, operational runbooks, and end-to-end smoke testing.

## `03 // engineering outcomes`
- New request types can be configured without creating a new page for each workflow.
- The service can run locally with SQLite and move to PostgreSQL when deployed.
- Operational tasks such as backups and recurring notifications are documented and automated.

## `04 // systems loadout`

`Next.js` · `TypeScript` · `React` · `SQLite` · `PostgreSQL` · `Docker` · `Playwright` · `PWA`

```text
REQUEST → ROUTE → TRACK → RESOLVE → LEARN
```

[← Return to systems profile](../README.md)
