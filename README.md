# Awesome API Collection Templates & Blueprints [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of API templates, specifications, collection blueprints, design schemas, and development tooling across leading SaaS platforms and top-tier open-source projects.

An authoritative directory for API architects, developers, and platform engineers seeking pre-built collection templates, API specification blueprints (OpenAPI, RAML, API Blueprint), mock templates, interactive API docs, and developer experience (DX) tooling.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source Solutions](#open-source-solutions)
- [Contributing](#contributing)
- [License](#license)

---

## Sector Overview & Market Dynamics

The global API management and developer tooling market is estimated at **$7.7B – $9.7B in 2024–2025**, projected to surpass **$18B+ by 2029** at a compound annual growth rate (CAGR) exceeding 18%. 

The sector exhibits a **hybrid market structure**:
* **Enterprise Infrastructure & Gateways:** Highly **concentrated** and dominated by cloud hyperscalers and legacy enterprise integration giants (Google Cloud Apigee, AWS API Gateway, Microsoft Azure API Management, IBM, MuleSoft).
* **API Design, Collections, Mocking & Tooling:** Moderately to heavily **fragmented**, with specialized product-led platforms (Postman, SmartBear SwaggerHub, Kong Insomnia, ReadMe) competing alongside high-growth open-source tools (Hoppscotch, Scalar, Mockoon, Spectral) catering to decentralized API-first developer workflows.

---

## SaaS & Hosted Platforms

The table below catalogs proprietary and hosted platforms offering collection templates, API design hubs, and blueprint tooling. The list is sorted in descending order by **Company Size (Valuation / Revenue)**.

| SaaS Product | Description & Template Features | Company Size (Valuation / ARR) | Starting Tier Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| [**Postman**](https://www.postman.com/) | API platform providing pre-built workspace templates, collection runners, and mock servers. | **$5.6B Valuation** (~$313M ARR) | **$19/user/mo** (Team plan, billed annually) | **Free Forever**: Restricted strictly to 1 solo user (no shared workspaces/collaboration); includes unlimited collection runs and mock server requests. |
| [**Kong Insomnia**](https://insomnia.rest/) | API client and design tool with Git sync, collection workspaces, and Konnect cloud integration. | **$2.0B Valuation** (Kong Inc., $100M+ ARR) | **$10/user/mo** (Pro plan, billed annually) | **Free Forever (Essentials)**: 1 user, up to 3 collaborators on Git Sync projects, unlimited local projects, and 1,000 mock requests/mo; 14-day free trial on enterprise features. |
| [**SwaggerHub (SmartBear)**](https://swagger.io/tools/swaggerhub/) | Cloud API design and documentation platform featuring reusable SwaggerHub Domains for standardized schema components. | **$1.8B – $2.0B Valuation** (~$150M ARR) | **$19/user/mo** (Individual plan, billed annually) | **14-day Free Trial** for Team/Enterprise plans (includes domains, RBAC, webhooks); free individual basic editor access with restricted collaboration and rate limits. |
| [**ReadMe**](https://readme.com/) | Developer hub platform featuring interactive API reference docs and step-by-step API Recipe walkthrough templates. | **~$10M – $11M ARR** ($10.3M total VC funding) | **$250/mo** (Pro plan, billed annually; unlocks Recipes & Forums) | **Free Forever (Starter)**: 1 project, 1 version, 1 admin seat, custom domain, and interactive API reference with 7-day metrics history (Recipes require Pro). |
| [**Speakeasy**](https://www.speakeasy.com/) | API infrastructure platform automating SDK generation, CLI tools, and Terraform providers via `gen.yaml` configuration templates. | **$25M – $50M Valuation** ($25.9M total VC funding) | **Usage-based** (e.g., $0.35/M session storage tokens, $0.99/M risk scanner tokens, $20/GiB MCP gateway egress) | **Free Forever (Deploy for Free)**: Self-serve tier for solo developers to generate base SDKs and test MCP gateway connections without platform license fees. |

---

## Open-Source Solutions

A curated collection of open-source API specifications, mocking frameworks, testing suites, and documentation engines. Ranked in descending order by **GitHub Star Count**.

| Open-Source Project | Description & Blueprint Features | GitHub Stars |
| :--- | :--- | :--- |
| [**Hoppscotch**](https://github.com/hoppscotch/hoppscotch) | Lightweight, web-based open-source API development ecosystem and Postman alternative supporting REST, GraphQL, and WebSocket collections. | [![GitHub Stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=social&color=white)](https://github.com/hoppscotch/hoppscotch/stargazers) |
| [**Kong Insomnia**](https://github.com/Kong/insomnia) | Open-source desktop API client for GraphQL, REST, WebSockets, and gRPC with design and debugging workflows. | [![GitHub Stars](https://img.shields.io/github/stars/Kong/insomnia?style=social&color=white)](https://github.com/Kong/insomnia/stargazers) |
| [**OpenAPI Specification**](https://github.com/OAI/OpenAPI-Specification) | The vendor-neutral, industry-standard API description format for RESTful APIs across the world. | [![GitHub Stars](https://img.shields.io/github/stars/OAI/OpenAPI-Specification?style=social&color=white)](https://github.com/OAI/OpenAPI-Specification/stargazers) |
| [**Swagger UI**](https://github.com/swagger-api/swagger-ui) | High-performance HTML, JavaScript, and CSS asset collection that dynamically generates documentation from OpenAPI definitions. | [![GitHub Stars](https://img.shields.io/github/stars/swagger-api/swagger-ui?style=social&color=white)](https://github.com/swagger-api/swagger-ui/stargazers) |
| [**OpenAPI Generator**](https://github.com/OpenAPITools/openapi-generator) | Code generator supporting generation of API client SDKs, server stubs, documentation, and configuration templates from OpenAPI specs (50+ languages). | [![GitHub Stars](https://img.shields.io/github/stars/OpenAPITools/openapi-generator?style=social&color=white)](https://github.com/OpenAPITools/openapi-generator/stargazers) |
| [**Redoc**](https://github.com/Redocly/redoc) | Declarative, responsive OpenAPI/Swagger documentation renderer with customizable layout blueprints. | [![GitHub Stars](https://img.shields.io/github/stars/Redocly/redoc?style=social&color=white)](https://github.com/Redocly/redoc/stargazers) |
| [**Scalar**](https://github.com/scalar/scalar) | Modern, interactive API documentation platform and REST client featuring OpenAPI integration and theme templates. | [![GitHub Stars](https://img.shields.io/github/stars/scalar/scalar?style=social&color=white)](https://github.com/scalar/scalar/stargazers) |
| [**API Blueprint**](https://github.com/apiaryio/api-blueprint) | Powerful, human-readable Markdown-based specification language for writing API descriptions and blueprint architectures. | [![GitHub Stars](https://img.shields.io/github/stars/apiaryio/api-blueprint?style=social&color=white)](https://github.com/apiaryio/api-blueprint/stargazers) |
| [**Mockoon**](https://github.com/mockoon/mockoon) | Complete local mock server application providing environment templates, rule-based routes, and regex responses. | [![GitHub Stars](https://img.shields.io/github/stars/mockoon/mockoon?style=social&color=white)](https://github.com/mockoon/mockoon/stargazers) |
| [**RAML Specification**](https://github.com/raml-org/raml-spec) | RESTful API Modeling Language (RAML) specification allowing structured YAML descriptions of practical APIs. | [![GitHub Stars](https://img.shields.io/github/stars/raml-org/raml-spec?style=social&color=white)](https://github.com/raml-org/raml-spec/stargazers) |
| [**Spectral**](https://github.com/stoplightio/spectral) | Flexible JSON/YAML linter for OpenAPI and AsyncAPI blueprints with custom ruleset and styling templates. | [![GitHub Stars](https://img.shields.io/github/stars/stoplightio/spectral?style=social&color=white)](https://github.com/stoplightio/spectral/stargazers) |
| [**Microcks**](https://github.com/microcks/microcks) | Open-source Kubernetes-native mock response and contract testing framework supporting OpenAPI, Postman, and gRPC template schemas. | [![GitHub Stars](https://img.shields.io/github/stars/microcks/microcks?style=social&color=white)](https://github.com/microcks/microcks/stargazers) |

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork this repository.
2. Create a descriptive branch: `git checkout -b add-my-template`.
3. Add your entry ensuring accurate pricing/star badges and following the existing format.
4. Open a Pull Request with a clear summary of your changes.

---

## License

Distributed under the [MIT License](LICENSE).
