# Awesome-API-Collection-Templates-Blueprints

# Awesome-API-Collection-Templates-Blueprints

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **your list mixes four different things**, and the "open-source" side is thinner than it appears.

## The category problem

Your list combines:

- **Postman Collection Templates**: a feature inside Postman—predefined content you apply when creating a collection . Not a standalone product.
- **SwaggerHub Domains**: a proprietary SwaggerHub feature for reusable components (definitions, path items, parameters, responses) . No open-source equivalent.
- **ReadMe Recipes**: a proprietary ReadMe feature for step-by-step code walkthroughs with line-by-line annotation . Not a template library.
- **API Blueprint**: an **open specification language**—a set of semantic assumptions over Markdown for describing APIs . It is a format, not a template collection.
- **RAML**: an open modeling language, but the GitHub topic results show the ecosystem is largely **archived or stale**—MuleSoft Labs repos are archived, and the most recent activity is from 2024 .
- **Microcks Templates**: **open-source** mock response templating using mustaches, JSON Pointer, XPath, and fallback expressions . This is a real, active feature of an open-source project.
- **Insomnia/Hoppscotch Collections**: both clients support **import/export** of collections, but "templates" are just saved requests . Not a template ecosystem.
- **OpenAPI Starter Kits**: this is a **GitHub topic**, not a product. The one surfaced (Hono Open API Starter) is a community starter template .
- **Speakeasy Templates**: `gen.yaml` configuration for SDK generation—proprietary SaaS configuration, not a template library .

## What the search results actually contain

**Genuinely open-source items:**

| Project | What it actually is | Status |
|---|---|---|
| **API Blueprint** | Open specification language (Markdown-based)  | Open spec |
| **Microcks Templates** | Mock response templating with JSON Pointer/XPath/fallbacks  | Active, open source |
| **Hono Open API Starter** | Community starter template for Hono + Zod + Scalar  | Active |

**Proprietary features (not open source):**
- Postman Collection Templates 
- SwaggerHub Domains 
- ReadMe Recipes 
- Speakeasy `gen.yaml` 

**Stale or archived:**
- **RAML ecosystem**: MuleSoft Labs repos are archived; most recent activity 2024 .

**What is missing:**
- **No star counts** for any of these projects in the results.
- **No pricing** for Postman, SwaggerHub, ReadMe, or Speakeasy.
- **No revenue or valuation** for any vendor.

## What I recommend

**Rename the repo** to something honest, such as:

> **Awesome API Specification Languages & Starter Templates** — a curated list of open API description formats (API Blueprint, RAML, OpenAPI), mock templating (Microcks), and community starter kits (Hono Open API Starter).

**The "SaaS/Hosted Platforms" section should list proprietary features honestly:**
- Postman Collection Templates (quote-only)
- SwaggerHub Domains (quote-only)
- ReadMe Recipes (quote-only)
- Speakeasy Templates (quote-only)

**The "Open-Source" section should contain only what is actually open source:**
- API Blueprint (specification)
- Microcks (mock templates)
- Hono Open API Starter (starter template)

**Drop RAML or mark it as legacy.** The ecosystem is archived and stale .

**Do not present "OpenAPI Starter Kits" as a product.** It is a GitHub topic, not a thing.

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate star counts, invent pricing, or present Postman/SwaggerHub/ReadMe features as open source.
