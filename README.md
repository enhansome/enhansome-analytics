# Awesome Analytics with stars

A curated list of awesome analytics platforms, resources and other awesomeness. Inspired by [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata) ⭐ 14,711 | 🐛 0 | 📅 2026-10-30.

Your feedback and contributions are always welcome! Maintained by [@onurakpolat](https://github.com/onurakpolat) & [@koconder](https://github.com/koconder)

Use your browser's search for `Self-Hosted` or `SaaS` to find tagged hosting options.

* [Awesome Analytics](#awesome-analytics)
  * [General analytics](#general-analytics)
  * [Real-time](#real-time)
  * [Website analytics](#website-analytics)
  * [Endpoints](#endpoints)
  * [SEO](#seo)
  * [Privacy focused analytics](#privacy-focused-analytics)
  * [Heatmap analytics](#heatmap-analytics)
  * [Analytics layers](#analytics-layers)
  * [Mobile analytics](#mobile-analytics)
  * [App store analytics](#app-store-analytics)
  * [Attribution tracking](#attribution-tracking)
  * [Social media analytics](#social-media-analytics)
  * [Analytics dashboards](#analytics-dashboards)
  * [Developer analytics](#developer-analytics)

* [Other Awesome Lists](#other-awesome-lists)

## General analytics

**[`^        back to top        ^`](#)**

* [PostHog](https://posthog.com) - Open-source product analytics to track users, events, funnels and trends. Alternative to Mixpanel/Amplitude/Heap. Also includes session recording (alternative to HotJar) and feature flag/experimentation tools (alternative to Optimizely).([Source Code](https://github.com/posthog/posthog) ⭐ 40,524 | 🐛 5,142 | 🌐 Python | 📅 2026-10-30) `MIT` `Python`
* [rrweb](https://rrweb.com) - Open-source session replay library for the browser. Records the DOM and user interactions and replays them pixel-perfect. ([Source Code](https://github.com/rrweb-io/rrweb) ⭐ 20,325 | 🐛 437 | 🌐 TypeScript | 📅 2026-10-30) `MIT` `TypeScript`
* [Druid](http://druid.io/) - Distributed, column-oriented, real-time analytics data store. ([Source Code](https://github.com/druid-io/druid) ⭐ 14,091 | 🐛 780 | 🌐 Java | 📅 2026-10-30) `Apache-2.0` `Java`
* [GrowthBook](https://growthbook.io) - Open-source A/B testing and feature flagging that uses your existing data sources.([Source Code](https://github.com/growthbook/growthbook) ⭐ 8,550 | 🐛 876 | 🌐 TypeScript | 📅 2026-10-30) `MIT` `Typescript`
* [Deepnote](https://deepnote.com/) - Deepnote is a drop-in replacement for Jupyter and an AI-native data workspace for modern data teams. ([GitHub](https://github.com/deepnote/deepnote) ⭐ 3,026 | 🐛 34 | 🌐 TypeScript | 📅 2026-10-30) `Apache-2.0` `©` `SaaS` `TypeScript`
* [Open Web Analytics](http://www.openwebanalytics.com/) - Google Analytics and Matomo alternative. ([Source Code](https://github.com/padams/Open-Web-Analytics) ⭐ 2,695 | 🐛 15 | 🌐 PHP | 📅 2026-10-29) `GPL-2.0` `PHP`
* [Rakam](https://rakam.io/) - Custom analytics platform that lets you to create your own analytics service. Integrate with any data source (web, mobile, IoT etc.), analyze data with SQL and create dashboards. ([Source Code](https://github.com/rakam-io/rakam) ⭐ 789 | 🐛 13 | 🌐 Java | 📅 2021-11-13) `Apache-2.0` `Java`
* [AWStats](http://www.awstats.org/) - Generates web, streaming, ftp or mail server statistics graphically. ([Source Code](https://github.com/eldy/awstats) ⭐ 439 | 🐛 138 | 🌐 Perl | 📅 2025-11-10) `GPL-3.0` `Perl`
* [Edalitics](https://www.edalitics.com) - Open source analytics/BI tool.  ([Source Code](https://github.com/jortilles/EDA) ⭐ 212 | 🐛 9 | 🌐 TypeScript | 📅 2026-10-30) `©` `SaaS` `AGPL-3.0` `Angular/Nodejs`
* [OneQuery](https://github.com/wordbricks/onequery) ⭐ 17 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-30 - Self-hosted gateway for safe, auditable queries for agents across approved data sources. `Apache-2.0` `Self-Hosted` `Rust`
* [stratif.io](https://stratif.io) - Open-source, self-hosted, warehouse-native product analytics. Runs funnels, retention, and path analysis directly on DuckDB, Postgres, Snowflake, or ClickHouse — no ingestion, no SDK. ([Source Code](https://github.com/stratif-io/stratif.io) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-30) `Apache-2.0` `Python/TypeScript`
* [DataSpoc Lens](https://github.com/dataspoclab/dataspoc-lens) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-04-28 - Virtual warehouse over cloud Parquet (S3/GCS/Azure). SQL shell, Jupyter/Marimo notebooks, AI natural language queries, and local cache. ([Source Code](https://github.com/dataspoclab/dataspoc-lens) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-04-28) `Apache-2.0` `Python`
* [Replayowl](https://replayowl.com/) - Open source, self-hosted session replay that runs on Cloudflare Workers or Node. ([Source Code](https://github.com/replayowl/replayowl) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-22) `AGPL-3.0` `TypeScript`
* [Superset-Datafusion](https://github.com/frett27/superset-datafusion) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2025-09-14 - Superset integration for Datafusion
* [UXWizz](https://www.uxwizz.com/) - Self-hosted web analytics with heatmaps, session-recordings, A/B tests and more. `©` `Self-Hosted` `PHP`
* [Panelbear](https://panelbear.com/) - free real-time website analytics. Supports custom event tracking, email digests, and site speed metrics. `©` `SaaS`
* [Hotjar](https://www.hotjar.com/) - new and easy way to truly understand your web and mobile site visitors. `©` `SaaS`
* [Matomo](https://matomo.org/) - Leading open-source analytics platform that gives you more than just powerful analytics, formerly known as Piwik. ([Source Code](https://github.com/matomo-org/)) `GPL-3.0` `PHP`
* [Heap](https://heap.io) - tracks your app users, clicks, form submissions, and anything else. `©` `SaaS`
* [Privatrak](https://privatrak.com/) - Cookieless product analytics with visual event tracking, conversion funnels, and custom dashboards. `©` `SaaS`
* [Opentracker](http://www.opentracker.net/) - real time reporting, geo-location user tracking. `©` `SaaS`
* [FoxMetrics](http://foxmetrics.com/) - analytics to track your user’s actions and activities. `©` `SaaS`
* [Adobe Analytics](https://www.adobe.com/analytics/web-analytics.html) - web data into insights that everyone can act on. `©` `SaaS`
* [Google Analytics](https://www.google.com/analytics/) - de facto standard for analytics in the web analytics space. `©` `SaaS`
* [Screpy](https://screpy.com) - Screpy is a web analyzer and monitoring tool. Its powered by Google Lighthouse. `©` `SaaS`
* [Clicktale](https://www.clicktale.com) - record and watch exactly how a visitor used your website. `©` `SaaS`
* [GoSquared](https://www.gosquared.com/) - analytics with visitor tagging to help you dig deeper into one user’s visit. `©` `SaaS`
* [Clicky](http://clicky.com/) - track visits and conversions, you can also track your video and audio analytics. `©` `SaaS`
* [Woopra](https://www.woopra.com/) - track where your users are coming from. `©` `SaaS`
* [Mint](https://haveamint.com/) - self-hosted analytics solution (no longer on sale).  `©` `SaaS`
* [Going Up](https://www.goingup.com/) - manage SEO analytics and web app analytics with one tool. `©` `SaaS`
* [Chartbeat](https://chartbeat.com/) - beautiful, real-time app analytics tool for web apps. `©` `SaaS`
* [Gauges](http://get.gaug.es/) - real-time web analytics tool. `©` `SaaS`
* [Indicative](https://www.indicative.com/) - Web & mobile analytics tool, with heavy emphasis on segmentation and funnel visualization. `©` `SaaS`
* [Statcounter](https://statcounter.com/) - one of the ORIGINAL web analytics tools available. `©` `SaaS`
* [Adobe Digital Analytics](http://www.adobe.com/data-analytics-cloud/analytics/capabilities.html) - standard analytics tools plus some that large organizations can use. `©` `SaaS`
* [Hitslink.com](https://www.hitslink.com/) - real-time analytics, social media traffic reporting, and real-time dynamic segmentation. `©` `SaaS`
* [parse.ly](https://www.parse.ly) - real-time web analytics tool with a focus on tracking content. `©` `SaaS`
* [Kissmetrics](https://www.kissmetrics.com/) - real-time standard cohort analysis tool. `©` `SaaS`
* [Sitemeter](http://sitemeter.com/) - old analytics tool. `©` `SaaS`
* [Crawl Track](http://www.crawltrack.net/) - another old analytics tool. `©` `SaaS`
* [Sitespect](https://www.sitespect.com/) - full-suite web app analytics tool including A/B testing. `©` `SaaS`
* [Kirro](https://kirro.io/) - A/B testing tool with visual editor and GA4 conversion tracking. 9KB script. `©` `SaaS`
* [ExperimentFlow](https://experimentflow.com) - A/B testing and AI personalisation platform. Features neural bandits, lightweight SDK, privacy-first (no cookies, no PII). Google Optimize alternative. `©` `SaaS`
* [Metabase](https://www.metabase.com) - opensource analytics/BI tool  `©` `SaaS`
* [LiveSession](https://livesession.io) - session replay user analytics. `©` `SaaS`
* [Glassbox](https://glassboxdigital.com/) - customer experince and session recording analytics. `©` `SaaS`
* [Sequential](https://www.usesequential.com/) - session replay and product analytics with an AI judge that reviews each session and lists the findings to fix. `©` `SaaS`
* [Redash](https://redash.io/) - open source analytics/BI tool `©` `SaaS`
* [Countly](https://count.ly) - Real time mobile and web analytics, crash reporting and push notifications platform. ([Source Code](https://github.com/countly)) `AGPL-3.0` `Javascript`
* [Hastic](https://hastic.io) - Hackable time series pattern recognition tool with UI for Grafana. ([Source Code](https://github.com/hastic)) `Apache-2.0` `Python/Nodejs`
* [Count](https://count.co/) - notebook-based analytics platform, use SQL or drag-and-drop to build queries. `©` `SaaS`
* [Datafusion](https://datafusion.apache.org) - Arrow centric - SQL and in memory analytics for general usage
* [FullSession](https://www.fullsession.io/) – Session replay and user behavior analytics for websites
* [StackData](https://greg-rg-git.github.io/stackdata-store/tools/compare/) - Free SaaS pricing comparison tool with pricing data; structured CSV datasets available for bulk analysis. `©` `SaaS`
* [Klinky](https://klinky.io) - A/B testing link shortener that splits one link between two destinations, with click counts. `©` `SaaS`
* [Zoho Apptics](https://www.zoho.com/apptics) – Cross-platfom analytics to monitor performance, analyze user behavior and collect feedback for mobile, web, and desktop apps.
* [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU`

## Real-time

**[`^        back to top        ^`](#)**

* [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal. ([Source Code](https://github.com/allinurl/goaccess) ⭐ 21,099 | 🐛 449 | 🌐 C | 📅 2026-10-28) `GPL-2.0` `C`

* [VisitorPing](https://visitorping.com/) - Live website visitor dashboard with iPhone notifications for incoming visits. `©` `SaaS`

## Website analytics

**[`^        back to top        ^`](#)**

* [Umami](https://umami.is) - Umami is a simple, fast, privacy-focused alternative to Google Analytics. Umami is GDPR compliant. ([Source Code](https://github.com/umami-software/umami) ⭐ 39,804 | 🐛 138 | 🌐 TypeScript | 📅 2026-10-29) `MIT` `JavaScript`

* [KISSS](https://kis3.dev) - Very minimalistic (KISS) website statistics tool. ([Source Code](https://github.com/kis3/kis3)) `MIT` `Go`

* [Vectr4](https://vectr4.com/) - Self-hosted web analytics with funnels and more. `©` `Self-Hosted` `Docker`

* [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU`

* [ShieldLabs](https://shieldlabs.ai) - Traffic quality analytics with bot detection, visitor identification and risk signals by traffic source. ([Anonymity Checker](https://demo.shieldlabs.ai/anonymity-checker)) `©` `SaaS`

## Endpoints

**[`^        back to top        ^`](#)**

* [RudderStack](https://rudderstack.com/) - The warehouse-first customer data platform (CDP) that builds your CDP on your data warehouse for you. RudderStack makes it easy to collect, unify, transform, and store your customer data as well as route it securely to a wide range of common, popular marketing, sales, and product tools (open-source alternative to Segment et al.). ([Source Code](https://github.com/rudderlabs/rudder-server/) ⭐ 4,509 | 🐛 46 | 🌐 Go | 📅 2026-10-30) `AGPL-3.0` `Go`
* [Rawbbit](https://rawbbit.one/) - Self-hosted analytics pipeline that lands raw events as Parquet in your own object storage. Designed for teams that want to own their raw event data instead of feeding it into a SaaS vendor's pipeline. Alternative to Firebase Analytics and Amplitude. ([Source Code](https://github.com/mirlan-irokez/rawbbit) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-24) `Apache-2.0` `Python`
* [Census](https://getcensus.com/) - The easiest way to sync your customer data from your cloud data warehouse to SaaS applications like Salesforce, Marketo, HubSpot, Zendesk, etc. Census is the operational analytics platform that syncs your data warehouse with all your favorite apps. Get your customer success, sales & marketing teams on the same page by keeping customer data in sync. No engineering favors required—just SQL. `SaaS`
* [Snowplow](http://snowplowanalytics.com/) - Analytics tool for web apps with a lot of data. Have every single event, from your websites, mobile apps, desktop applications and server-side systems, stored in your own data warehouse and available to action in real-time. ([Source Code](https://github.com/snowplow/)) `Apache-2.0` `Scala` `real-time`

## SEO

**[`^        back to top        ^`](#)**

* [NotFair](https://github.com/nowork-studio/NotFair) ⭐ 4,087 | 🐛 6 | 🌐 Python | 📅 2026-10-30 - Open-source Claude Code agent skills for SEO, Google Ads, and Meta Ads, connecting to live data via Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP. Covers site audits, keyword research, meta tags, schema markup, GEO optimization, wasted-spend detection, and creative analysis. ([Source Code](https://github.com/nowork-studio/NotFair) ⭐ 4,087 | 🐛 6 | 🌐 Python | 📅 2026-10-30) `MIT`

* [Serposcope](https://serposcope.serphacker.com/) - Serposcope is a free and open-source rank tracker to monitor websites ranking in Google and improve your SEO performances. ([Source Code](https://github.com/serphacker/serposcope) ⚠️ Archived) `MIT` `Java`

* [gsc-hub](https://github.com/izzipizzy/gsc-hub) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-27 - Local self-hosted multi-account hub for Google Search Console: all sites from several Google accounts in one table, aggregated queries and pages, per-site SEO analytics. ([Source Code](https://github.com/izzipizzy/gsc-hub) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-27) `MIT` `Self-Hosted` `TypeScript`

* [AuditorIA](https://landing-five-dusky-44.vercel.app) - Free automated SEO audit for local businesses. Detects HTTPS, meta tags, Schema markup, viewport, and phone visibility in 30 seconds. No registration required. `©` `SaaS`

* [FeedPulse](https://feed-pulse.com) - Free SEO checkers: domain authority, domain rating, SERP position, Google index status, page speed, plus a schema generator. Also serves embeddable traffic and visitor-country widgets. No signup, no paid tier. `©` `SaaS`

* [Vaneform](https://vaneform.com/) - Free website traffic lookup: estimated monthly visits, traffic sources, top countries, search keywords and similar sites for any domain, no signup required. `©` `SaaS`

* [SiteData](https://sitedata.dev/) - website traffic estimation, reverse AdSense lookup, Google Ads advertiser analysis, and Domain Rating lookup. `©` `SaaS`

* [GeoBuddy](https://geobuddy.co/) - AI search analytics: tracks whether ChatGPT, Claude, Gemini and Perplexity mention your brand, with rank, share of voice and competitor tracking; free check without signup.

* [LLM Pulse](https://llmpulse.ai/) - AI search analytics for tracking brand mentions, citations, sentiment, and competitor share of voice across ChatGPT, Perplexity, Gemini, Google AI Overviews, and Google AI Mode. `©` `SaaS`

## Privacy focused analytics

**[`^        back to top        ^`](#)**

* [Umami](https://umami.is/) - Umami is a simple, easy to use, self-hosted web analytics solution. The goal is to provide you with a friendlier, privacy-focused alternative to Google Analytics and a free, open-sourced alternative to paid solutions. ([Demo](https://app.umami.is/share/ISgW2qz8/flightphp.com), [Source Code](https://github.com/mikecao/umami) ⭐ 39,804 | 🐛 138 | 🌐 TypeScript | 📅 2026-10-29) `MIT` `Nodejs`
* [Plausible Analytics](https://plausible.io/) - Lightweight and [open source](https://github.com/plausible-insights/plausible) ⭐ 29,725 | 🐛 52 | 🌐 Elixir | 📅 2026-10-30 web analytics. Doesn’t use cookies and doesn't track personal data. A privacy-friendly alternative to Google Analytics. ([Demo](https://plausible.io/plausible.io), [Source Code](https://github.com/plausible/analytics/) ⭐ 29,725 | 🐛 52 | 🌐 Elixir | 📅 2026-10-30) `AGPL-3.0` `Elixir`
* [Fathom Lite](https://github.com/usefathom/fathom) ⭐ 8,035 | 🐛 5 | 🌐 Go | 📅 2026-03-18 - Fathom Lite, a lightweight version of Fathom Analytics `MIT` `Self-Hosted`
* [GoatCounter](https://www.goatcounter.com/) - GoatCounter is an open source web analytics platform available as a hosted service (free for non-commercial use) or self-hosted app. ([Source](https://github.com/arp242/goatcounter) ⭐ 6,125 | 🐛 51 | 🌐 Go | 📅 2026-09-27, [Demo](https://stats.arp242.net/)) `MIT` `SaaS` `Self-Hosted`
* [Ackee](https://ackee.electerious.com) - Self-hosted analytics tool for those who care about privacy. ([Demo](http://demo.ackee.electerious.com), [Source Code](https://github.com/electerious/Ackee) ⭐ 4,721 | 🐛 23 | 🌐 JavaScript | 📅 2026-10-23) `MIT` `Nodejs`
* [Shynet](https://github.com/milesmcc/shynet) ⭐ 3,156 | 🐛 65 | 🌐 Python | 📅 2026-03-15 - Modern, privacy-friendly, and detailed web analytics that works without cookies or JS. Designed for self-hosting. `Apache-2.0` `Python`
* [Swetrix](https://swetrix.com/) - European OSS product & web analytics, ([Source Code](https://github.com/swetrix/swetrix) ⭐ 1,210 | 🐛 22 | 🌐 TypeScript | 📅 2026-10-29) `MIT`/`AGPL-3.0` `NodeJS`
* [Offen](https://www.offen.dev/) - Offen is a fair and open web analytics tool. Gain insights while your users have full access to their data. Lightweight, self hosted and free. ([Demo](https://www.offen.dev/try-demo/), [Source Code](https://github.com/offen/offen) ⭐ 982 | 🐛 19 | 🌐 JavaScript | 📅 2026-03-04) `Apache-2.0` `Go/Docker`
* [Koko Analytics](https://www.kokoanalytics.com/) - Privacy-friendly and open source analytics plugin for WordPress. ([Source Code](https://github.com/ibericode/koko-analytics/) ⭐ 405 | 🐛 8 | 🌐 PHP | 📅 2026-10-25) `GPL-3.0` `PHP`
* [Freshlytics](https://github.com/sheshbabu/freshlytics) ⭐ 362 | 🐛 27 | 🌐 TypeScript | 📅 2026-02-13 - Privacy respecting, cookie free and low resource usage analytics platform. `MIT` `Docker/Nodejs`
* [Kindmetrics](https://kindmetrics.io/) - Clean privacy-focused website analytics. ([Source Code](https://github.com/kindmetrics/kindmetrics) ⭐ 98 | 🐛 21 | 🌐 Crystal | 📅 2023-01-08) `MIT` `Crystal`
* [piratepx](https://www.piratepx.com/) - Just a little analytics insight for your personal or indie project. 100% free and open source. ([Demo](https://app.piratepx.com/shared/bGQbUJ-YADC_xIGZaYmyqp-J_PD6O1pkCdHmYdIjUvs53ExsImlzFeou4MCuZRbH), [Source](https://github.com/piratepx/app) ⚠️ Archived) `MIT` `Nodejs`
* [Respectlytics](https://respectlytics.com) - Privacy-first, session-based mobile app analytics with strict 5-field storage and no persistent user tracking. ([Source Code](https://github.com/respectlytics/respectlytics) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2026-10-26) `AGPL-3.0` `Python/Docker`
* [Facet](https://github.com/writerslogic/facet) ⭐ 2 | 🐛 18 | 🌐 TypeScript | 📅 2026-10-26 - Cookieless, privacy-first web analytics & experimentation that runs entirely on the Cloudflare edge (Workers + D1). No cookies, no cross-session identity, raw IP is never stored; GPC/DNT respecting and self-hosted with a one-command deploy. `AGPL-3.0` `Cloudflare Workers`
* [Ucoder Insight](https://insights.ucoder.in) - Privacy-first, cookie-free web analytics SDK for developers. 7.4kb gzipped, zero dependencies, offline support via IndexDB. ([Source Code](https://github.com/soumydip/ucoder_insight_core) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28) `MIT` `JavaScript`
* [Stomatopod](https://stoma.top) - Privacy-friendly, cookieless self-hosted web analytics. Single binary, embedded storage, no external DB. ([Source Code](https://github.com/kkir/stomatopod) ⭐ 1 | 🐛 5 | 🌐 Rust | 📅 2026-10-20) `MIT` `Rust/Docker`
* [measuremy.site](https://measuremy.site/) - Cookieless web analytics your AI agent can read: an MCP server lets Claude Code, Cursor and other agents install the script and answer traffic questions. ([Source Code](https://github.com/developeron29/measuremysite-mcp) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-15 for the self-hosted version) `©` `SaaS` `MIT` `Self-Hosted`
* [Lupa](https://getlupa.ru/) - Cookie-free web analytics in a single Go binary with ClickHouse. No stored IPs, daily-rotating visitor hash, goals, funnels, realtime, click heatmaps and session replay with masked inputs. ([Demo](https://demo.getlupa.ru/), [Source Code](https://github.com/cutover-team/lupa) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2026-10-14) `AGPL-3.0` `Go` `Self-Hosted`
* [DevDome Analytics](https://devdome.com/) - Cookieless analytics for WordPress that separates human visitors from bots and AI crawlers. Free plan. ([Plugin Source Code](https://github.com/DevDomeFamily/devdome-analytics) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2026-10-29) `GPL-2.0` `SaaS`
* [Beam](https://beam-privacy.com/) - Lightweight, cookie-free web analytics on Cloudflare Workers and D1. No cookies, no fingerprinting, GDPR-compliant by design. Free tier included. ([Source Code](https://github.com/scobb/beam.js) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-05) `©` `SaaS`
* [Fathom](https://usefathom.com/) - Fathom Analytics provides simple, useful websites stats without tracking or storing personal data of your users `©` `SaaS`
* [Simple Analytics](https://simpleanalytics.io/) - Simple, clean, and friendly analytics for developers `©` `SaaS`
* [Logly](https://logly.uk/) - Cookieless web analytics with a sub-1KB tracker. Bots are counted separately and labelled by type — search engines, AI crawlers, SEO tools, monitors — instead of being filtered out silently. ([Demo](https://app.logly.uk/demo)) `©` `SaaS`
* [Nibspace](https://nibspace.com/) - Affordable, lightweight, privacy-friendly website analytics `©` `SaaS`
* [Metrical](https://metrical.xyz/) - A privacy-first web analytics tool for everyone. `©` `SaaS`
* [Piwik PRO](https://piwik.pro/) - A privacy-friendly alternative to Google Analytics with built-in consent management. Hosted in EU, in your private cloud or on-premises. `©` `SaaS` `Self-Hosted`
* [Rybbit Analytics](https://rybbit.com/) - Rybbit is powerful, lightweight, and super easy to use analytics. Cookieless and GDPR compliant. Hosted on EU infrastructure in Germany. Self-hosting compatible `©` `SaaS` `Self-Hosted` `EU`
* [Clickport](https://clickport.io/) - Privacy-first web analytics without cookies. GDPR compliant, EU-hosted, with session tracking, goals, and real-time dashboard. `©` `SaaS` `EU`
* [PageLens](https://pagelens.io/) - Cookieless, EU-hosted web analytics with revenue by traffic source and AI Visibility: which pages ChatGPT, Claude and Perplexity read, use in answers and send visitors to. ([Demo](https://pagelens.io/demo)) `©` `SaaS` `EU`
* [Lomen](https://lomenanalytics.com/) - Cookie-free website analytics with an AI you can ask about your traffic, revenue from Stripe, Shopify, Lemon Squeezy and Polar next to visitors, and tracking of visits from ChatGPT, Claude and Perplexity. ([Demo](https://lomenanalytics.com/demo)) `©` `SaaS`
* [Statable](https://statable.com/) - Privacy-first, cookieless web analytics hosted in the EU. Import your Google Analytics 4 history and keep a unified timeline. `©` `SaaS` `EU`
* [Measure.events](https://measure.events) - Privacy-first web analytics with an agent-native API, MCP server, and natural language summaries. Built for AI-forward teams. `©` `SaaS`
* [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU`
* [d8a.tech](https://d8a.tech/) - Open-source, GA4/Matomo-compatible analytics. Warehouse-native storage in BigQuery, ClickHouse, or files (CSV/Parquet). Available as EU-hosted cloud or self-hosted. `MIT` `SaaS` `Self-Hosted` `Go/Docker`
* [twelvebit](https://twelvebit.app/) - Privacy-friendly web analytics with revenue attribution: see which channels bring paying customers, with a live globe, funnels, journeys and an MCP server for AI agents. ([Demo](https://twelvebit.app/demo)) `©` `SaaS`

## Heatmap analytics

**[`^        back to top        ^`](#)**

* [Lupa](https://getlupa.ru/) - Self-hosted click heatmaps rendered directly on your page (no iframe), top clicked elements and scroll depth, plus session replay. ([Demo](https://demo.getlupa.ru/), [Source Code](https://github.com/cutover-team/lupa) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2026-10-14) `AGPL-3.0` `Go` `Self-Hosted`
* [Crazyegg](http://www.crazyegg.com/) - a heatmaps only analytics tool. `©` `SaaS`
* [Inspeclet](https://www.inspectlet.com/) - another web app heatmaps tool. `©` `SaaS`
* [Mouseflow](http://mouseflow.com/) - live analytics and heatmaps. `©` `SaaS`
* [Hoot Lens](https://hootlens.com/) - session replay, click heatmaps by device class and broken-click detection, readable by AI coding agents over MCP. `©` `SaaS`
* [Session Cam](http://www.sessioncam.com/) - heatmaps analytics tool. `©` `SaaS`

## Analytics layers

**[`^        back to top        ^`](#)**

* [Keen.io](http://keen.io/) - custom-analytics API. `©` `SaaS`
* [Popcorn Metrics](http://www.popcornmetrics.com/) - visual editor to capture events and send to other platforms. `©` `SaaS`
* [Segment](https://segment.com/) - helps you integrate multiple app analytics tool with one piece of code. `©` `SaaS`
* [Iteratively](https://iterative.ly/) - capture clean product analytics consistently across teams & platforms. `©` `SaaS`
* [Analytics npm package](https://getanalytics.io/) - A lightweight, extendable analytics library designed to work with any third-party analytics provider to track page views, custom events, & identify users. Works in browsers & node.js. `©` `SaaS`

## Mobile analytics

**[`^        back to top        ^`](#)**

The tools listed here are not necessarily mobile analytics tools only. However they show a strong mobile focus.

* [Upsight](http://www.upsight.com/) - mobile app analytics tool for developers. `©` `SaaS`
* [Appsflyer](http://www.appsflyer.com/) - all-in-one marketing tool with analytics. `©` `SaaS`
* [Amazon Pinpoint](https://aws.amazon.com/pinpoint/) - Amazons multi-platform, basic mobile analytics tool. `©` `SaaS`
* [Tapstream](https://tapstream.com/) - user lifecycle analytics. `©` `SaaS`
* [Honeytracks](https://honeytracks.com/) - mobile app analytics for games. `©` `SaaS`
* [Apsalar](https://apsalar.com/) - analytics tool for larger app shops. `©` `SaaS`
* [Roambi](http://www.roambi.com/) - 3-in-1 analytics tool that helps you track analytics, handle mobile app business intelligence, and app reporting. `©` `SaaS`
* [Appcelerator](http://www.appcelerator.com/platform/appcelerator-analytics/) - entire mobile app marketing suite. `©` `SaaS`
* [Flurry](http://www.flurry.com/) - pretty much the “industry standard” for mobile app analytics. `©` `SaaS`
* [Countly](http://count.ly/) - open source mobile & web application analytics tool. `©` `SaaS`
* [Playtomatic](http://playtomic.org/) - mobile app open source analytics tool for games. `©` `SaaS`
* [Capptain](http://www.capptain.com/) - real-time analytics tool with segmentation and push. `©` `SaaS`
* [Amplitude](https://amplitude.com/) - real-time mobile analytics with all data provided in redshift. `©` `SaaS`
* [Appsee](http://www.appsee.com/) - mobile app analytics platform automatically tracks all users' interactions in your app `©` `SaaS`
* [Mixpanel](https://mixpanel.com/) - fully featured mobile analytics platform with segmentation and push. `©` `SaaS`
* [Localytics](http://www.localytics.com/) - fast and beautiful real-time mobile analytics platform with in-app and push. `©` `SaaS`
* [GameAnalytics](http://www.gameanalytics.com/) - leading game analytics platform. `©` `SaaS`
* [Swrve](https://swrve.com) - mobile analytics with segmentation, push, A/B testing and rich messaging `©` `SaaS`
* [Firebase](https://firebase.google.com/features/) - a free and unlimited analytics solution for android and iOS `©` `SaaS`
* [Liquid](https://onliquid.com/) - real-time mobile analytics, personalization, multivariate testing, audience segmentation and push. `©` `SaaS`
* [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU`
* [Apparent](https://apparent.fyi/) - mobile app analytics for iOS and Android makers: live activity from its own SDK plus App Store Connect, Google Play and RevenueCat, all apps on one page. `©` `SaaS`

## App store analytics

**[`^        back to top        ^`](#)**

* [AsoBeast](https://asobeast.com) - Open-source ASO tool and keyword rank tracker for the App Store and Google Play: daily rankings, competitors, reviews and an MCP server. ([Source Code](https://github.com/AsoBeast/asobeast) ⭐ 115 | 🐛 12 | 🌐 TypeScript | 📅 2026-10-30) `AGPL-3.0` `TypeScript` `Self-Hosted` `SaaS`
* [Appfigures](http://appfigures.com/) - app store analytics to track sales, reviews and rankings with an API. `©` `SaaS`
* [Appannie](http://www.appannie.com/) - track your app data from iTunes, Google Play & Amazon. `©` `SaaS`
* [Distimo](http://www.distimo.com/) - free app store analytics (acquired by [Appannie](http://www.appannie.com/)). `©` `SaaS`
* [Priori Data](https://prioridata.com/) - track and benchmark the performance of apps on Apple- and Play store. `©` `SaaS`
* [Asking Point](http://www.askingpoint.com/mobile-app-rating-widget) - track your mobile app user ratings. `©` `SaaS`
* [Apptrace](http://www.apptrace.com/) - fast and free app store analytics platform. `©` `SaaS`
* [AdMapix](https://www.admapix.com/) - AI ad intelligence and app market research platform for searching competitor creatives and tracking app rankings, downloads, and revenue across markets. `©` `SaaS`

## Attribution tracking

**[`^        back to top        ^`](#)**

* [ClickTrail](https://www.npmjs.com/package/@vizuh/clicktrail) - Deterministic first-party attribution engine for UTMs, ad click IDs, referrers, and first/last touch. ([Source Code](https://github.com/vizuh/clicktrail-js) ⭐ 3 | 🐛 19 | 🌐 TypeScript | 📅 2026-10-24) `MIT` `TypeScript`
* [Virling](https://github.com/virling/virling) ⭐ 1 | 🐛 54 | 🌐 Rust | 📅 2026-10-30 - open-source revenue attribution that ties each visit to the Stripe, Dodo Payments or Polar payment that followed. `AGPL-3.0` `Self-Hosted`
* [Adjust](http://adjust.com/) - open-source SDK with sophisticated analysis and campaign tracking. `©` `SaaS`
* [Clickmeter](https://clickmeter.com) - analytics tool that helps you track marketing campaigns. `©` `SaaS`
* [HasOffers Mobile app tracking](http://www.mobileapptracking.com/) - attribution analytics platform. `©` `SaaS`
* [WhichPost](https://whichpost.app/) - See which creator posts brought paying customers, from a read-only Stripe or RevenueCat connection, with a range on every result. `©` `SaaS`
* [OneLence](https://onelence.com/) - Marketing analytics: what to scale, hold or stop across ads, SEO, AI search and affiliates. `©` `SaaS`
* [mbuzz](https://mbuzz.co/) - server-side multi-touch attribution platform with open-source SDKs for Ruby, Node, Python, and PHP, plus a SQL-like attribution DSL. `©` `SaaS`
* [Cascads UTM Builder](https://cascads.com/tools/utm-builder/) - free campaign URL builder for GA4 that lowercases values and builds one tagged link per channel, with nothing leaving the browser. `©` `SaaS`

## Social media analytics

**[`^        back to top        ^`](#)**

Often there is no clear differentiation between social media management and analytics as most the tools provide analytics.

* [Brandwatch](http://www.brandwatch.com/) - Social media monitoring and analytics. `©` `SaaS`
* [Falconsocial](http://www.falconsocial.com/) - communications platform built on social media with analytics. `©` `SaaS`
* [Quintly](https://www.quintly.com/) - web-based tool to help you track, benchmark and optimize your social media performance. `©` `SaaS`
* [Buffer](https://bufferapp.com/) - Social media publishing and analytics platform. `©` `SaaS`
* [Topsy](http://topsy.com/) - Social analytics tool with search. `©` `SaaS`
* [SocialBlade](http://socialblade.com/) - premiere YouTube statistics tracking. `©` `SaaS`
* [Open Channel Stats](https://openchannelstats.com) - Browse real YouTube channels' full owner analytics — retention, CTR, traffic sources — published by the creators themselves, not estimated; connect your own free to compare. Daily refresh; each public channel exports as a documented SQLite file. `©` `SaaS`
* [Hootsuite](https://hootsuite.com/) - Social media management dashbaord. `©` `SaaS`
* [SocialBu](https://socialbu.com/) - AI-powered social media management and analytics platform with scheduling, monitoring, and automation. `©` `SaaS`
* [Sproutsocial](http://sproutsocial.com/) - Social media management and analytics platform. `©` `SaaS`
* [AI TikTok Analyzer Pro](https://tiktok.poviai.com/) - TikTok content research: rank a creator's public videos by engagement, export comments, AI transcripts and sentiment analysis. `©` `SaaS`
* [Pulse](https://pulse.walls.sh) - Social post metrics REST API — give it a public post URL and get back views, likes, comments, shares in JSON. Covers YouTube, X/Twitter, TikTok, Bluesky, Mastodon, Instagram. No API key to start. `Free` `SaaS`
* [IGDataHub](https://igdatahub.com/) - Instagram profile lookup (followers, following, posts) and dated follower readings for the accounts it tracks. `©` `SaaS`
* [SnapDataHub](https://snapdatahub.com/) - Subscriber counts, Spotlight views and growth for public Snapchat creator profiles; earnings figures are estimates. `©` `SaaS`
* [TKMetrics](https://tkmetrics.com/) - TikTok creator reports (average views, engagement rate, posting times) and public hashtag trends. `©` `SaaS`
* [twtData](https://twtdata.com/) - X (Twitter) follower, following and tweet exports to CSV, plus an X trends archive by country. `©` `SaaS`

## Developer analytics

**[`^        back to top        ^`](#)**

* [YYLO Benchmark](https://github.com/yylo-dev/yylo-benchmark) ⭐ 2 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-29 - Trusted-host experiment runner for AI coding agents: replay historical tasks, supplied prompts and workflows as independent attempts in fresh repositories, compare models, harnesses and configurations, and evaluate retained outputs with different checks or judges later. ([Source Code](https://github.com/yylo-dev/yylo-benchmark) ⭐ 2 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-29) `MIT`
* [Dev Ledger](https://devledger.site/) - Open-source GitHub analytics for developers — longitudinal development history across repositories: source growth, churn, activity, languages, and releases. ([Source Code](https://github.com/Aliferous3/dev-ledger) ⭐ 0 | 🐛 5 | 🌐 JavaScript | 📅 2026-10-26) `AGPL-3.0` `SaaS`
* [BitDive](https://bitdive.io/) - APM for Java/Kotlin with distributed tracing, runtime profiling, service maps, and performance metrics. `©` `SaaS`
* [Codeflash](https://www.codeflash.ai/) - Ship Blazing-Fast Python Code — Every Time.
* [GitSpo](https://gitspo.com/) - Analytics for Open-Source. `©` `SaaS`
* [Hatica](https://www.hatica.io/) - Engineering Analytics to boost developer productivity `©` `SaaS`
* [Haystack](https://usehaystack.io) - Metrics and insights for engineering teams `©` `SaaS`
* [LogBrew](https://logbrew.co/) - Error tracking, logs, traces, metrics and product events for apps, with a free plan and an MCP server for AI coding agents. `©` `SaaS`
* [Moiva.io](https://moiva.io/) - A dashboard with charts and graphs to evaluate and compare any npm package. `©` `SaaS`
* [Plandek](https://plandek.com) - Metrics and insights for software delivery `©` `SaaS`
* [Screenful](https://screenful.com/) - Visualise and share your project progress `©` `SaaS`

## Analytics dashboards

**[`^        back to top        ^`](#)**

* [Superset](http://superset.apache.org/) - Modern, enterprise-ready business intelligence web application. ([Source Code](https://github.com/apache/incubator-superset) ⭐ 75,370 | 🐛 598 | 🌐 Python | 📅 2026-10-30) `Apache-2.0` `Python`
* [Metabase](https://metabase.com/) - Metabase is the easy, open source way for everyone in your company to ask questions and learn from data. Simple Dashboarding and GUI Query tool, Nightly Emails and Slack Integration w/ PostgreSQL, MySQL, Redshift and other DBs. ([Source Code](https://github.com/metabase/metabase) ⭐ 50,022 | 🐛 4,647 | 🌐 Clojure | 📅 2026-10-30) `AGPL-3.0` `Java`
* [Redash](http://redash.io) - connect to over 18 types of databases (SQL and "NoSQL"), query your data, visualize it and create dashboards. Everything has a URL that can be shared. Slack and HipChat integration. ([Demo](https://demo.redash.io), [Source Code](https://github.com/getredash/redash) ⭐ 28,853 | 🐛 786 | 🌐 TypeScript | 📅 2026-10-30) `BSD-2-Clause` `Python`
* [Freeboard](https://github.com/Freeboard/freeboard) ⭐ 6,501 | 🐛 166 | 🌐 JavaScript | 📅 2023-09-23 - open source real-time dashboard builder for IOT and other web mashups. `©` `SaaS`
* [Chartbrew](https://chartbrew.com) - Chartbrew allows you to query your databases and APIs to create live charts and visualize your data. Featuring automatic chart updates, sharing, embedding, printing, exporting, and team support with granular permissions. ([Demo](https://app.chartbrew.com/live-demo), [Source Code](https://github.com/chartbrew/chartbrew) ⭐ 4,064 | 🐛 2 | 🌐 JavaScript | 📅 2026-10-29) `MIT` `NodeJS` `SaaS` `Self-Hosted`
* [Socioboard](https://socioboard.org/) - `⚠` Social media management, analytics, and reporting platform supporting nine social media networks out-of-the-box. ([Source Code](https://github.com/socioboard/Socioboard-4.0) ⭐ 1,525 | 🐛 40 | 🌐 JavaScript | 📅 2026-10-29) `GPL-3.0` `C#/JavaScript`
* [DAC](https://getbruin.com/docs/dac/) - dashboard-as-code tool that defines dashboards in YAML and TSX, with a built-in semantic layer for metrics and dimensions. ([Source Code](https://github.com/bruin-data/dac) ⭐ 801 | 🐛 11 | 🌐 Go | 📅 2026-10-29) `AGPL-3.0` `Go` `Self-Hosted`
* [Edalitics](https://www.edalitics.com) - Open source analytics/BI tool.  ([Source Code](https://github.com/jortilles/EDA) ⭐ 212 | 🐛 9 | 🌐 TypeScript | 📅 2026-10-30) `©` `SaaS` `AGPL-3.0` `Angular/Nodejs`
* [DataPallas](https://github.com/flowkraft/datapallas) ⭐ 81 | 🐛 29 | 🌐 TypeScript | 📅 2026-10-30 - Business intelligence platform with interactive dashboards, pivot tables and pixel-perfect report generation. `SSPL-1.0` `Source Available`
* [GoatCounter Dashboard](https://github.com/abhishekhsingh/goatcounter-dashboard) ⭐ 15 | 🐛 0 | 🌐 HTML | 📅 2026-07-21 - Modern analytics dashboard for GoatCounter with interactive charts, choropleth world map, and demo mode. Single HTML file, no build step, no server. ([Demo](https://abhishekhsingh.github.io/goatcounter-dashboard), [Source Code](https://github.com/abhishekhsingh/goatcounter-dashboard) ⭐ 15 | 🐛 0 | 🌐 HTML | 📅 2026-07-21) `MIT` `JavaScript`
* [Geckoboard](https://www.geckoboard.com/) - dashboard for key metrics in one place. `©` `SaaS`
* [Grafana](https://grafana.com/) -  open source dashboard for displaying metrics.([Grafana dashboard inspiration](https://logit.io/blog/post/the-top-21-grafana-dashboards-and-visualisations))
* [Klipfolio](https://www.klipfolio.com/) - Klipfolio is an online dashboard platform for building powerful real-time business dashboards for your team or your clients. `©` `SaaS`
* [Vizia](https://www.brandwatch.com/products/vizia/) - Visual command center dashboarding solution `©` `SaaS`
* [Conyso Lens](https://conyso.com/lens.html?utm_source=github\&utm_medium=directory\&utm_campaign=listing) - General-purpose data-visualization studio: point it at any dataset and get publication-quality charts across 112 chart types, each with a plain-English, rule-based read (never AI-generated). Runs entirely in the browser; nothing you load ever leaves it. Self-host option available. `©` `SaaS` `Self-Hosted`

- [AppRankly](https://github.com/zmsp/AppRankly) ⭐ 28 | 🐛 3 | 🌐 JavaScript | 📅 2026-10-15 - Self-hosted dashboard bringing together iOS App Store Connect and Google Play Console metrics.

* [GeoSQL](https://github.com/dekart-xyz/geosql) ⭐ 682 | 🐛 1 | 🌐 Python | 📅 2026-10-09 - AI-native geospatial analytics. Claude/Codex skill that turns natural language into validated SQL + maps on BigQuery and Snowflake. `MIT` `Python`
* [Dekart](https://dekart.xyz) - Open-source geospatial analytics. Turn SQL on BigQuery/Snowflake/PostGIS into shareable interactive maps. ([Source Code](https://github.com/dekart-xyz/dekart) ⭐ 437 | 🐛 34 | 🌐 JavaScript | 📅 2026-10-23) `AGPL-3.0` `Go` `Self-Hosted` `SaaS`
* [DataHub Pro](https://www.datahubpro.co.uk/) - AI analytics for spreadsheets: turn an Excel or CSV file into dashboards, forecasts and reports, with an audit trail for every number. Built for small teams without a data engineer. `SaaS`
* [Better Analyst](https://betteranalyst.com/) - AI data analyst that connects GA4, Sheets, SQL and BigQuery, answers questions in plain English with the SQL/Python shown, and builds dashboards and scheduled reports. `©` `SaaS`

# Other Awesome Lists

* Even more lists [awesome](https://github.com/sindresorhus/awesome) ⭐ 527,414 | 🐛 105 | 📅 2026-09-02.
* Other awesome lists [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,757 | 🐛 65 | 🌐 Ruby | 📅 2024-06-02.
* Analytics [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata) ⭐ 14,711 | 🐛 0 | 📅 2026-10-30.
* Another list? [list](https://github.com/jnv/lists) ⭐ 11,614 | 🐛 4 | 📅 2026-10-29.
* WTF! [awesome-awesome-awesome](https://github.com/t3chnoboy/awesome-awesome-awesome) ⭐ 2,292 | 🐛 5 | 📅 2023-11-13.

# Resources and Comparisons

* [Analytics Compare](https://www.analytics-compare.com/tools/compare/) - An independent, interactive database comparing 30+ analytics tools based on features, hidden costs, and scalability risks.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-30._
