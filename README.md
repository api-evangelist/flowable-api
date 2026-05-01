# Flowable (flowable-api)

Flowable connects systems, data, and people for faster and smarter process automation. Drawing on a long heritage of open source business process management, Flowable provides a model-driven, low-code platform for end-to-end automation of BPMN, CMMN, and DMN processes. The platform is used by enterprises to drive operational excellence and digital transformation through BPM, case management, and decision automation.

For developers, Flowable is delivered through a programmatic Java Process Engine API and a packaged REST API webapp. The Process Engine exposes a set of services that together cover the full BPM lifecycle: RepositoryService, RuntimeService, TaskService, IdentityService, HistoryService, ManagementService, FormService, and DynamicBpmnService.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/flowable-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Automation
- BPM
- BPMN
- Business Process
- CMMN
- DMN
- Workflows

## APIs

### Flowable Process Engine API

The Process Engine API is the primary programmatic interface for interacting with Flowable. From a configured ProcessEngine, applications obtain services that cover deployment, runtime, tasks, identity, history, jobs, forms, and runtime modifications.

- **RepositoryService** — deploy and manage process definitions, versions, and resources.
- **RuntimeService** — start process instances, manage variables, send signals.
- **TaskService** — query, assign, claim, and complete human tasks.
- **IdentityService** — users and groups (often integrated with LDAP).
- **HistoryService** — audit data, historical queries, and process metrics.
- **ManagementService** — jobs, timers, and engine database metadata.
- **FormService** — start and task forms embedded in process definitions.
- **DynamicBpmnService** — runtime modifications to process definitions.

The API supports both fluent typesafe queries and native SQL queries.

**Documentation:** [https://www.flowable.com/open-source/docs/bpmn/ch04-API](https://www.flowable.com/open-source/docs/bpmn/ch04-API)

### Flowable REST API

Flowable ships a packaged REST API webapp that exposes the Process Engine services over HTTP. The REST API covers process definitions and deployments, process instances and variables, user tasks and forms, history, identity, and engine management, enabling non-Java clients to drive BPMN, CMMN, and DMN processes from any platform.

**Documentation:** [https://www.flowable.com/open-source/docs/](https://www.flowable.com/open-source/docs/)

**GitHub:** [https://github.com/flowable/flowable-engine](https://github.com/flowable/flowable-engine)

## Common Properties

- [Website](https://www.flowable.com/)
- [Documentation](https://www.flowable.com/open-source/docs/)
- [GitHub Repository](https://github.com/flowable/flowable-engine)
- [GitHub Organization](https://github.com/flowable)
- [Blog](https://blog.flowable.org/)

## Timestamps

- **Created:** 2024-11-07
- **Modified:** 2026-04-28

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
