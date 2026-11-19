# Task Tracker Dashboard

A lightweight task-tracking dashboard for multi-department teams, so progress lives in one place instead of chats and scattered spreadsheets.

## Status
Early stage. Phase 1 is being built with Devin.

## Planned features
- Microsoft Entra ID (M365) single sign-on, restricted to one tenant
- Role-based access: department heads edit their own team's tasks; leadership gets a read-only overview
- Tasks with owner, deadline, status and weighted subtasks
- Auto-calculated progress % per task and per department, plus overdue rate
- Microsoft Teams bot (Phase 2): reminders 24h before a deadline and when overdue

## Stack
Next.js 14, TypeScript, PostgreSQL (Prisma), NextAuth

## Roadmap
- [ ] Phase 1: schema, SSO, task API, progress calculation, tests
- [ ] Phase 2: Teams bot and alerts
- [ ] Phase 3: dashboards and pilot with 2-3 departments

## License
MIT
