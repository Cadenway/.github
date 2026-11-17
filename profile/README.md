# Cadenway

**A shared space for the work that moves projects forward.**

Cadenway brings project and task management, documents, automation, and real-time collaboration together in one platform. This organization contains the applications, services, contracts, and infrastructure that make up the project.

[Discover Cadenway](https://cadenway.com) · [Explore the repositories](https://github.com/orgs/Cadenway/repositories) · [Start the local stack](https://github.com/Cadenway/cadenway-ops#readme)

## One place for your team's work

- **Organize projects:** bring spaces, lists, sprints, and tasks together.
- **Keep context close:** work with documents and attachments alongside project information.
- **Stay in sync:** follow updates, notifications, and presence across the application.
- **Make work flow:** connect tools and build automation around recurring actions.

## Explore the platform

Cadenway is organized as a collection of focused repositories. Start with the application to explore the user experience, or follow the contracts and services to understand how the platform fits together.

### Applications and experience

| Repository | Purpose |
| --- | --- |
| [Web application](https://github.com/Cadenway/cadenway-webapp) | The Angular application for working in Cadenway. |
| [Website](https://github.com/Cadenway/cadenway-website) | The public site and legal pages. |
| [Design system](https://github.com/Cadenway/cadenway-design-system) | Shared Angular components, icons, design tokens, and Storybook. |

### APIs and shared foundations

| Repository | Purpose |
| --- | --- |
| [API contracts](https://github.com/Cadenway/cadenway-api-contracts) | OpenAPI and AsyncAPI specifications and generated packages. |
| [API gateway](https://github.com/Cadenway/cadenway-api-gateway) | The public API for application requests. |
| [Realtime gateway](https://github.com/Cadenway/cadenway-realtime-gateway) | WebSocket updates and presence. |
| [Service kit](https://github.com/Cadenway/cadenway-service-kit) | Shared NestJS foundations for services and gateways. |
| [Tooling](https://github.com/Cadenway/cadenway-tooling) | Development and architecture testing tools. |

### Platform services

| Repository | Purpose |
| --- | --- |
| [Tasks](https://github.com/Cadenway/cadenway-task-service) | Spaces, lists, sprints, tasks, and related work. |
| [Documents](https://github.com/Cadenway/cadenway-document-service) | Block-based documents. |
| [Storage](https://github.com/Cadenway/cadenway-storage-service) | File attachments and object storage. |
| [Identity](https://github.com/Cadenway/cadenway-identity-service) | Accounts, authentication, sessions, and API tokens. |
| [Organizations](https://github.com/Cadenway/cadenway-organization-service) | Organizations, members, invitations, domains, and audit logs. |
| [Billing](https://github.com/Cadenway/cadenway-billing-service) | Plans, seats, invoices, and quotas. |
| [Notifications](https://github.com/Cadenway/cadenway-notification-service) | Inbox, reminders, preferences, and emails. |
| [Automation](https://github.com/Cadenway/cadenway-automation-service) | When–then automation rules. |
| [Integrations](https://github.com/Cadenway/cadenway-integration-service) | GitHub and GitLab integrations. |
| [Search](https://github.com/Cadenway/cadenway-search-service) | Search indexing. |

### Operations

[**Cadenway Ops**](https://github.com/Cadenway/cadenway-ops) brings together the local stack, deployment configuration, and infrastructure tooling. Its README is the starting point for running the platform locally.

## Built with

The platform combines **Angular** and **TypeScript** on the front end with **NestJS** services. OpenAPI and AsyncAPI describe the interfaces between applications and services; PostgreSQL, NATS, and Docker Compose support the platform's service architecture and local development.

## Getting involved

Each repository has its own README with setup and checks, as well as its own contribution, support, security, and licensing information. Start with the repository closest to the area you want to explore.

---

[Website](https://cadenway.com) · [All repositories](https://github.com/orgs/Cadenway/repositories)
