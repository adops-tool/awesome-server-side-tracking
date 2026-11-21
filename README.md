[![awesome-lead-generation](image/awesome-server-side-tracking.png)](https://github.com/adops-tool/awesome-server-side-tracking/pulls)

[![animated-line](https://github.com/readme-SVG/animated-line/blob/main/STORAGE/line-svg-3D444D.svg)](https://github.com/readme-SVG/animated-line) <!-- -SVG-Line- -->

A curated collection of tools and technical resources for building reliable, privacy-aware server-side measurement.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg)](LICENSE)

</div>

## Contents

- [Server-Side Tag Managers & Gateways](#server-side-tag-managers--gateways)
- [Open-Source CDPs & Event Collectors](#open-source-cdps--event-collectors)
- [Conversion APIs (CAPI) & Official SDKs](#conversion-apis-capi--official-sdks)
- [Debugging, Validation & QA Tools](#debugging-validation--qa-tools)
- [Self-Hosting & Infrastructure Templates](#self-hosting--infrastructure-templates)
- [Technical Guides, Architecture & Benchmarks](#technical-guides-architecture--benchmarks)
- [Communities](#communities)
- [Contributing](#contributing)
- [License](#license)

## Server-Side Tag Managers & Gateways

- [Google Tag Manager server-side tagging](https://developers.google.com/tag-platform/tag-manager/server-side/overview) - Run server containers that receive, transform, and route measurement events.
- [Cloudflare Zaraz](https://developers.cloudflare.com/zaraz/) - Load and manage third-party tools through Cloudflare's edge network.
- [Stape Data Client](https://github.com/stape-io/data-client) - Receive and parse events sent by the Data Tag in server-side GTM.
- [Stape Data Tag](https://github.com/stape-io/data-tag) - Send custom events from a web GTM container to a server container.
- [Stape Facebook Conversions API Tag](https://github.com/stape-io/facebook-tag) - Forward server-side GTM events to Meta's Conversions API.

## Open-Source CDPs & Event Collectors

- [Snowplow](https://github.com/snowplow/snowplow) - Collect and process structured behavioral events through a configurable data pipeline.
- [RudderStack](https://github.com/rudderlabs/rudder-server) - Collect, transform, and route customer events to downstream destinations.
- [PostHog](https://github.com/PostHog/posthog) - Capture product analytics events with a self-hostable analytics platform.
- [Jitsu](https://github.com/jitsucom/jitsu) - Ingest and route event streams into analytics destinations.
- [Matomo](https://github.com/matomo-org/matomo) - Self-host web analytics with configurable data ownership and reporting.
- [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) - Receive, process, and export telemetry through configurable pipelines.

## Conversion APIs (CAPI) & Official SDKs

- [Meta Conversions API](https://developers.facebook.com/docs/marketing-api/conversions-api/) - Send server-side marketing events to Meta for measurement and attribution.
- [Meta Business SDK for Node.js](https://github.com/facebook/facebook-nodejs-business-sdk) - Integrate Meta's Marketing API and Conversions API from Node.js.
- [Google Analytics Measurement Protocol](https://developers.google.com/analytics/devguides/collection/protocol/ga4) - Send GA4 events directly from servers using HTTP requests.
- [TikTok Events API 2.0](https://business-api.tiktok.com/portal/docs/events-api-2.0/v1.3) - Report web, app, offline, and CRM events to TikTok.
- [LinkedIn Conversions API](https://learn.microsoft.com/en-us/linkedin/marketing/integrations/ads-reporting/conversions-api) - Stream conversion events and matching identifiers to LinkedIn.
- [Snap Conversions API](https://developers.snap.com/api/marketing-api/Conversions-API) - Send server-side conversion events to Snapchat for campaign measurement.
- [Reddit Conversions API](https://business.reddithelp.com/articles/Knowledge/Conversions-API) - Share conversion events with Reddit Ads through a server-to-server connection.

## Debugging, Validation & QA Tools

- [Google Tag Assistant](https://tagassistant.google.com/) - Inspect Google tags and troubleshoot browser-side tag behavior.
- [GA4 Measurement Protocol validation](https://developers.google.com/analytics/devguides/collection/protocol/ga4/verify-implementation) - Verify event delivery with Realtime reports and DebugView.
- [Snowplow Micro](https://github.com/snowplow/snowplow-micro) - Test tracking implementations against a local Snowplow pipeline.
- [mitmproxy](https://github.com/mitmproxy/mitmproxy) - Inspect and modify HTTP traffic using an open-source intercepting proxy.
- [Chrome DevTools Network panel](https://developer.chrome.com/docs/devtools/network/) - Inspect browser requests, response headers, payloads, and timing.
- [JSON Schema](https://json-schema.org/) - Define and validate structured event payload contracts.

## Self-Hosting & Infrastructure Templates

- [sGTM Cloud Run setup](https://developers.google.com/tag-platform/tag-manager/server-side/cloud-run-setup-guide) - Provision preview and tagging servers with Google Cloud Run.
- [sGTM manual setup](https://developers.google.com/tag-platform/tag-manager/server-side/manual-setup-guide) - Deploy Google's tagging server container image on your own infrastructure.
- [Snowplow Micro Docker setup](https://docs.snowplow.io/docs/testing-debugging/snowplow-micro/basic-usage) - Run a local event validation pipeline in Docker.
- [PostHog deployment](https://github.com/PostHog/posthog/tree/master/docker) - Explore Docker configuration for self-hosting PostHog components.
- [Terraform AWS modules](https://github.com/terraform-aws-modules) - Reuse infrastructure modules when provisioning AWS networking and compute for collectors.

## Technical Guides, Architecture & Benchmarks

- [Server-side tagging fundamentals](https://developers.google.com/tag-platform/learn/sst-fundamentals) - Learn server container architecture, deployment, and event flow.
- [Send data to server-side Tag Manager](https://developers.google.com/tag-platform/tag-manager/server-side/send-data) - Configure clients and route measurement requests into a server container.
- [Google Consent Mode](https://developers.google.com/tag-platform/security/concepts/consent-mode) - Understand how consent signals affect Google tag behavior.
- [CloudEvents specification](https://github.com/cloudevents/spec) - Standardize event metadata and transport across services.
- [HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110.html) - Reference HTTP methods, status codes, caching semantics, and intermediaries.
- [OpenTelemetry documentation](https://opentelemetry.io/docs/) - Instrument pipelines with traces, metrics, and logs for operational visibility.

## Communities

- [Measure Slack](https://join.measure.chat/) - Join practitioners discussing analytics, tagging, attribution, and measurement.
- [r/GoogleAnalytics](https://www.reddit.com/r/GoogleAnalytics/) - Discuss Google Analytics implementation, debugging, and reporting.
- [r/analytics](https://www.reddit.com/r/analytics/) - Exchange ideas about analytics tools, data engineering, and measurement.
- [Snowplow Discourse](https://discourse.snowplow.io/) - Discuss Snowplow event collection, schemas, and pipeline operations.

## Contributing

Contributions are welcome! Open a pull request with a verified, publicly accessible resource and a concise technical description. Prefer official documentation and open-source projects; avoid duplicates, affiliate links, and promotional landing pages. Follow the existing list format and place each resource in the most relevant section.

## License

This list is dedicated to the public domain under [CC0 1.0 Universal](LICENSE). Linked resources retain their own licenses.

[![CC0](https://img.shields.io/badge/CC0-1.0-lightgrey?style=flat-square)](LICENSE)
