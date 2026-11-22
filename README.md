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

![web](image/alg_I.png) [Addingwell](https://www.addingwell.com/) - Host and monitor server-side Google Tag Manager containers with tag health checks and consent-aware data flows.

![web](image/alg_I.png) [Tagmux](https://tagmux.com/) - Open-source (AGPL) server-side tag manager and proxy for self-hosted measurement.

### Open-Source Tag Managers & Edge

![github](image/alg_R.png) [walkerOS](https://github.com/elbwalker/walkerOS) - Collect, route, and manage events with an open-source tag and consent management system.

![github](image/alg_R.png) [Matomo Tag Manager](https://github.com/matomo-org/tag-manager) - Self-host tag management with server-side capable containers and first-party data collection.

![github](image/alg_R.png) [OSSTag](https://github.com/opentagmanager/osstag) - Self-host an open-source tag manager for collecting and forwarding measurement events.

![github](image/alg_R.png) [TagPiper](https://github.com/analytics-debugger/tagpiper) - Self-host an open-source server-side tag management system for analytics and marketing tags.

![github](image/alg_R.png) [junction](https://github.com/tyssejc/junction) - Run privacy-focused, self-hosted web analytics and tag management.

![github](image/alg_R.png) [ai-tagging-server](https://github.com/analitikisler/ai-tagging-server) - Rust tagging server compatible with Google Tag Manager server container request and response formats.

![github](image/alg_R.png) [Server-side-track](https://github.com/ShuvoGT/Server-side-track) - Open-source platform for hosting a server-side Google Tag Manager container.

![github](image/alg_R.png) [scale8 Tag Manager & Analytics](https://github.com/scale8/scale8-tag-manager-and-analytics) - Self-hosted tag manager and analytics platform (archived).

### Google Tag Manager Clients & Tags

![github](image/alg_R.png) [Stape Data Client](https://github.com/stape-io/data-client) - Receive and parse events sent by the Data Tag in server-side GTM.

![github](image/alg_R.png) [Stape Data Tag](https://github.com/stape-io/data-tag) - Send custom events from a web GTM container to a server container.

![github](image/alg_R.png) [Stape Facebook Conversions API Tag](https://github.com/stape-io/facebook-tag) - Forward server-side GTM events to Meta's Conversions API.

![github](image/alg_R.png) [Stape TikTok Events API Tag](https://github.com/stape-io/tiktok-tag) - Send server-side GTM events to TikTok's Events API.

![github](image/alg_R.png) [Stape LinkedIn Conversion API Tag](https://github.com/stape-io/linkedin-tag) - Send server-side GTM events to LinkedIn's Conversions API.

![github](image/alg_R.png) [Stape Reddit Tag](https://github.com/stape-io/reddit-tag) - Forward server-side GTM events to Reddit's Conversions API.

![github](image/alg_R.png) [Stape Microsoft CAPI Tag](https://github.com/stape-io/microsoft-capi-tag) - Send server-side GTM events to Microsoft Advertising's Conversions API.

![github](image/alg_R.png) [Stape OpenAI CAPI Tag](https://github.com/stape-io/openai-capi-tag) - Forward server-side GTM events to the OpenAI Ads Conversions API.

![github](image/alg_R.png) [Stape Snapchat Tag](https://github.com/stape-io/snapchat-tag) - Send server-side GTM events to Snapchat's Conversions API.

![github](image/alg_R.png) [Stape Pinterest CAPI Tag](https://github.com/stape-io/pinterest-capi-tag) - Map server-side GTM events to Pinterest's Conversions API.

![github](image/alg_R.png) [Stape GA4 Advanced Tag](https://github.com/stape-io/ga4-advanced-tag) - Send GA4 events from a server container with extended parameter control.

![github](image/alg_R.png) [Stape Klaviyo Tag](https://github.com/stape-io/klaviyo-tag) - Forward server-side GTM events to Klaviyo.

![github](image/alg_R.png) [Stape HubSpot Tag](https://github.com/stape-io/hubspot-tag) - Send server-side GTM events to HubSpot.

![github](image/alg_R.png) [Stape Google Customer Match Tag](https://github.com/stape-io/google-customer-match-tag) - Upload hashed customer lists to Google Ads Customer Match from a server container.

![github](image/alg_R.png) [Stape Google Conversion Events Tag](https://github.com/stape-io/google-conversion-events-tag) - Send conversion events to Google advertising products from a server container.

![github](image/alg_R.png) [Stape JSON HTTP Request Tag](https://github.com/stape-io/json-http-request-tag) - Send JSON payloads from a server container to external endpoints.

![github](image/alg_R.png) [Stape Cookie Extender Tag](https://github.com/stape-io/cookie-extender-tag) - Extend first-party cookie lifetimes managed by a server container.

![github](image/alg_R.png) [Stape Cookie Restore Tag](https://github.com/stape-io/cookie-restore-tag) - Restore first-party cookies from server-side storage after browser restrictions clear them.

![github](image/alg_R.png) [Stape User Data Extractor Variable](https://github.com/stape-io/user-data-extractor-variable) - Extract and normalize user data fields for server-side tags and APIs.

![github](image/alg_R.png) [Stape Unique Event ID Variable](https://github.com/stape-io/unique-event-id-variable) - Generate stable event IDs for browser and server event deduplication.

![github](image/alg_R.png) [Stape Event Generator Tag](https://github.com/stape-io/event-generator-tag) - Generate synthetic events in a server container for testing and validation.

![github](image/alg_R.png) [Stape Logger Tag](https://github.com/stape-io/logger-tag) - Log incoming requests and event data from a server container for debugging.

![github](image/alg_R.png) [Stape Spreadsheet Tag](https://github.com/stape-io/spreadsheet-tag) - Write event data from a server container to Google Sheets.

![github](image/alg_R.png) [Stape Firestore Writer Tag](https://github.com/stape-io/firestore-writer-tag) - Store event data from a server container in Cloud Firestore.

![github](image/alg_R.png) [Stape WordPress Plugin](https://github.com/stape-io/gtm-server-side-wordpress-plugin) - Send WordPress and WooCommerce events to a server-side GTM container.

![github](image/alg_R.png) [Stape Magento Module](https://github.com/stape-io/gtm-server-side-magento-module) - Send Magento storefront events to a server-side GTM container.

![github](image/alg_R.png) [Stape Shopify Container Templates](https://github.com/stape-io/shopify-gtm-container-templates) - GTM container templates for Shopify server-side tracking setups.

![github](image/alg_R.png) [Stape GTM Standards](https://github.com/stape-io/gtm-standards) - Documented standards and conventions for server-side GTM implementations.

![github](image/alg_R.png) [Addingwell Meta Conversion API Tag](https://github.com/addingwell/meta-conversion-api-tag) - Forward server-side GTM events to Meta's Conversions API with dual pixel support.

![github](image/alg_R.png) [Addingwell TikTok Conversion API Tag](https://github.com/addingwell/tiktok-conversion-api-tag) - Send server-side GTM events to TikTok's Events API.

![github](image/alg_R.png) [Addingwell Microsoft UET CAPI Tag](https://github.com/addingwell/microsoft-uet-conversion-api-tag) - Forward server-side GTM events to Microsoft Advertising via UET and the Conversions API.

![github](image/alg_R.png) [Addingwell OpenAI Conversion API Tag](https://github.com/addingwell/openai-conversion-api-tag) - Send server-side GTM events to the OpenAI Ads Conversions API.

![github](image/alg_R.png) [Addingwell Pinterest Conversion API Tag](https://github.com/addingwell/pinterest-conversion-api-tag) - Map server-side GTM events to Pinterest's Conversions API.

![github](image/alg_R.png) [Addingwell Snapchat Conversion API Tag](https://github.com/addingwell/snapchat-conversion-api-tag) - Forward server-side GTM events to Snapchat's Conversions API.

![github](image/alg_R.png) [Addingwell LinkedIn Conversion API Tag](https://github.com/addingwell/linkedin-conversion-api-tag) - Send server-side GTM events to LinkedIn's Conversions API.

![github](image/alg_R.png) [Addingwell Awin Conversion API Tag](https://github.com/addingwell/awin-conversion-api-tag) - Forward affiliate conversion events from a server container to Awin.

![github](image/alg_R.png) [Addingwell Data Manager API Conversions Tag](https://github.com/addingwell/data-manager-api-conversions-tag) - Send Google Ads conversions through the Google Ads Data Manager API from a server container.

![github](image/alg_R.png) [Addingwell Monitoring Tag](https://github.com/addingwell/addingwell-monitoring-tag) - Emit container health and tag execution metrics from a server container.

![github](image/alg_R.png) [TAGGRS Data Client](https://github.com/TAGGRS/TAGGRS-Data-Client) - Receive custom webhook events in a server-side GTM container (dormant).

![github](image/alg_R.png) [TAGGRS WordPress Plugin](https://github.com/TAGGRS/taggrs-wordpress) - Send WordPress and WooCommerce events to a server-side GTM container.

![github](image/alg_R.png) [TAGGRS Magento2 Module](https://github.com/TAGGRS/TAGGRS_Magento2) - Send Magento storefront events to a server-side GTM container.

![github](image/alg_R.png) [TAGGRS Click ID Recovery](https://github.com/TAGGRS/taggrs-click-id-recovery) - Recover Google click identifiers (gclid, gbraid, wbraid) after browser storage restrictions.

![github](image/alg_R.png) [TAGGRS Consent State Template](https://github.com/TAGGRS/ConsentStateTemplate) - Capture and forward consent state values into a server container (dormant).

![github](image/alg_R.png) [TAGGRS ChatGPT Ads CAPI Tag](https://github.com/TAGGRS/chatgpt-ads-sgtm-conversion-api) - Forward server-side GTM events to OpenAI Ads conversion endpoints.

![github](image/alg_R.png) [Meta Conversions API Tag for GTM](https://github.com/facebookincubator/ConversionsAPI-Tag-for-GoogleTagManager) - Official Meta tag template for sending events from a server container to the Conversions API.

![github](image/alg_R.png) [Meta Conversions API Client for GTM](https://github.com/facebookincubator/ConversionsAPI-Client-for-GoogleTagManager) - Official Meta client template for claiming and parsing browser requests in a server container (archived).

![github](image/alg_R.png) [Adsmurai Facebook Pixel and CAPI Template](https://github.com/Adsmurai-Google-Tag-Manager-Templates/adsmurai-facebook-pixel-and-conversions-api) - Server-side GTM template that sends Meta Pixel and Conversions API events together.

![github](image/alg_R.png) [Snowplow GTM Server-Side Client](https://github.com/snowplow/snowplow-gtm-server-side-client) - Claim and parse browser requests into Snowplow events inside a server container.

![github](image/alg_R.png) [Snowplow GTM Server-Side Tag](https://github.com/snowplow/snowplow-gtm-server-side-tag) - Forward server container events to Snowplow collectors (dormant).

![github](image/alg_R.png) [Custom Event Parser Client](https://github.com/NHinternesch/gtm-server-client-custom-event-parser) - Generic server client that parses GET and POST payloads into event data (dormant).

![github](image/alg_R.png) [Simo Ahava Public GTM Templates](https://github.com/gtm-templates-simo-ahava/gtm-templates-public) - Community GTM template gallery covering web and server-side use cases.

![github](image/alg_R.png) [Consent Mode Template](https://github.com/gtm-templates-simo-ahava/consent-mode) - GTM template for setting and updating Google Consent Mode values.

![github](image/alg_R.png) [GTM Loader Client](https://github.com/gtm-templates-simo-ahava/gtm-loader) - Server client that loads and serves third-party scripts from the tagging server.

![github](image/alg_R.png) [Catch-all Client](https://github.com/gtm-templates-simo-ahava/catch-all-client) - Server client that claims unmatched HTTP requests for inspection (dormant).

![github](image/alg_R.png) [Cookie Monster Client](https://github.com/gtm-templates-simo-ahava/cookie-monster) - Server client for reading and managing cookies on incoming requests (dormant).

![github](image/alg_R.png) [SHA-256 Hasher Variable](https://github.com/gtm-templates-simo-ahava/sha256-hasher) - Hash user identifiers with SHA-256 for enhanced conversions and CAPI payloads (dormant).

![github](image/alg_R.png) [Preflight Request Template](https://github.com/gtm-templates-simo-ahava/preflight-request) - Handle CORS preflight requests in a server container (dormant).

![github](image/alg_R.png) [Google Consent Parser Template](https://github.com/analytics-debugger/gtm-template-server-side-google-consent-parser) - Parse Google consent signals from incoming requests in a server container.

![github](image/alg_R.png) [Laravel Tag Manager](https://github.com/Label84/laravel-tagmanager) - Send Measurement Protocol and server-side GA4 events from Laravel applications.

![github](image/alg_R.png) [Pinterest Conversion API Server Template](https://github.com/pinterest/ss-gtm-template) - Map server-side GTM events to the Pinterest Conversions API.

![web](image/alg_I.png) [GTM Template Gallery](https://tagmanager.google.com/gallery/) - Browse community and vendor tag, client, and variable templates for web and server containers.

## Event Collection & Customer Data Platforms

*Collectors and analytics platforms for ingesting, processing, and routing behavioral events.*

### Event Pipelines & Collectors

![github](image/alg_R.png) [Snowplow](https://github.com/snowplow/snowplow) - Collect and process structured behavioral events through a configurable data pipeline.

![github](image/alg_R.png) [RudderStack](https://github.com/rudderlabs/rudder-server) - Collect, transform, and route customer events to downstream destinations.

![github](image/alg_R.png) [Jitsu](https://github.com/jitsucom/jitsu) - Ingest and route event streams into analytics destinations.

![github](image/alg_R.png) [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) - Receive, process, and export telemetry through configurable pipelines.

![web](image/alg_I.png) [Segment Sources](https://segment.com/docs/connections/sources/) - Send events from server libraries and cloud sources into Segment connections.

### Analytics Platforms

![github](image/alg_R.png) [PostHog](https://github.com/PostHog/posthog) - Capture product analytics events with a self-hostable analytics platform.

![github](image/alg_R.png) [Matomo](https://github.com/matomo-org/matomo) - Self-host web analytics with configurable data ownership and reporting.

![github](image/alg_R.png) [Plausible Analytics](https://github.com/plausible/analytics) - Analyze website traffic and custom events using a self-hostable analytics platform.

![github](image/alg_R.png) [Umami](https://github.com/umami-software/umami) - Collect website and custom event analytics with a self-hostable platform.

![github](image/alg_R.png) [Ackee](https://github.com/electerious/Ackee) - Track website traffic with a self-hosted, privacy-focused analytics server.

![github](image/alg_R.png) [GoatCounter](https://github.com/arp242/goatcounter) - Self-host web analytics with page views and custom events.

![github](image/alg_R.png) [Fathom Analytics](https://github.com/usefathom/fathom) - Self-host lightweight website analytics with custom event support.

![github](image/alg_R.png) [Shynet](https://github.com/milesmcc/shynet) - Self-host cookieless website analytics for Django applications and static sites.

![github](image/alg_R.png) [Countly](https://github.com/Countly/countly-server) - Self-host product analytics with web, mobile, and server event collection.

![github](image/alg_R.png) [Open Web Analytics](https://github.com/Open-Web-Analytics/Open-Web-Analytics) - Self-host web analytics with heatmaps, sessions, and custom event tracking.

![web](image/alg_I.png) [GA4 BigQuery export](https://support.google.com/analytics/answer/9823238) - Export raw GA4 event data to BigQuery for warehouse-side analysis.

## Conversion APIs & Server SDKs

*Official event ingestion APIs and libraries for sending conversions or analytics events from servers.*

### Conversion & Measurement APIs

![web](image/alg_I.png) [Meta Conversions API](https://developers.facebook.com/docs/marketing-api/conversions-api/) - Send server-side marketing events to Meta for measurement and attribution.

![web](image/alg_I.png) [Meta event deduplication](https://developers.facebook.com/documentation/ads-commerce/conversions-api/deduplicate-pixel-and-server-events) - Match browser and server events with event_id and event_name to avoid double counting.

![web](image/alg_I.png) [Google Analytics Measurement Protocol](https://developers.google.com/analytics/devguides/collection/protocol/ga4) - Send GA4 events directly from servers using HTTP requests.

![web](image/alg_I.png) [TikTok Events API 2.0](https://business-api.tiktok.com/portal/docs/events-api-2.0/v1.3) - Report web, app, offline, and CRM events to TikTok.

![web](image/alg_I.png) [TikTok event deduplication](https://business-api.tiktok.com/portal/docs/event-deduplication/v1.3) - Deduplicate browser pixel and server Events API deliveries with shared event identifiers.

![web](image/alg_I.png) [LinkedIn Conversions API](https://learn.microsoft.com/en-us/linkedin/marketing/integrations/ads-reporting/conversions-api) - Send conversion events and matching identifiers to LinkedIn.

![web](image/alg_I.png) [Snap Conversions API](https://developers.snap.com/marketing-api/Conversions-API) - Send server-side conversion events to Snapchat for campaign measurement.

![web](image/alg_I.png) [Reddit Conversions API](https://business.reddithelp.com/articles/Knowledge/Conversions-API) - Share conversion events with Reddit Ads through a server-to-server connection.

![web](image/alg_I.png) [Pinterest Conversions API](https://developers.pinterest.com/docs/track-conversions/understand-conversions-and-how-to-track-them/) - Send conversion events to Pinterest from server-side integrations.

![web](image/alg_I.png) [Microsoft Advertising Conversions API](https://learn.microsoft.com/en-us/advertising/guides/uet-conversion-api-integration) - Send UET conversion events to Microsoft Advertising from servers with event ID deduplication.

![web](image/alg_I.png) [OpenAI Ads Conversions API](https://developers.openai.com/ads/conversion-tracking) - Report conversion events to OpenAI Ads with batched payloads and shared event IDs.

![web](image/alg_I.png) [Google Ads offline conversions](https://developers.google.com/google-ads/api/docs/conversions/upload-offline) - Upload click conversions with gclid, gbraid, or wbraid and enhanced conversion data.

![web](image/alg_I.png) [Google Ads enhanced conversions for web](https://developers.google.com/google-ads/api/docs/conversions/enhance-conversions) - Send hashed first-party customer data with conversion uploads for better matching.

![web](image/alg_I.png) [Campaign Manager 360 enhanced conversions](https://developers.google.com/doubleclick-advertisers/guides/conversions_ec) - Send hashed user data with Floodlight and CM360 conversion hits.

![web](image/alg_I.png) [Google Ads API client libraries](https://developers.google.com/google-ads/api/docs/client-libs) - Official client libraries for uploading conversions with the Google Ads API.

### Server-Side SDKs

![github](image/alg_R.png) [Meta Business SDK for Node.js](https://github.com/facebook/facebook-nodejs-business-sdk) - Integrate Meta's Marketing API and Conversions API from Node.js.

![github](image/alg_R.png) [Meta Business SDK for Python](https://github.com/facebook/facebook-python-business-sdk) - Integrate Meta's Marketing APIs from Python, including server-side events.

![github](image/alg_R.png) [Meta Business SDK for PHP](https://github.com/meta/facebook-php-business-sdk) - Send Meta Marketing API and Conversions API events from PHP applications.

![github](image/alg_R.png) [Meta Business SDK for Ruby](https://github.com/meta/facebook-ruby-business-sdk) - Send Meta Marketing API and Conversions API events from Ruby applications.

![github](image/alg_R.png) [Meta Business SDK for Java](https://github.com/meta/facebook-java-business-sdk) - Send Meta Marketing API and Conversions API events from Java applications.

![github](image/alg_R.png) [Meta CAPI Param Builder](https://github.com/meta/capi-param-builder) - Build correctly formatted Conversions API parameters for common integrations.

![github](image/alg_R.png) [TikTok Business API SDK](https://github.com/tiktok/tiktok-business-api-sdk) - Send TikTok Events API and Business API requests from server applications.

![github](image/alg_R.png) [Snowplow JavaScript Tracker](https://github.com/snowplow/snowplow-javascript-tracker) - Track Snowplow events from browsers and JavaScript servers.

![github](image/alg_R.png) [Snowplow Python Tracker](https://github.com/snowplow/snowplow-python-tracker) - Send Snowplow events from Python applications.

![github](image/alg_R.png) [Snowplow Go Tracker](https://github.com/snowplow/snowplow-golang-tracker) - Send Snowplow events from Go services and collectors.

![github](image/alg_R.png) [RudderStack Node SDK](https://github.com/rudderlabs/rudder-sdk-node) - Send analytics events from Node.js applications to RudderStack.

![github](image/alg_R.png) [RudderStack Python SDK](https://github.com/rudderlabs/rudder-sdk-python) - Send analytics events from Python applications to RudderStack.

![github](image/alg_R.png) [PostHog Python Library](https://github.com/PostHog/posthog-python) - Capture product analytics events from Python servers and workers.

![github](image/alg_R.png) [Matomo PHP Tracker](https://github.com/matomo-org/matomo-php-tracker) - Track Matomo visits and custom events from PHP applications.

![github](image/alg_R.png) [Google Ads Python Client](https://github.com/googleads/google-ads-python) - Upload offline and enhanced conversions with the official Google Ads API Python client.

![github](image/alg_R.png) [php-ga-measurement-protocol](https://github.com/theiconic/php-ga-measurement-protocol) - Send Google Analytics Measurement Protocol hits from PHP (dormant).

## Debugging, Validation & QA

*Tools for inspecting requests, validating events, and testing measurement pipelines.*

### Event Validation & Tag Debugging

![web](image/alg_I.png) [Google Tag Assistant](https://tagassistant.google.com/) - Inspect Google tags and troubleshoot tag behavior.

![web](image/alg_I.png) [GTM Preview and debug containers](https://support.google.com/tagmanager/answer/6107056) - Debug web container tags, variables, and data layer changes in preview mode.

![web](image/alg_I.png) [GTM server container preview](https://developers.google.com/tag-platform/tag-manager/server-side/debug) - Inspect incoming requests, clients, tags, variables, and outgoing HTTP calls in a server container.

![web](image/alg_I.png) [GA4 DebugView](https://support.google.com/analytics/answer/7201382) - Watch GA4 events in real time with debug mode enabled.

![web](image/alg_I.png) [GA4 Measurement Protocol validation](https://developers.google.com/analytics/devguides/collection/protocol/ga4/validating-events) - Validate Measurement Protocol event payloads against the validation server.

![web](image/alg_I.png) [GA4 Measurement Protocol verification](https://developers.google.com/analytics/devguides/collection/protocol/ga4/verify-implementation) - Verify event delivery with Realtime reports and DebugView.

![web](image/alg_I.png) [Stape debugging and monitoring guide](https://stape.io/blog/guide-to-debugging-and-monitoring-server-side-tracking-configuration) - Configure preview, logging, and monitoring for server-side GTM containers.

![github](image/alg_R.png) [Snowplow Micro](https://github.com/snowplow/snowplow-micro) - Test tracking implementations against a local Snowplow pipeline.

![github](image/alg_R.png) [JSON Schema Test Suite](https://github.com/json-schema-org/JSON-Schema-Test-Suite) - Test JSON Schema validator implementations against a shared test suite.

![github](image/alg_R.png) [Shopify CAPI Validator](https://github.com/lsb11/shopify-capi-validator) - Validate Shopify Conversions API payloads before and after deployment.

### HTTP Inspection & API Testing

![github](image/alg_R.png) [mitmproxy](https://github.com/mitmproxy/mitmproxy) - Inspect and modify HTTP traffic using an intercepting proxy.

![github](image/alg_R.png) [HTTP Toolkit](https://github.com/httptoolkit/httptoolkit) - Intercept, inspect, and debug HTTP and HTTPS traffic from apps and browsers.

![web](image/alg_I.png) [Chrome DevTools Network panel](https://developer.chrome.com/docs/devtools/network/) - Inspect browser requests, response headers, payloads, and timing.

![github](image/alg_R.png) [Mockoon](https://github.com/mockoon/mockoon) - Run local mock HTTP APIs to test event destinations and integrations.

![github](image/alg_R.png) [Bruno](https://github.com/usebruno/bruno) - Create and run API requests and collections for integration testing.

![github](image/alg_R.png) [Newman](https://github.com/postmanlabs/newman) - Run Postman API collections from the command line.

![github](image/alg_R.png) [Grafana k6](https://github.com/grafana/k6) - Load test HTTP endpoints and measure their performance.

## Self-Hosting & Infrastructure

*Deployment guides and infrastructure resources for operating tagging servers and event pipelines.*

### Server Containers & Local Testing

![web](image/alg_I.png) [sGTM Cloud Run setup](https://developers.google.com/tag-platform/tag-manager/server-side/cloud-run-setup-guide) - Provision preview and tagging servers with Google Cloud Run.

![web](image/alg_I.png) [sGTM App Engine setup](https://developers.google.com/tag-platform/tag-manager/server-side/app-engine-setup) - Deploy a tagging server on Google App Engine and map it to a custom domain.

![web](image/alg_I.png) [sGTM manual setup](https://developers.google.com/tag-platform/tag-manager/server-side/manual-setup-guide) - Deploy Google's tagging server container image on your own infrastructure.

![web](image/alg_I.png) [sGTM custom domain](https://developers.google.com/tag-platform/tag-manager/server-side/custom-domain) - Serve the tagging server from a subdomain or same-origin path for first-party cookies.

![github](image/alg_R.png) [local-sgtm](https://github.com/giovaniortolani/local-sgtm) - Run a local server-side GTM container with Docker for development and testing.

![github](image/alg_R.png) [sgtm-cloud-run-shell](https://github.com/sahava/sgtm-cloud-run-shell) - Shell script for provisioning sGTM on Google Cloud Run (dormant).

![web](image/alg_I.png) [Snowplow Micro local setup](https://docs.snowplow.io/docs/testing/snowplow-micro/local/) - Run a local event validation pipeline using Docker or Java.

![github](image/alg_R.png) [PostHog Docker configuration](https://github.com/PostHog/posthog/tree/master/docker) - Explore Docker configuration for PostHog components.

### First-Party Tag Delivery

![web](image/alg_I.png) [Google tag gateway setup guide](https://developers.google.com/tag-platform/tag-manager/gateway/setup-guide) - Serve Google tags and measurement requests from your own domain.

![web](image/alg_I.png) [Serve Google tags first-party](https://developers.google.com/tag-platform/tag-manager/server-side/dependency-serving) - Load gtm.js and gtag.js through a CDN or tagging server instead of Google domains.

![web](image/alg_I.png) [Cloudflare Google tag gateway](https://developers.cloudflare.com/google-tag-gateway/) - Enable first-party Google tag delivery through a Cloudflare zone.

### Infrastructure Modules

![github](image/alg_R.png) [Terraform AWS VPC module](https://github.com/terraform-aws-modules/terraform-aws-vpc) - Provision AWS networking for infrastructure such as event collectors.

## Technical Guides, Privacy & Standards

*Documentation for event architecture, consent handling, schemas, and transport.*

### Server-Side Tagging Guides

![web](image/alg_I.png) [Server-side tagging fundamentals](https://developers.google.com/tag-platform/learn/sst-fundamentals) - Learn server container architecture, deployment, and event flow.

![web](image/alg_I.png) [Send data to server-side Tag Manager](https://developers.google.com/tag-platform/tag-manager/server-side/send-data) - Configure clients and route measurement requests into a server container.

![web](image/alg_I.png) [Server-side tagging APIs](https://developers.google.com/tag-platform/tag-manager/server-side/api) - Reference APIs available to server-side GTM templates.

![web](image/alg_I.png) [Server-side tagging for mobile apps](https://developers.google.com/tag-platform/tag-manager/server-side/server-side-tagging-for-mobile-apps) - Route supported mobile app analytics through a server container.

![web](image/alg_I.png) [Stape server-side tracking guides](https://stape.io/blog/guides) - Step-by-step guides for GA4, ad platforms, CMS, and CRM server-side setups.

![web](image/alg_I.png) [Data Marketing School sGTM guide](https://data-marketing-school.com/en/blog/google-tag-manager/server-side-tagging/) - Tutorial covering server-side GTM architecture and implementation steps.

![web](image/alg_I.png) [Loves Data server-side tagging tutorial](https://www.lovesdata.com/blog/server-side-tagging/) - Introduction to moving tracking from the browser to a server container.

![web](image/alg_I.png) [Simo Ahava's blog](https://www.simonahava.com/) - Technical articles on Google Tag Manager, server-side tagging, and measurement.

### Consent & Data Governance

![web](image/alg_I.png) [Google Consent Mode](https://developers.google.com/tag-platform/security/concepts/consent-mode) - Understand how consent signals affect Google tag behavior.

![web](image/alg_I.png) [Snowplow consent events](https://docs.snowplow.io/docs/events/ootb-data/consent-events/) - Reference event schemas for recording consent preferences and changes.

![github](image/alg_R.png) [IAB GDPR Transparency & Consent Framework](https://github.com/InteractiveAdvertisingBureau/GDPR-Transparency-and-Consent-Framework) - Technical specs and guidelines for the TCF consent string and CMP API.

![web](image/alg_I.png) [Global Privacy Control](https://globalprivacycontrol.org/) - Browser signal and specification for opt-out of data selling and sharing.

![github](image/alg_R.png) [Klaro](https://github.com/kiprotect/klaro) - Open-source consent management library for websites.

![github](image/alg_R.png) [Osano Cookie Consent](https://github.com/osano/cookieconsent) - Open-source cookie consent banner for capturing user preferences.

![github](image/alg_R.png) [Complianz GDPR](https://github.com/complianz/complianz-gdpr) - WordPress consent management plugin with cookie and region scanning.

### Event Schemas & Transport

![github](image/alg_R.png) [CloudEvents specification](https://github.com/cloudevents/spec) - Standardize event metadata and transport across services.

![github](image/alg_R.png) [AsyncAPI specification](https://github.com/AsyncAPI/spec) - Define event-driven APIs and async message contracts.

![web](image/alg_I.png) [JSON Schema](https://json-schema.org/) - Define and validate structured event payload contracts.

![github](image/alg_R.png) [Iglu Central](https://github.com/snowplow/iglu-central) - Browse versioned schemas for Snowplow events and entities.

![web](image/alg_I.png) [HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110.html) - Reference HTTP methods, status codes, caching semantics, and intermediaries.

![web](image/alg_I.png) [HTTP Cookies (RFC 6265)](https://www.rfc-editor.org/rfc/rfc6265) - Reference cookie attributes, scope, and storage behavior used by first-party tagging.

![web](image/alg_I.png) [OpenTelemetry documentation](https://opentelemetry.io/docs/) - Instrument pipelines with traces, metrics, and logs for operational visibility.

## Communities

*Communities for discussing analytics implementation, event collection, and measurement.*

### Forums & Discussion

![web](image/alg_I.png) [Measure Slack](https://join.measure.chat/) - Join practitioners discussing analytics, tagging, attribution, and measurement.

![web](image/alg_I.png) [r/GoogleAnalytics](https://www.reddit.com/r/GoogleAnalytics/) - Discuss Google Analytics implementation, debugging, and reporting.

![web](image/alg_I.png) [r/analytics](https://www.reddit.com/r/analytics/) - Exchange ideas about analytics tools, data engineering, and measurement.

![web](image/alg_I.png) [Snowplow Discourse](https://discourse.snowplow.io/) - Discuss Snowplow event collection, schemas, and pipeline operations.

![web](image/alg_I.png) [Matomo Forum](https://forum.matomo.org/) - Ask questions about Matomo analytics, tag manager, and self-hosting.

![web](image/alg_I.png) [PostHog Forum](https://posthog.com/forum) - Discuss product analytics, event tracking, and PostHog integrations.

![web](image/alg_I.png) [Stack Overflow: google-tag-manager-server-side](https://stackoverflow.com/tags/google-tag-manager-server-side) - Find answers to server-side GTM setup and debugging questions.

## Contributing

Contributions are welcome! See the [contribution guidelines](CONTRIBUTING.md) for submission criteria, entry formatting, and checks.

## License

This list is dedicated to the public domain under [CC0 1.0 Universal](LICENSE). Linked resources retain their own licenses.

[![CC0](https://img.shields.io/badge/CC0-1.0-lightgrey?style=flat-square)](LICENSE)
