<div align="center">

[![awesome-server-side-tracking](image/awesome-server-side-tracking.png)](https://github.com/adops-tool/awesome-server-side-tracking)

[![animated-line](https://github.com/readme-SVG/animated-line/blob/main/STORAGE/line-svg-3D444D.svg)](https://github.com/readme-SVG/animated-line)

A curated collection of tools and technical resources for building reliable, privacy-aware server-side measurement.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg)](LICENSE)

</div>

> Each entry is marked with the kind of resource it is: ![github](image/alg_R.png) open-source repository, ![web](image/alg_I.png) documentation, specification, or hosted tool. Dormant and archived projects are kept when they still explain an architecture — they are labeled as such.

## Contents

- [Server-Side Tag Managers & Gateways](#server-side-tag-managers--gateways)
- [Event Collection & Customer Data Platforms](#event-collection--customer-data-platforms)
- [Conversion APIs & Server SDKs](#conversion-apis--server-sdks)
- [Debugging, Validation & QA](#debugging-validation--qa)
- [Self-Hosting & Infrastructure](#self-hosting--infrastructure)
- [Technical Guides, Privacy & Standards](#technical-guides-privacy--standards)
- [Communities](#communities)
- [Contributing](#contributing)
- [License](#license)

## Server-Side Tag Managers & Gateways

*Platforms and templates for receiving, processing, and forwarding measurement events from server containers and edge environments.*

### Tagging Platforms & Hosting

![web](image/alg_I.png) [Google Tag Manager server-side tagging](https://developers.google.com/tag-platform/tag-manager/server-side/overview) - Run server containers that receive, transform, and route measurement events.

![web](image/alg_I.png) [Cloudflare Zaraz](https://developers.cloudflare.com/zaraz/) - Manage third-party tools and route events through Cloudflare's edge network.

![web](image/alg_I.png) [Stape](https://stape.io/helpdesk/documentation/create-server-container-in-google-tag-manager) - Host and configure server-side Google Tag Manager containers.

![web](image/alg_I.png) [TAGGRS](https://taggrs.io/docs/server-side-tracking/intro) - Host server-side Google Tag Manager containers and manage tracking integrations.

### Google Tag Manager Clients & Tags

![github](image/alg_R.png) [Stape Data Client](https://github.com/stape-io/data-client) - Receive and parse events sent by the Data Tag in server-side GTM.

![github](image/alg_R.png) [Stape Data Tag](https://github.com/stape-io/data-tag) - Send custom events from a web GTM container to a server container.

![github](image/alg_R.png) [Stape Facebook Conversions API Tag](https://github.com/stape-io/facebook-tag) - Forward server-side GTM events to Meta's Conversions API.

![github](image/alg_R.png) [Stape TikTok Events API Tag](https://github.com/stape-io/tiktok-tag) - Send server-side GTM events to TikTok's Events API.

![github](image/alg_R.png) [Stape LinkedIn Conversion API Tag](https://github.com/stape-io/linkedin-tag) - Send server-side GTM events to LinkedIn's Conversions API.

![github](image/alg_R.png) [Stape Reddit Tag](https://github.com/stape-io/reddit-tag) - Forward server-side GTM events to Reddit's Conversions API.

![github](image/alg_R.png) [Pinterest Conversions API Tag](https://github.com/pinterest/ss-gtm-template) - Map server-side GTM events to the Pinterest Conversions API.

## Event Collection & Customer Data Platforms

*Collectors and analytics platforms for ingesting, processing, and routing behavioral events.*

### Event Pipelines & Collectors

![github](image/alg_R.png) [Snowplow](https://github.com/snowplow/snowplow) - Collect and process structured behavioral events through a configurable data pipeline.

![github](image/alg_R.png) [RudderStack](https://github.com/rudderlabs/rudder-server) - Collect, transform, and route customer events to downstream destinations.

![github](image/alg_R.png) [Jitsu](https://github.com/jitsucom/jitsu) - Ingest and route event streams into analytics destinations.

![github](image/alg_R.png) [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) - Receive, process, and export telemetry through configurable pipelines.

### Analytics Platforms

![github](image/alg_R.png) [PostHog](https://github.com/PostHog/posthog) - Capture product analytics events with a self-hostable analytics platform.

![github](image/alg_R.png) [Matomo](https://github.com/matomo-org/matomo) - Self-host web analytics with configurable data ownership and reporting.

![github](image/alg_R.png) [Plausible Analytics](https://github.com/plausible/analytics) - Analyze website traffic and custom events using a self-hostable analytics platform.

![github](image/alg_R.png) [Umami](https://github.com/umami-software/umami) - Collect website and custom event analytics with a self-hostable platform.

## Conversion APIs & Server SDKs

*Official event ingestion APIs and libraries for sending conversions or analytics events from servers.*

### Conversion & Measurement APIs

![web](image/alg_I.png) [Meta Conversions API](https://developers.facebook.com/docs/marketing-api/conversions-api/) - Send server-side marketing events to Meta for measurement and attribution.

![web](image/alg_I.png) [Google Analytics Measurement Protocol](https://developers.google.com/analytics/devguides/collection/protocol/ga4) - Send GA4 events directly from servers using HTTP requests.

![web](image/alg_I.png) [TikTok Events API 2.0](https://business-api.tiktok.com/portal/docs/events-api-2.0/v1.3) - Report web, app, offline, and CRM events to TikTok.

![web](image/alg_I.png) [LinkedIn Conversions API](https://learn.microsoft.com/en-us/linkedin/marketing/integrations/ads-reporting/conversions-api) - Send conversion events and matching identifiers to LinkedIn.

![web](image/alg_I.png) [Snap Conversions API](https://developers.snap.com/marketing-api/Conversions-API) - Send server-side conversion events to Snapchat for campaign measurement.

![web](image/alg_I.png) [Reddit Conversions API](https://business.reddithelp.com/articles/Knowledge/Conversions-API) - Share conversion events with Reddit Ads through a server-to-server connection.

![web](image/alg_I.png) [Pinterest Conversions API](https://developers.pinterest.com/docs/track-conversions/understand-conversions-and-how-to-track-them/) - Send conversion events to Pinterest from server-side integrations.

### Server-Side SDKs

![github](image/alg_R.png) [Meta Business SDK for Node.js](https://github.com/facebook/facebook-nodejs-business-sdk) - Integrate Meta's Marketing API and Conversions API from Node.js.

![github](image/alg_R.png) [Meta Business SDK for Python](https://github.com/facebook/facebook-python-business-sdk) - Integrate Meta's Marketing APIs from Python, including server-side events.

![github](image/alg_R.png) [Snowplow JavaScript Tracker](https://github.com/snowplow/snowplow-javascript-tracker) - Track Snowplow events from browsers and JavaScript servers.

![github](image/alg_R.png) [Snowplow Python Tracker](https://github.com/snowplow/snowplow-python-tracker) - Send Snowplow events from Python applications.

![github](image/alg_R.png) [RudderStack Node SDK](https://github.com/rudderlabs/rudder-sdk-node) - Send analytics events from Node.js applications to RudderStack.

## Debugging, Validation & QA

*Tools for inspecting requests, validating events, and testing measurement pipelines.*

### Event Validation & Tag Debugging

![web](image/alg_I.png) [Google Tag Assistant](https://tagassistant.google.com/) - Inspect Google tags and troubleshoot tag behavior.

![web](image/alg_I.png) [GA4 Measurement Protocol validation](https://developers.google.com/analytics/devguides/collection/protocol/ga4/validating-events) - Validate Measurement Protocol event payloads against the validation server.

![web](image/alg_I.png) [GA4 Measurement Protocol verification](https://developers.google.com/analytics/devguides/collection/protocol/ga4/verify-implementation) - Verify event delivery with Realtime reports and DebugView.

![github](image/alg_R.png) [Snowplow Micro](https://github.com/snowplow/snowplow-micro) - Test tracking implementations against a local Snowplow pipeline.

![github](image/alg_R.png) [JSON Schema Test Suite](https://github.com/json-schema-org/JSON-Schema-Test-Suite) - Test JSON Schema validator implementations against a shared test suite.

### HTTP Inspection & API Testing

![github](image/alg_R.png) [mitmproxy](https://github.com/mitmproxy/mitmproxy) - Inspect and modify HTTP traffic using an intercepting proxy.

![web](image/alg_I.png) [Chrome DevTools Network panel](https://developer.chrome.com/docs/devtools/network/) - Inspect browser requests, response headers, payloads, and timing.

![github](image/alg_R.png) [Mockoon](https://github.com/mockoon/mockoon) - Run local mock HTTP APIs to test event destinations and integrations.

![github](image/alg_R.png) [Bruno](https://github.com/usebruno/bruno) - Create and run API requests and collections for integration testing.

![github](image/alg_R.png) [Newman](https://github.com/postmanlabs/newman) - Run Postman API collections from the command line.

![github](image/alg_R.png) [Grafana k6](https://github.com/grafana/k6) - Load test HTTP endpoints and measure their performance.

## Self-Hosting & Infrastructure

*Deployment guides and infrastructure resources for operating tagging servers and event pipelines.*

### Server Containers & Local Testing

![web](image/alg_I.png) [sGTM Cloud Run setup](https://developers.google.com/tag-platform/tag-manager/server-side/cloud-run-setup-guide) - Provision preview and tagging servers with Google Cloud Run.

![web](image/alg_I.png) [sGTM manual setup](https://developers.google.com/tag-platform/tag-manager/server-side/manual-setup-guide) - Deploy Google's tagging server container image on your own infrastructure.

![web](image/alg_I.png) [Snowplow Micro local setup](https://docs.snowplow.io/docs/testing/snowplow-micro/local/) - Run a local event validation pipeline using Docker or Java.

![github](image/alg_R.png) [PostHog Docker configuration](https://github.com/PostHog/posthog/tree/master/docker) - Explore Docker configuration for PostHog components.

### Infrastructure Modules

![github](image/alg_R.png) [Terraform AWS VPC module](https://github.com/terraform-aws-modules/terraform-aws-vpc) - Provision AWS networking for infrastructure such as event collectors.

## Technical Guides, Privacy & Standards

*Documentation for event architecture, consent handling, schemas, and transport.*

### Server-Side Tagging Guides

![web](image/alg_I.png) [Server-side tagging fundamentals](https://developers.google.com/tag-platform/learn/sst-fundamentals) - Learn server container architecture, deployment, and event flow.

![web](image/alg_I.png) [Send data to server-side Tag Manager](https://developers.google.com/tag-platform/tag-manager/server-side/send-data) - Configure clients and route measurement requests into a server container.

![web](image/alg_I.png) [Server-side tagging APIs](https://developers.google.com/tag-platform/tag-manager/server-side/api) - Reference APIs available to server-side GTM templates.

![web](image/alg_I.png) [Server-side tagging for mobile apps](https://developers.google.com/tag-platform/tag-manager/server-side/server-side-tagging-for-mobile-apps) - Route supported mobile app analytics through a server container.

### Consent & Data Governance

![web](image/alg_I.png) [Google Consent Mode](https://developers.google.com/tag-platform/security/concepts/consent-mode) - Understand how consent signals affect Google tag behavior.

![web](image/alg_I.png) [Snowplow consent events](https://docs.snowplow.io/docs/events/ootb-data/consent-events/) - Reference event schemas for recording consent preferences and changes.

### Event Schemas & Transport

![github](image/alg_R.png) [CloudEvents specification](https://github.com/cloudevents/spec) - Standardize event metadata and transport across services.

![web](image/alg_I.png) [JSON Schema](https://json-schema.org/) - Define and validate structured event payload contracts.

![github](image/alg_R.png) [Iglu Central](https://github.com/snowplow/iglu-central) - Browse versioned schemas for Snowplow events and entities.

![web](image/alg_I.png) [HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110.html) - Reference HTTP methods, status codes, caching semantics, and intermediaries.

![web](image/alg_I.png) [OpenTelemetry documentation](https://opentelemetry.io/docs/) - Instrument pipelines with traces, metrics, and logs for operational visibility.

## Communities

*Communities for discussing analytics implementation, event collection, and measurement.*

### Forums & Discussion

![web](image/alg_I.png) [Measure Slack](https://join.measure.chat/) - Join practitioners discussing analytics, tagging, attribution, and measurement.

![web](image/alg_I.png) [r/GoogleAnalytics](https://www.reddit.com/r/GoogleAnalytics/) - Discuss Google Analytics implementation, debugging, and reporting.

![web](image/alg_I.png) [r/analytics](https://www.reddit.com/r/analytics/) - Exchange ideas about analytics tools, data engineering, and measurement.

![web](image/alg_I.png) [Snowplow Discourse](https://discourse.snowplow.io/) - Discuss Snowplow event collection, schemas, and pipeline operations.

## Contributing

Contributions are welcome! See the [contribution guidelines](CONTRIBUTING.md) for submission criteria, entry formatting, and checks.

## License

This list is dedicated to the public domain under [CC0 1.0 Universal](LICENSE). Linked resources retain their own licenses.

[![CC0](https://img.shields.io/badge/CC0-1.0-lightgrey?style=flat-square)](LICENSE)
