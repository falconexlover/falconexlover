# Employee Operations Portal

## Context
An internal operations portal was designed to replace fragmented, manual request workflows with a single digital entry point.

## Independent delivery
- Built a declarative request engine supporting 30 request types across 13 departments.
- Implemented role-based access, operator queues, SLA tracking, escalation, employee communication features, knowledge base, and management dashboards.
- Added PWA offline request queue for unreliable connectivity.
- Built a portable deployment package with Docker and PostgreSQL, automated migrations, backup rotation, operational runbooks, and end-to-end smoke testing.

## Engineering outcomes
- New request types can be configured without creating a new page for each workflow.
- The service can run locally with SQLite and move to PostgreSQL when deployed.
- Operational tasks such as backups and recurring notifications are documented and automated.

## Technologies
Next.js · TypeScript · React · SQLite · PostgreSQL · Docker · Playwright · PWA
