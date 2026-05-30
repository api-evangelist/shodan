# Shodan (shodan)

Shodan is the world's first search engine for Internet-connected devices. It continuously crawls the public Internet to build a searchable database of servers, IoT devices, industrial control systems, routers, webcams, databases, and any other host that exposes a service. Shodan provides REST, Streaming, and Trends APIs along with on-demand scanning, network alerts, notifiers, DNS lookups, the InternetDB API, and the CVEDB vulnerability database. It is widely used for attack-surface management, security research, threat intelligence, vulnerability discovery, market research, and academic study of the Internet itself.

**URL:** [Visit APIs.json URL](https://developer.shodan.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Security, Search, Internet, Devices, IoT, Vulnerabilities, CVE, Attack Surface, Threat Intelligence, Reconnaissance, Network, DNS, Scanning, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Shodan REST API
The primary Shodan REST API exposes search methods, host lookups, on-demand scanning, network alerts, notifiers, the saved-query directory, DNS lookups, utility methods, account information, bulk data, and organization management. Auth is via the `key` query parameter.

**Human URL:** [https://developer.shodan.io/api](https://developer.shodan.io/api)

#### Tags:

 - REST, Search, Host, Scanning, Alerts, Notifiers, DNS

#### Properties

- [Documentation](https://developer.shodan.io/api)
- [APIReference](https://developer.shodan.io/api)
- [Authentication](https://developer.shodan.io/api/requirements)
- [OpenAPI](openapi/shodan-rest-openapi.yml)
- [JSONSchema (Host)](json-schema/shodan-rest-host-schema.json)
- [JSONSchema (Search Result)](json-schema/shodan-rest-search-result-schema.json)
- [JSONSchema (Alert)](json-schema/shodan-rest-alert-schema.json)
- [JSONSchema (Notifier)](json-schema/shodan-rest-notifier-schema.json)
- [JSONSchema (Scan)](json-schema/shodan-rest-scan-schema.json)
- [JSONStructure (Host)](json-structure/shodan-rest-host-structure.json)
- [JSONStructure (Alert)](json-structure/shodan-rest-alert-structure.json)
- [JSON-LD](json-ld/shodan-context.jsonld)
- [Example (Host Lookup)](examples/shodan-rest-host-lookup-example.json)
- [Example (Search)](examples/shodan-rest-search-example.json)
- [Example (Scan Create)](examples/shodan-rest-scan-create-example.json)
- [Example (Alert Create)](examples/shodan-rest-alert-create-example.json)

### Shodan Streaming API
The Shodan Streaming API provides a real-time firehose of banner data as Shodan collects it. Filtered streams are available by ASN, country, port, and CVE. Output is either newline-separated JSON or Server-Sent Events.

**Human URL:** [https://developer.shodan.io/api/stream](https://developer.shodan.io/api/stream)

#### Tags:

 - Streaming, Real-Time, Firehose, SSE

#### Properties

- [Documentation](https://developer.shodan.io/api/stream)
- [APIReference](https://developer.shodan.io/api/stream)
- [AsyncAPI](asyncapi/shodan-stream-asyncapi.yml)
- [OpenAPI](openapi/shodan-stream-openapi.yml)
- [JSONSchema (Banner)](json-schema/shodan-stream-banner-schema.json)
- [JSONStructure (Banner)](json-structure/shodan-stream-banner-structure.json)
- [Example (Banner)](examples/shodan-stream-banner-example.json)

### Shodan Trends API
Trends is the historical analytics API for Shodan, exposing breakdowns of historical scan results aggregated by facet (product, port, country, organization, etc.) by month. Access is Enterprise-only.

**Human URL:** [https://developer.shodan.io/api/trends](https://developer.shodan.io/api/trends)

#### Tags:

 - Trends, Analytics, Historical, Enterprise

#### Properties

- [Documentation](https://developer.shodan.io/api/trends)
- [APIReference](https://developer.shodan.io/api/trends)
- [OpenAPI](openapi/shodan-trends-openapi.yml)
- [JSONSchema (Result)](json-schema/shodan-trends-result-schema.json)
- [Example (Search)](examples/shodan-trends-search-example.json)

### InternetDB API
The InternetDB API is a free, unauthenticated lookup service that returns the open ports, CPEs, hostnames, tags, and known CVEs for any IPv4 address. The dataset is refreshed once per week. Free for non-commercial use; commercial use requires an enterprise license.

**Human URL:** [https://internetdb.shodan.io/](https://internetdb.shodan.io/)

#### Tags:

 - InternetDB, Free, IP Lookup, Public

#### Properties

- [Documentation](https://internetdb.shodan.io/)
- [OpenAPI](openapi/shodan-internetdb-openapi.yml)
- [JSONSchema (Host)](json-schema/shodan-internetdb-host-schema.json)
- [Example (Host)](examples/shodan-internetdb-host-example.json)

### CVEDB API
CVEDB is Shodan's open vulnerability database API. It provides CVE lookups, CPE-keyed vulnerability search, KEV filtering, EPSS ordering, and date-range queries. No API key required; updated daily. Free for non-commercial use.

**Human URL:** [https://cvedb.shodan.io/](https://cvedb.shodan.io/)

#### Tags:

 - CVE, Vulnerabilities, CPE, KEV, EPSS, Free

#### Properties

- [Documentation](https://cvedb.shodan.io/)
- [OpenAPI](openapi/shodan-cvedb-openapi.yml)
- [JSONSchema (CVE)](json-schema/shodan-cvedb-cve-schema.json)
- [JSONSchema (CPE)](json-schema/shodan-cvedb-cpe-schema.json)
- [Example (CVE Lookup)](examples/shodan-cvedb-cve-lookup-example.json)

## Common Properties

- [Website](https://www.shodan.io/)
- [DeveloperPortal](https://developer.shodan.io/)
- [Documentation](https://developer.shodan.io/)
- [APIReference](https://developer.shodan.io/api)
- [Pricing](https://account.shodan.io/billing)
- [Plans](plans/shodan-plans-pricing.yml)
- [RateLimits](rate-limits/shodan-rate-limits.yml)
- [SignUp](https://account.shodan.io/register)
- [Login](https://account.shodan.io/login)
- [Console](https://www.shodan.io/dashboard)
- [Authentication](https://developer.shodan.io/api/requirements)
- [GettingStarted](https://help.shodan.io/the-basics/what-is-shodan)
- [Quickstart](https://help.shodan.io/the-basics/search-query-fundamentals)
- [Tutorials](https://help.shodan.io/)
- [KnowledgeCenter](https://help.shodan.io/)
- [Glossary](https://datapedia.shodan.io/)
- [Support](mailto:support@shodan.io)
- [Blog](https://blog.shodan.io/)
- [StatusPage](https://status.shodan.io/)
- [TermsOfService](https://www.shodan.io/legal/tos)
- [PrivacyPolicy](https://www.shodan.io/legal/privacy)
- [Legal](https://www.shodan.io/legal)
- [X](https://x.com/shodanhq)
- [LinkedIn](https://www.linkedin.com/company/shodan)
- [YouTube](https://www.youtube.com/@shodanhq)
- [GitHubOrganization](https://github.com/achillean)
- [GitHubRepository (shodan-python)](https://github.com/achillean/shodan-python)
- [GitHubRepository (shodan-developer-docs)](https://github.com/achillean/shodan-developer-docs)
- [GitHubRepository (shodan-ruby)](https://github.com/achillean/shodan-ruby)
- [GitHubRepository (shodan-perl)](https://github.com/achillean/shodan-perl)
- [GitHubRepository (Shodan.NET)](https://github.com/achillean/Shodan.NET)
- [GitHubRepository (steampipe-plugin-shodan)](https://github.com/achillean/steampipe-plugin-shodan)
- [CLI](https://help.shodan.io/command-line-interface/0-installation)
- [SDK - Python](https://github.com/achillean/shodan-python)
- [SDK - Ruby](https://github.com/picatz/shodanz)
- [SDK - PHP](https://github.com/ScadaExposure/Shodan-PHP-REST-API)
- [SDK - C++](https://github.com/prophetl33t/ShodanCPP)
- [SDK - C#](https://www.nuget.org/packages/Shodan/)
- [SDK - C# (alt)](https://github.com/tparnell8/Shodan.Net)
- [SDK - Go](https://github.com/shadowscatcher/shodan)
- [SDK - Go (ns3777k)](https://github.com/ns3777k/go-shodan)
- [SDK - Haskell](https://github.com/iomonad/shodan)
- [SDK - Java](https://github.com/fooock/jshodan)
- [SDK - Node.js](https://github.com/jesusprubio/shodan-client.js)
- [SDK - Perl](https://github.com/Dudley5000/WWW-Shodan-API)
- [SDK - PowerShell](https://github.com/darkoperator/Posh-Shodan)
- [SDK - Rust](https://github.com/femiagbabiaka/shodan-rust)
- [SDK - Crystal](https://github.com/PercussiveElbow/Shodan)
- [Tools - Steampipe Plugin](https://github.com/achillean/steampipe-plugin-shodan)
- [Tools - Shodan Monitor](https://monitor.shodan.io)
- [Tools - Shodan Maps](https://maps.shodan.io)
- [Tools - Shodan Images](https://images.shodan.io)
- [Tools - Shodan Bulk Data](https://enterprise.shodan.io)
- [Tools - Shodan Snippets](https://snippets.shodan.io)
- [Tools - MCP Server (BurtTheCoder)](https://github.com/BurtTheCoder/mcp-shodan)
- [Tools - MCP Server (ADEOSec)](https://github.com/ADEOSec/mcp-shodan)
- [Tools - MCP Server (Cyreslab-AI)](https://github.com/Cyreslab-AI/shodan-mcp-server)
- [Tools - MCP Server (Vorota-ai)](https://github.com/Vorota-ai/shodan-mcp)
- [Tools - MCP Server (mohdhaji87)](https://github.com/mohdhaji87/Shodan-MCP)
- [SpectralRules](rules/shodan-rules.yml)
- [Vocabulary](vocabulary/shodan-vocabulary.yml)
- [FinOps](finops/shodan-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Internet-Wide Device Search | Search billions of indexed banners from servers, routers, webcams, industrial control systems, and IoT devices using a powerful query language with facets and filters. |
| Host Information Lookup | Retrieve all known information for an IP including open ports, service banners, geolocation, ASN/ISP, hostnames, vulnerabilities, SSL/TLS certificates, and detected technologies. |
| On-Demand Scanning | Submit IPs, CIDR ranges, or netblocks for an on-demand crawl using scan credits. Enterprise plans can request Internet-wide scans for a specific port or protocol. |
| Network Alerts and Notifiers | Create alerts on monitored IP ranges that fire when new services, changes, vulnerabilities, or expirations are detected, with delivery via Slack, email, webhook, and other notifier providers. |
| DNS Lookup Suite | Forward, reverse, and full-domain DNS lookups including subdomain enumeration backed by Shodan's passive DNS database. |
| Streaming Firehose | Subscribe to real-time banner data filtered by ASN, country, port, or CVE for SIEMs, data lakes, and bespoke analytics pipelines. |
| Trends Analytics | Run faceted queries against the full historical scan database to analyze product adoption, regional exposure, and changes over time. |
| InternetDB Free Lookup | Open, key-free lookup that returns the open ports, CPEs, tags, and CVEs for any IPv4 address; refreshed weekly. |
| CVEDB Vulnerability Database | Open vulnerability lookup with CPE search, KEV filter, EPSS sorting, and date-range queries. |
| Bulk Data Exports | Enterprise-tier daily and on-demand bulk exports of Shodan's underlying datasets for offline analysis and warehousing. |
| Organization Management | Enterprise organization support for sharing credits and managing members through the API. |
| Saved Query Directory | Browse, search, and tag community-contributed Shodan queries covering common technologies, exposures, and devices. |
| Notifier Providers | Built-in notification provider integrations for Slack, email, Discord, Telegram, webhook, and more. |

## Use Cases

| Name | Description |
|------|-------------|
| Attack Surface Management | Continuously monitor an organization's external attack surface for new services, configuration drift, and vulnerable software. |
| Vulnerability Intelligence | Quantify exposure to specific CVEs across the Internet or a defined customer footprint using CVEDB and the search/trends APIs. |
| Threat Hunting and OSINT | Pivot from IPs, certificates, banners, and ASNs to map adversary infrastructure and discover related hosts. |
| Security Research | Study the distribution of misconfigured services, exposed databases, and emerging IoT ecosystems across the public Internet. |
| Competitive and Market Research | Track adoption of products, web servers, cloud providers, and frameworks across regions and industries using Trends. |
| Regulatory and Compliance Reporting | Demonstrate visibility into externally exposed assets for frameworks that require attack-surface inventories. |
| Insurance Underwriting | Inform cyber-insurance scoring with externally observable evidence of exposed services, vulnerabilities, and hygiene. |
| Incident Response | Triage IPs observed in alerts against Shodan history to determine who they are and what services they expose. |

## Integrations

| Name | Description |
|------|-------------|
| Splunk | Shodan data is widely ingested into Splunk for security analytics via the streaming API and the Splunk add-on ecosystem. |
| Maltego | Shodan transforms for Maltego enable graph-based pivoting on banners, certificates, and IPs. |
| Slack | Notifier integration delivers alert events to Slack channels. |
| Email | Notifier integration delivers alert events to mailboxes. |
| Webhook | Notifier integration posts alert events to arbitrary HTTPS endpoints. |
| Discord | Notifier integration delivers alert events to Discord servers. |
| Telegram | Notifier integration delivers alert events to Telegram chats. |
| Steampipe | Official Steampipe plugin lets you query Shodan host, DNS, and exploit data using standard SQL. |
| Model Context Protocol | Multiple community MCP servers expose Shodan tools to AI assistants including Claude, Cursor, and VS Code. |
| Nmap | Shodan's CLI ships helpers to enrich Nmap scan output with Shodan-derived banner context. |

## Solutions

| Name | Description |
|------|-------------|
| Shodan Monitor | Hosted attack-surface monitoring product built on the network alerts and notifiers APIs. |
| Enterprise Data Feed | Real-time firehose and daily bulk data exports for SOCs, threat intelligence platforms, and academic researchers. |
| InternetDB | Free, unauthenticated host lookup designed for embedding into security tools and dashboards. |
| CVEDB | Free vulnerability database with KEV and EPSS metadata for prioritization workflows. |
| Internet-Wide Scanning | Enterprise-only capability to request a scan of the entire Internet for a specific port or protocol. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Shodan REST API](openapi/shodan-rest-openapi.yml)
- [Shodan Streaming API](openapi/shodan-stream-openapi.yml)
- [Shodan Trends API](openapi/shodan-trends-openapi.yml)
- [Shodan InternetDB API](openapi/shodan-internetdb-openapi.yml)
- [Shodan CVEDB API](openapi/shodan-cvedb-openapi.yml)

### AsyncAPI

- [Shodan Streaming API](asyncapi/shodan-stream-asyncapi.yml)

### JSON Schema

- [Shodan REST Host](json-schema/shodan-rest-host-schema.json)
- [Shodan REST Banner](json-schema/shodan-rest-banner-schema.json)
- [Shodan REST Search Result](json-schema/shodan-rest-search-result-schema.json)
- [Shodan REST Alert](json-schema/shodan-rest-alert-schema.json)
- [Shodan REST Notifier](json-schema/shodan-rest-notifier-schema.json)
- [Shodan REST Scan](json-schema/shodan-rest-scan-schema.json)
- [Shodan Stream Banner](json-schema/shodan-stream-banner-schema.json)
- [Shodan Trends Result](json-schema/shodan-trends-result-schema.json)
- [Shodan InternetDB Host](json-schema/shodan-internetdb-host-schema.json)
- [Shodan CVEDB CVE](json-schema/shodan-cvedb-cve-schema.json)
- [Shodan CVEDB CPE](json-schema/shodan-cvedb-cpe-schema.json)

### JSON Structure

- [Shodan REST Host](json-structure/shodan-rest-host-structure.json)
- [Shodan REST Alert](json-structure/shodan-rest-alert-structure.json)
- [Shodan Stream Banner](json-structure/shodan-stream-banner-structure.json)

### JSON-LD

- [Shodan Context](json-ld/shodan-context.jsonld)

### Examples

- [REST Host Lookup](examples/shodan-rest-host-lookup-example.json)
- [REST Search](examples/shodan-rest-search-example.json)
- [REST Scan Create](examples/shodan-rest-scan-create-example.json)
- [REST Alert Create](examples/shodan-rest-alert-create-example.json)
- [Stream Banner](examples/shodan-stream-banner-example.json)
- [Trends Search](examples/shodan-trends-search-example.json)
- [InternetDB Host](examples/shodan-internetdb-host-example.json)
- [CVEDB CVE Lookup](examples/shodan-cvedb-cve-lookup-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Shodan REST](capabilities/shared/shodan-rest.yaml) - 26 operations for search, host lookup, scanning, alerts, notifiers, DNS, and account management
- [Shodan Streaming](capabilities/shared/shodan-stream.yaml) - 5 operations for the real-time banner firehose (full + ASN/country/port/CVE filters)
- [Shodan InternetDB](capabilities/shared/shodan-internetdb.yaml) - 1 operation for the free unauthenticated IP lookup service
- [Shodan CVEDB](capabilities/shared/shodan-cvedb.yaml) - 3 operations for CVE detail, CVE search, and CPE search

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Attack Surface Monitoring](capabilities/attack-surface-monitoring.yaml) | REST + Streaming | 7 | Security Operations / Attack Surface Manager |
| [Vulnerability Intelligence](capabilities/vulnerability-intelligence.yaml) | CVEDB + REST + Streaming + InternetDB | 7 | Vulnerability Analyst / Threat Intel Team |
| [Internet Asset Discovery](capabilities/internet-asset-discovery.yaml) | REST + InternetDB | 8 | Red Team / M&A Due Diligence / Third-Party Risk |

## Plans

Commercial plans and pricing modeled as API Commons Plans 0.1.

- [Shodan Plans & Pricing](plans/shodan-plans-pricing.yml) - Developer (free), Membership (one-time $49), Freelancer ($69/mo), Small Business ($359/mo), Corporate ($1,099/mo), Enterprise (custom)

## Rate Limits

Request-rate, concurrency, and quota policies modeled as API Commons Rate Limits 0.1.

- [Shodan Rate Limits](rate-limits/shodan-rate-limits.yml) - REST request cap, per-tier query/scan credit quotas, monitored-IP allotments, plus CVEDB/InternetDB fair-use policy

## FinOps

Billing surface aligned to the FinOps Framework / FOCUS data spec.

- [Shodan FinOps](finops/shodan-finops.yml) - FOCUS-mapped subscription + metered allotment model for query credits, scan credits, monitored IPs, REST requests, and streaming connection seconds

## Vocabulary

- [Shodan Domain Vocabulary](vocabulary/shodan-vocabulary.yml) - 39 terms spanning search/scanning/alerting concepts, banner/host/CVE/CPE data primitives, credit accounting, and notifier delivery channels

## Rules

- [Shodan Ruleset](rules/shodan-rules.yml) - 11 Spectral rules enforcing HTTPS-only servers, `key`-named apiKey scheme, Title Case summaries, mandatory tags / operationIds / descriptions, and required 200 responses

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
