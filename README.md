# CMiC (cmic)

CMiC is a unified construction-industry ERP and project management platform used by general contractors, civil contractors, and heavy/highway builders. CMiC exposes an OAuth 2.0 secured REST API (api.cmic.ca) along with a Power BI connector for accessing project financials, job costing, subcontractor and vendor management, equipment tracking, and document management with application-level security applied across company, job, project, and employee scopes.

**URL:** [https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Access:** 3rd-Party

## Tags

- Construction
- ERP
- Finance
- Project Management

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-04-23

## APIs

### CMiC Construction ERP API
OAuth 2.0 secured REST API for project financials, subcontractor and vendor management, job costing, equipment tracking, and document management.

**Human URL:** [https://developers.cmicglobal.com/](https://developers.cmicglobal.com/)

**Base URL:** https://api.cmic.ca

#### Tags

- Construction, ERP, Finance, OAuth2, Project Management

#### Properties

- [Documentation](https://developers.cmicglobal.com/docs/overview)
- [Authentication](https://developers.cmicglobal.com/v1/docs/authentication)
- [Getting Started](https://developers.cmicglobal.com/docs/developer-api-account)
- [Reference](https://docs.cmicglobal.com/portal/Content/E_Reference_Material/CMiC_API/Reference/API_and_OAuth2/API_and_OAuth2.htm)
- [OpenAPI](openapi/cmic-construction-erp-openapi.yml)
- [JSON Schema](json-schema/cmic-project-schema.json)
- [JSON-LD Context](json-ld/cmic-context.jsonld)
- [Spectral Ruleset](rules/cmic-rules.yml)
- [Naftiko Capabilities](capabilities/cmic-construction-erp-capabilities.yml)

#### Features

- **Project Management:** List, create, retrieve, and update construction projects.
- **Job Cost Tracking:** Track jobs, cost codes, budgets, and committed costs.
- **Subcontractor and Vendor Management:** List and manage vendors and subcontractors per company.
- **Equipment Tracking:** Track equipment, usage, and assignment.
- **Document Management:** List and retrieve project documents and approvals.
- **OAuth 2.0 Authentication:** Client credentials flow with Azure / external IdP support.

#### Use Cases

- **Project Financials Dashboard:** Surface project, job, and cost-code data in BI tools.
- **Subcontractor Onboarding:** Sync vendor and subcontractor records into procurement systems.
- **Equipment Utilization:** Drive equipment utilization reporting and predictive maintenance.
- **Document Workflow Automation:** Push and pull project documents into external review workflows.

### CMiC API Power BI Connector
Native Power BI connector for CMiC ERP data, enabling BI dashboards and reports for construction project financials, job costing, and operational metrics.

**Human URL:** [https://docs.cmicglobal.com/portal/Content/Home.htm](https://docs.cmicglobal.com/portal/Content/Home.htm)

#### Tags

- Analytics, Business Intelligence, Construction, ERP, Power BI

## Common Properties

- [Website](https://cmicglobal.com/)
- [OpenAPI](openapi/cmic-construction-erp-openapi.yml)
- [JSON Schema](json-schema/cmic-project-schema.json)
- [JSON-LD Context](json-ld/cmic-context.jsonld)
- [Spectral Ruleset](rules/cmic-rules.yml)
- [Naftiko Capabilities](capabilities/cmic-construction-erp-capabilities.yml)
- [Portal](https://developers.cmicglobal.com/)
- [Documentation](https://docs.cmicglobal.com/portal/Content/Home.htm)
- [Authentication](https://developers.cmicglobal.com/v1/docs/authentication)
- [Getting Started](https://developers.cmicglobal.com/docs/developer-api-account)
- [Integrations](https://cmicglobal.com/integrations/api-bundles/)
- [Privacy Policy](https://cmicglobal.com/privacy-policy)
- [Blog](https://cmicglobal.com/resources/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
