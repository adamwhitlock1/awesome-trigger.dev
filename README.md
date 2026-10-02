# Awesome Trigger.dev [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Trigger.dev workflows, agent examples, integrations, and self-hosting resources.

[![License: CC0 1.0](https://img.shields.io/badge/license-CC0_1.0-blue.svg)](LICENSE)

[Trigger.dev](https://trigger.dev/) runs durable tasks and workflows with retries, scheduling, and realtime updates. This list organizes working examples by the problem they solve, including AI orchestration, document processing, and deployment.

An independent community list. **Official** identifies resources maintained by the project team; **Integration** identifies documentation or examples maintained by an integrating project; **Community** identifies third-party work.

## Contents

- [Start here](#start-here)
- [AI and agents](#ai-and-agents)
- [Human approval and realtime interfaces](#human-approval-and-realtime-interfaces)
- [Browsers, documents, and images](#browsers-documents-and-images)
- [Integrations](#integrations)
- [Community implementations](#community-implementations)
- [Self-hosting](#self-hosting)
- [Compatibility](#compatibility)
- [Contributing](#contributing)
- [License](#license)

## Start here

- [Trigger.dev source](https://github.com/triggerdotdev/trigger.dev) - Platform source, SDK packages, and release history. **Official.**
- [Introduction](https://trigger.dev/docs/introduction) - Learn the task model and development workflow. **Official.**
- [SDK reference projects](https://github.com/triggerdotdev/references) - Reference projects using published SDK packages and build extensions. **Official.**

## AI and agents

- [Agent workflow patterns](https://github.com/triggerdotdev/examples/tree/main/building-effective-agents) - Prompt chaining, routing, parallelization, and orchestrator patterns. **Official.**
- [Claude Agent SDK](https://github.com/triggerdotdev/examples/tree/main/claude-agent-sdk-trigger) - Run Claude Agent SDK work inside a task. **Official.**
- [Mastra agents](https://github.com/triggerdotdev/examples/tree/main/mastra-agents) - Use Mastra agents with task orchestration. **Official.**
- [Batch LLM evaluator](https://github.com/triggerdotdev/examples/tree/main/batch-llm-evaluator) - Batch evaluation with the AI SDK and realtime output. **Official.**

## Human approval and realtime interfaces

- [Article summary workflow](https://github.com/triggerdotdev/examples/tree/main/article-summary-workflow) - Review AI summaries through waitpoints and a React Flow interface. **Official.**
- [Realtime CSV importer](https://github.com/triggerdotdev/examples/tree/main/realtime-csv-importer) - Process uploaded CSV data with visible progress. **Official.**

## Browsers, documents, and images

- [Python Crawl4AI](https://github.com/triggerdotdev/examples/tree/main/python-crawl4ai) - Run browser crawling with Python and Playwright. **Official.**
- [Document-to-Markdown converter](https://github.com/triggerdotdev/examples/tree/main/python-doc-to-markdown-converter) - Convert documents with Python and MarkItDown. **Official.**
- [PDF form extractor](https://github.com/triggerdotdev/examples/tree/main/python-pdf-form-extractor) - Extract form data with PyMuPDF. **Official.**
- [Python image processing](https://github.com/triggerdotdev/examples/tree/main/python-image-processing) - Process images with Pillow and upload the results. **Official.**

## Integrations

- [Supabase Edge Functions](https://github.com/triggerdotdev/examples/tree/main/supabase-edge-functions) - Trigger tasks from functions and database changes. **Official.**
- [Remix webhooks](https://github.com/triggerdotdev/examples/tree/main/remix-webhooks) - Start tasks from incoming webhooks. **Official.**
- [Doppler secret synchronization](https://github.com/triggerdotdev/trigger-doppler-sync-example) - Proof of concept for syncing Doppler secrets at deploy time and through webhooks. **Official.**

## Community implementations

- [Papermark PDF workflow](https://github.com/papermark/papermark/blob/main/lib/trigger/pdf-to-image-route.ts) - Document-conversion task routing in a larger document-sharing application. **Community.**

## Self-hosting

- [Docker guide](https://trigger.dev/docs/self-hosting/docker) - Deploy the platform with the current Docker self-hosting instructions. **Official.**
- [Kubernetes guide](https://trigger.dev/docs/self-hosting/kubernetes) - Deploy with the official Helm-based setup. **Official.**
- [Docker templates](https://github.com/triggerdotdev/docker) - Docker configuration source; use the current guide when instructions differ. **Official.**

## Compatibility

Use the current SDK and self-hosting documentation. Older v1 and v2 integration examples use different APIs. Most entries here are official examples because the maintained reference collection is substantial; Papermark provides an independent implementation to inspect.

Links and source descriptions were reviewed on October 2, 2026. [Verification notes](VERIFICATION.md) record the checks and exclusions. Linked applications were not installed or run as part of this review.

## Contributing

We prefer runnable source, clear workflow boundaries, and documented deployment paths. An API client alone is not a Trigger.dev integration. Proofs of concept are labeled, and obsolete job templates are excluded.

Read the [contribution guide](CONTRIBUTING.md), then open a pull request with one resource and a short explanation of what it adds. Corrections, broken-link reports, and removal requests are welcome. Participation follows the [code of conduct](CODE_OF_CONDUCT.md).

## License

This list and its original descriptions are dedicated to the public domain under [CC0 1.0](LICENSE). Linked projects, documentation, and trademarks retain their own licenses and ownership.
