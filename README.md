# The Racing API (the-racing-api)
High performance API for horse racing statistical modelling, application development and web content. Complete coverage of UK, Irish and Hong Kong horse racing with real-time data updates every 3 minutes.

**URL:** [Visit The Racing API](https://www.theracingapi.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Horse Racing, Sports, Statistics, Betting, Analytics

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-03

## APIs

### The Racing API
High performance API for horse racing statistical modelling, application development and web content. Complete coverage of UK, Irish and Hong Kong horse racing. Access racecards, results, horse form, jockey and trainer statistics, and real-time analysis endpoints with 58 endpoints across courses, racecards, results, horses, jockeys, trainers, owners, sires, dams, damsires, odds, and North America/Australia add-on coverage.

**Human URL:** [https://www.theracingapi.com/](https://www.theracingapi.com/)

#### Tags:

 - Horse Racing, Sports, Statistics, Racecards, Results, Analytics

#### Properties

- [Documentation](https://api.theracingapi.com/documentation)
- [OpenAPI](openapi/the-racing-api-openapi.yml)
- [Website](https://www.theracingapi.com/)
- [Authentication](https://www.theracingapi.com/dashboard)
- [JSONSchema - Racecard Summary Schema](json-schema/the-racing-api-racecard-summary-schema.json)
- [JSONStructure - Racecard Summary Structure](json-structure/the-racing-api-racecard-summary-structure.json)
- [JSON-LD - The Racing API JSON-LD Context](json-ld/the-racing-api-context.jsonld)

## Common Properties

- [Website](https://www.theracingapi.com/)
- [Documentation](https://api.theracingapi.com/documentation)
- [Sign Up](https://www.theracingapi.com/register)
- [Dashboard](https://www.theracingapi.com/dashboard)
- [SpectralRules](rules/the-racing-api-spectral-rules.yml)
- [Vocabulary](vocabulary/the-racing-api-vocabulary.yml)
- [NaftikoCapability - Horse Racing Analytics](capabilities/horse-racing-analytics.yaml)

## Features

| Name | Description |
|------|-------------|
| Real-Time Racecards | Today's and tomorrow's racecards updated every 3 minutes with odds and runners |
| Historical Results | Over 500,000 horse racing results covering UK, Ireland, and Hong Kong |
| Statistical Analysis | Analysis endpoints computing win percentages, A/E ratios, and 1-unit profit/loss for horses, jockeys, trainers, and owners |
| Breeding Data | Sire, dam, and damsire lineage data with progeny performance statistics |
| North America Coverage | Add-on coverage for North American race meets, entries, and results |
| Australia Coverage | Add-on coverage for Australian race meets and race details |
| AI/MCP Integration | Remote MCP server for integration with Claude, ChatGPT, Gemini, and other AI tools |

## Use Cases

| Name | Description |
|------|-------------|
| Application Development | Build horse racing applications and websites with live data |
| Statistical Modelling | Develop betting models using historical results and real-time analysis |
| AI Agent Integration | Feed racing data into AI agents for predictions and insights |
| Research and Analytics | Perform academic and professional research on horse racing performance |

## Integrations

| Name | Description |
|------|-------------|
| Claude AI | Integration via remote MCP server for AI-powered racing insights |
| ChatGPT | Integration via remote MCP server |
| Gemini | Integration via remote MCP server |
| Grok | Integration via remote MCP server |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [The Racing API OpenAPI](openapi/the-racing-api-openapi.yml)

### JSON Schema

122 JSON Schema files for API entities including Racecard, Result, Horse, Jockey, Trainer, Course, and analytics schemas.

- [the-racing-api-racecard-summary-schema.json](json-schema/the-racing-api-racecard-summary-schema.json)
- [the-racing-api-result-standard-schema.json](json-schema/the-racing-api-result-standard-schema.json)
- [the-racing-api-horse-schema.json](json-schema/the-racing-api-horse-schema.json)
- [the-racing-api-jockey-schema.json](json-schema/the-racing-api-jockey-schema.json)
- [the-racing-api-trainer-schema.json](json-schema/the-racing-api-trainer-schema.json)
- *(and 117 more)*

### JSON Structure

122 JSON Structure files converted from JSON Schemas.

### JSON-LD

- [The Racing API JSON-LD Context](json-ld/the-racing-api-context.jsonld)

### Examples

122 example JSON payloads for all schema types.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [The Racing API](capabilities/shared/the-racing-api.yaml) — 16 operations for horse racing data access

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Horse Racing Analytics](capabilities/horse-racing-analytics.yaml) | The Racing API | 17 | Racing Analyst, Application Developer, AI Agent |

## Vocabulary

- [The Racing API Vocabulary](vocabulary/the-racing-api-vocabulary.yml) — Unified taxonomy mapping 12 resources, 4 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [The Racing API Spectral Rules](rules/the-racing-api-spectral-rules.yml) — 20 rules across 8 categories enforcing The Racing API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
