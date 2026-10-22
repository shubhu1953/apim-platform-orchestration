# APIM Platform Orchestration

Diagrams and talking points for an Azure integration platform built with Terraform and GitHub Actions:

* **platform-governance**: landing resource groups, OIDC deploy identities, least-privilege RBAC, PIM, GitHub environments
* **apixp-infra**: the front door: API Management, API Center, Key Vault, App Configuration, utilities, observability
* **intapp-infra**: domain services (product, orders, logistics) on a Service Bus event backbone, private by default
* **API repos**: one per domain, each publishing its API, policies and MCP tools for AI agents

View it at https://shubhu1953.github.io/apim-platform-orchestration/
