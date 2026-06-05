# Flowable (flowable-api)

Flowable connects systems, data, and people for faster and smarter process automation, drawing on a long heritage of open source BPM. Flowable provides a model-driven, low-code platform for end-to-end automation of BPMN, CMMN, and DMN processes, delivered through a programmatic Java Process Engine API and a packaged REST API. The Process Engine exposes RepositoryService, RuntimeService, TaskService, IdentityService, HistoryService, ManagementService, FormService, and DynamicBpmnService for managing process definitions, instances, tasks, history, and runtime behavior.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flowable-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flowable-api/refs/heads/main/apis.yml)

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

## Timestamps

- **Created:** 2024-11-07
- **Modified:** 2026-05-19

## APIs

### Flowable Process Engine API

The Flowable Process Engine API is the primary programmatic interface for interacting with Flowable. From a configured ProcessEngine, applications obtain a set of services that cover the full BPM lifecycle: RepositoryService for deploying and managing process definitions, RuntimeService for starting and signaling process instances, TaskService for human task assignment and completion, IdentityService for users and groups, HistoryService for audit and reporting queries, ManagementService for jobs and engine metadata, FormService for start and task forms, and DynamicBpmnService for runtime modifications. The API supports both fluent typesafe queries and native SQL queries.

- **Human URL:** [https://www.flowable.com/open-source/docs/bpmn/ch04-API](https://www.flowable.com/open-source/docs/bpmn/ch04-API)
- **Base URL:** `https://www.flowable.com/open-source/docs/bpmn/`

#### Tags

- BPM
- BPMN
- Process Engine
- Workflows

#### Properties

- [Documentation](https://www.flowable.com/open-source/docs/bpmn/ch04-API)
- [Documentation Portal](https://www.flowable.com/open-source/docs/)
- [OpenAPI](openapi/flowable-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flowable-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowable-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flowable REST API

Flowable also ships a packaged REST API webapp that exposes the Process Engine services over HTTP. The REST API covers process definitions and deployments, process instances and variables, user tasks and forms, history, identity, and engine management, allowing non-Java clients to drive BPMN, CMMN, and DMN processes from any platform.

- **Human URL:** [https://www.flowable.com/open-source/docs/bpmn/](https://www.flowable.com/open-source/docs/bpmn/)
- **Base URL:** `https://www.flowable.com/open-source/docs/bpmn/`

#### Tags

- BPM
- REST
- Workflows

#### Properties

- [Documentation](https://www.flowable.com/open-source/docs/)
- [GitHub Repository](https://github.com/flowable/flowable-engine)
- [Postman Collection](collections/flowable-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowable-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/flowable-group)
- [Website](https://www.flowable.com/)
- [Documentation](https://www.flowable.com/open-source/docs/)
- [GitHub Repository](https://github.com/flowable/flowable-engine)
- [GitHub Organization](https://github.com/flowable)
- [Blog](https://blog.flowable.org/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
