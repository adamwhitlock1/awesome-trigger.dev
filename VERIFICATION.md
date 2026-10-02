# Verification notes

Initial review date: October 2, 2026.

The README contains 20 curated entries. Each entry's source was inspected for relevance and its URL checked. GitHub repositories and paths were checked through the authenticated GitHub REST API; other pages were fetched with HTTP GET. Repository checks also inspected archive status and the current default branch. Descriptions summarize the linked material in original wording.

These checks establish source availability and documented use. They do not prove installation, runtime behavior, deployment reliability, security, or compatibility with every current dependency version. A repository's latest push can include non-code changes. Dates below are review snapshots, not a maintenance commitment.

## Entries

| Resource | Source inspected | Availability on review date | Upstream latest push, UTC date |
| --- | --- | --- | --- |
| [Trigger.dev source](https://github.com/triggerdotdev/trigger.dev) | Repository readme | GitHub API, 200 | 2026-10-02 |
| [Introduction](https://trigger.dev/docs/introduction) | Documentation page | HTTP GET, 200 | Not applicable |
| [SDK reference projects](https://github.com/triggerdotdev/references) | Repository readme | GitHub API, 200 | 2026-09-07 |
| [Agent workflow patterns](https://github.com/triggerdotdev/examples/tree/main/building-effective-agents) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Claude Agent SDK](https://github.com/triggerdotdev/examples/tree/main/claude-agent-sdk-trigger) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Mastra agents](https://github.com/triggerdotdev/examples/tree/main/mastra-agents) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Batch LLM evaluator](https://github.com/triggerdotdev/examples/tree/main/batch-llm-evaluator) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Article summary workflow](https://github.com/triggerdotdev/examples/tree/main/article-summary-workflow) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Realtime CSV importer](https://github.com/triggerdotdev/examples/tree/main/realtime-csv-importer) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Python Crawl4AI](https://github.com/triggerdotdev/examples/tree/main/python-crawl4ai) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Document-to-Markdown converter](https://github.com/triggerdotdev/examples/tree/main/python-doc-to-markdown-converter) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [PDF form extractor](https://github.com/triggerdotdev/examples/tree/main/python-pdf-form-extractor) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Python image processing](https://github.com/triggerdotdev/examples/tree/main/python-image-processing) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Supabase Edge Functions](https://github.com/triggerdotdev/examples/tree/main/supabase-edge-functions) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Remix webhooks](https://github.com/triggerdotdev/examples/tree/main/remix-webhooks) | Directory readme | GitHub API, 200 | 2026-09-25 |
| [Doppler secret synchronization](https://github.com/triggerdotdev/trigger-doppler-sync-example) | Repository readme | GitHub API, 200 | 2026-09-08 |
| [Papermark PDF workflow](https://github.com/papermark/papermark/blob/main/lib/trigger/pdf-to-image-route.ts) | Source file | GitHub API, 200 | 2026-08-28 |
| [Docker guide](https://trigger.dev/docs/self-hosting/docker) | Documentation page | HTTP GET, 200 | Not applicable |
| [Kubernetes guide](https://trigger.dev/docs/self-hosting/kubernetes) | Documentation page | HTTP GET, 200 | Not applicable |
| [Docker templates](https://github.com/triggerdotdev/docker) | Repository readme | GitHub API, 200 | 2025-11-25 |

## Excluded or superseded candidates

- triggerdotdev/api-reference: historical TriggerClient and eventTrigger examples, not current task APIs.
- Archived basic-starter, cron-basic, and scheduled-healthcheck repositories were excluded.
- triggerdotdev/langsmith-otel-demo explicitly uses legacy telemetry; omitted from the current list.
- Older community Coolify templates were not included without current deployment evidence.

## Updating this record

For a later addition or correction, record the check date, source evidence, and result with the affected entry. Retain the original date for unchanged rows. Link-check failures need investigation: rate limits and access restrictions can occur even when a page exists. Prefer a verified canonical replacement to an unexamined redirect.
