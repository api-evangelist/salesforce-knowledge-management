# Salesforce Knowledge Management

API for managing knowledge articles, categories, and data in Salesforce Knowledge. Enables creating, reading, updating, publishing, and archiving knowledge articles for customer self-service and agent-assisted support scenarios.

**URL:** https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/

**Tags:** Articles, CRM, Customer Service, Documentation, Knowledge Management, Support

## APIs

### Salesforce Knowledge REST API

REST API for accessing and managing Salesforce Knowledge articles, categories, and knowledge base content.

- **Base URL:** https://yourInstance.salesforce.com/services/data/v59.0/support
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development.htm
- **OpenAPI:** [salesforce-knowledge-management-rest-api-openapi.yml](openapi/salesforce-knowledge-management-rest-api-openapi.yml)
- **Authentication:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm

### Salesforce Knowledge SOAP API

SOAP API for managing knowledge articles with enterprise integration.

- **Base URL:** https://yourInstance.salesforce.com/services/Soap/c/59.0
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_knowledge.htm
- **WSDL:** https://yourInstance.salesforce.com/services/wsdl/class/KnowledgeArticleVersion

## Common Resources

| Type | URL |
|------|-----|
| Getting Started | https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development_intro.htm |
| Authentication | https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm |
| Rate Limits | https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm |
| SDKs | https://developer.salesforce.com/tools/sdks |
| Status | https://status.salesforce.com/ |
| Terms of Service | https://www.salesforce.com/company/legal/agreements/ |
| Privacy Policy | https://www.salesforce.com/company/privacy/ |
| Trailhead Learning | https://trailhead.salesforce.com/en/content/learn/modules/knowledge-basics |
| GitHub Organization | https://github.com/salesforce |

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [salesforce-knowledge-management-rest-api-openapi.yml](openapi/salesforce-knowledge-management-rest-api-openapi.yml) | Salesforce Knowledge REST API — articles, categories, search, and suggestions |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [salesforce-knowledge-management-rules.yml](rules/salesforce-knowledge-management-rules.yml) | Spectral rules enforcing Salesforce Knowledge API conventions |

### Capabilities

| Capability | Description |
|------------|-------------|
| [knowledge-management.yaml](capabilities/knowledge-management.yaml) | Unified workflow capability for Knowledge article lifecycle management (11 tools) |

**Shared Definitions:**

| Shared | Description |
|--------|-------------|
| [knowledge-rest-api.yaml](capabilities/shared/knowledge-rest-api.yaml) | Salesforce Knowledge REST API consumed definition |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [salesforce-knowledge-management-article-schema.json](json-schema/salesforce-knowledge-management-article-schema.json) | Schema for Salesforce Knowledge Article objects |
| [salesforce-knowledge-management-category-schema.json](json-schema/salesforce-knowledge-management-category-schema.json) | Schema for Salesforce Knowledge Data Category objects |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [salesforce-knowledge-management-article-structure.json](json-structure/salesforce-knowledge-management-article-structure.json) | Structural documentation for the Knowledge Article resource |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [salesforce-knowledge-management-context.jsonld](json-ld/salesforce-knowledge-management-context.jsonld) | JSON-LD context mapping Knowledge vocabulary to schema.org |

### Examples

| Example | Description |
|---------|-------------|
| [salesforce-knowledge-management-search-articles-example.json](examples/salesforce-knowledge-management-search-articles-example.json) | Example request/response for searching knowledge articles |
| [salesforce-knowledge-management-create-article-example.json](examples/salesforce-knowledge-management-create-article-example.json) | Example request/response for creating a knowledge article draft |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [salesforce-knowledge-management-vocabulary.yml](vocabulary/salesforce-knowledge-management-vocabulary.yml) | Domain vocabulary and taxonomy for Salesforce Knowledge Management |

## Maintainers

- Kin Lane (kin@apievangelist.com)
