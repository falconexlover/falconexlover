<picture>
  <source media="(max-width: 720px)" srcset="../assets/brand/github-readme-hero-mobile-780x390.png">
  <img src="../assets/brand/github-readme-hero-desktop-1280x320.png" alt="Star_Burster — Product and Operational Systems Engineer. Merged does not mean delivered." width="1280">
</picture>

[← Back to the profile](../README.md)

# Employee Operations Portal

**Owner-authored case study · Enterprise workflows · Offline resilience · Operations**

## Context

Fragmented employee requests needed one digital entry point without building and maintaining a separate page and handling path for every department and request type.

## Constraint

The documented scope covers 30 request types across 13 departments, role-specific queues, SLA tracking, escalation, employee communication, unreliable connectivity, deployment, backups, and recurring operations.

## Decisions

- built a declarative request engine so new request types can be configured instead of receiving a dedicated page;
- added role-based access, role-specific work queues, SLA tracking, escalation, communication features, a knowledge base, and management dashboards;
- added a PWA offline request queue for unreliable connectivity;
- supported local operation with SQLite and deployment with PostgreSQL;
- packaged deployment with Docker, automated migrations, backup rotation, operational runbooks, recurring notifications, and end-to-end smoke testing.

## Verification path

```text
REQUEST → ROUTE → ROLE QUEUE → TRACK → RESOLVE → SMOKE CHECK → RECOVER
```

The documented acceptance surface covers request creation, routing, role visibility, lifecycle tracking, offline queuing, deployment steps, and recurring operational tasks.

## Result

The public case documents a configurable request system that brings multiple departmental workflows into one model while keeping deployment and operational responsibilities explicit.

## Evidence boundary

The figures `30 request types` and `13 departments` are owner-authored scope facts. The documented system is a prototype: it has not been deployed or connected to live identity, mail, access-control, service-management, or accounting systems. This case does not independently prove adoption, time savings, SLA improvement, availability, security, or organization-wide business impact.

## Коротко по-русски

Портал объединяет 30 типов заявок для 13 подразделений через декларативный движок, ролевые очереди, SLA-контур и offline-очередь PWA. Это прототип: он не развёрнут и не подключён к боевым системам. Публичный кейс показывает заявленный охват и устройство рабочего потока, но не выдаёт их за независимо подтверждённый бизнес-эффект.

[← Back to the profile](../README.md)
