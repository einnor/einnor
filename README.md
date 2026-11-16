# Ronnie Nyaga

### APIs, asynchronous workflows, and thoughtful interfaces.

I build software with a focus on **correctness, reliability, and clear trade-offs**. My public projects explore the path from an interactive client to an API, persistent state, and background work.

## Start here

| Project | Engineering focus | Explore |
| --- | --- | --- |
| **[GraphQL Forum API](https://github.com/einnor/graphql-forum-api)** | Authorization boundaries, request-scoped batching, transactional answer selection, database migrations and subscription events. | [Schema](https://github.com/einnor/graphql-forum-api/blob/master/docs/schema.graphql) · [Integration scenarios](https://github.com/einnor/graphql-forum-api/blob/master/test/forum.test.js) |
| **[Uptime](https://github.com/einnor/uptime)** | A dependency-free Node.js monitoring API: sessions, background probes, timeouts, atomic file replacement and status-change alerts. | [API walkthrough](https://github.com/einnor/uptime#readme) · [Failure-path tests](https://github.com/einnor/uptime/blob/master/test/uptime.test.js) |
| **[Serverless Reminders](https://github.com/einnor/serverless-reminders)** | Scheduled Lambda workflows, SES integration, scoped IAM and offline email-template verification. | [Design and operational boundaries](https://github.com/einnor/serverless-reminders#readme) |

## Interfaces and state

| Project | What to look for |
| --- | --- |
| **[Song-Hop](https://github.com/einnor/song-hop)** | React 19 discovery UI, resilient device-local favorites, responsive layouts and user-initiated synthetic audio. An account-free demo with fictional content. |
| **[Todoey](https://github.com/einnor/flutter-todoey)** | Flutter/Provider state flow, input validation, widget interaction tests and a runnable web build. |
| **[React Tetris](https://github.com/einnor/react-tetris)** | Collision rules, immutable movement, timer lifecycle and regression-tested line-clear scoring. |

[![Song-Hop's running discovery interface](https://raw.githubusercontent.com/einnor/song-hop/master/docs/screenshots/discover.png)](https://github.com/einnor/song-hop)

Also: **[Ruyo Client](https://github.com/einnor/ruyo-client)**, a legacy TypeScript order-management frontend with documented API contracts and browser screenshots using clearly labeled simulated services.

## How I approach engineering

- **Make behavior inspectable.** Executable examples and tests should explain an API better than a feature checklist alone.
- **Exercise failure paths.** Expired sessions, missing data, interrupted requests and unavailable services are part of the design.
- **State the consistency boundary.** Atomic file writes, database transactions and at-least-once delivery solve different problems.
- **Keep demonstrations honest.** Local fixtures, external integrations and production-readiness gaps are explicitly identified in each README.

These are hands-on portfolio and learning projects, including refreshed older implementations. Their value is in the code, decisions and reproducible behavior—not claims of unverified production scale.
