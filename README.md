# Shodan (shodan)

Shodan is the world's first search engine for Internet-connected devices. It continuously crawls the public Internet to build a searchable database of servers, IoT devices, industrial control systems, routers, webcams, databases, and any other host that exposes a service. Shodan provides REST, Streaming, and Trends APIs along with on-demand scanning, network alerts, notifiers, DNS lookups, the InternetDB API, and the CVEDB vulnerability database. It is widely used for attack-surface management, security research, threat intelligence, vulnerability discovery, market research, and academic study of the Internet itself.

**APIs.json:** [https://developer.shodan.io/](https://developer.shodan.io/)

## Tags

- Security
- Search
- Internet
- Devices
- IoT
- Vulnerabilities
- CVE
- Attack Surface
- Threat Intelligence
- Reconnaissance
- Network
- DNS
- Scanning
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Shodan REST API

The primary Shodan REST API exposes search methods, host lookups, on-demand scanning, network alerts, notifiers, the saved-query directory, DNS lookups, utility methods, account information, bulk data, and organization management. Auth is via the `key` query parameter.

- **Human URL:** [https://developer.shodan.io/api](https://developer.shodan.io/api)
- **Base URL:** `https://api.shodan.io`

#### Tags

- REST
- Search
- Host
- Scanning
- Alerts
- Notifiers
- DNS

#### Properties

- [Documentation](https://developer.shodan.io/api)
- [API Reference](https://developer.shodan.io/api)
- [Authentication](https://developer.shodan.io/api/requirements)
- [OpenAPI](openapi/shodan-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shodan-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shodan-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/shodan-rest-host-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shodan-rest-search-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shodan-rest-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shodan-rest-notifier-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shodan-rest-scan-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/shodan-rest-host-structure.json)
- [JSON Structure](json-structure/shodan-rest-alert-structure.json)
- [J S O N- L D](json-ld/shodan-context.jsonld)
- [Example](examples/shodan-rest-host-lookup-example.json)
- [Example](examples/shodan-rest-search-example.json)
- [Example](examples/shodan-rest-scan-create-example.json)
- [Example](examples/shodan-rest-alert-create-example.json)

### Shodan Streaming API

The Shodan Streaming API provides a real-time firehose of banner data as Shodan collects it. Filtered streams are available by ASN, country, port, and CVE. Output is either newline-separated JSON or Server-Sent Events.

- **Human URL:** [https://developer.shodan.io/api/stream](https://developer.shodan.io/api/stream)
- **Base URL:** `https://stream.shodan.io`

#### Tags

- Streaming
- Real-Time
- Firehose
- SSE

#### Properties

- [Documentation](https://developer.shodan.io/api/stream)
- [API Reference](https://developer.shodan.io/api/stream)
- [AsyncAPI](asyncapi/shodan-stream-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [OpenAPI](openapi/shodan-stream-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shodan-stream.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shodan-stream.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/shodan-stream-banner-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/shodan-stream-banner-structure.json)
- [Example](examples/shodan-stream-banner-example.json)

### Shodan Trends API

Trends is the historical analytics API for Shodan, exposing breakdowns of historical scan results aggregated by facet (product, port, country, organization, etc.) by month. Access is Enterprise-only.

- **Human URL:** [https://developer.shodan.io/api/trends](https://developer.shodan.io/api/trends)
- **Base URL:** `https://trends.shodan.io`

#### Tags

- Trends
- Analytics
- Historical
- Enterprise

#### Properties

- [Documentation](https://developer.shodan.io/api/trends)
- [API Reference](https://developer.shodan.io/api/trends)
- [OpenAPI](openapi/shodan-trends-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shodan-trends.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shodan-trends.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/shodan-trends-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/shodan-trends-search-example.json)

### InternetDB API

The InternetDB API is a free, unauthenticated lookup service that returns the open ports, CPEs, hostnames, tags, and known CVEs for any IPv4 address. The dataset is refreshed once per week. Free for non-commercial use; commercial use requires an enterprise license.

- **Human URL:** [https://internetdb.shodan.io/](https://internetdb.shodan.io/)
- **Base URL:** `https://internetdb.shodan.io`

#### Tags

- InternetDB
- Free
- IP Lookup
- Public

#### Properties

- [Documentation](https://internetdb.shodan.io/)
- [OpenAPI](openapi/shodan-internetdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shodan-internetdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shodan-internetdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/shodan-internetdb-host-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/shodan-internetdb-host-example.json)

### CVEDB API

CVEDB is Shodan's open vulnerability database API. It provides CVE lookups, CPE-keyed vulnerability search, KEV filtering, EPSS ordering, and date-range queries. No API key required; updated daily. Free for non-commercial use.

- **Human URL:** [https://cvedb.shodan.io/](https://cvedb.shodan.io/)
- **Base URL:** `https://cvedb.shodan.io`

#### Tags

- CVE
- Vulnerabilities
- CPE
- KEV
- EPSS
- Free

#### Properties

- [Documentation](https://cvedb.shodan.io/)
- [OpenAPI](openapi/shodan-cvedb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shodan-cvedb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shodan-cvedb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/shodan-cvedb-cve-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shodan-cvedb-cpe-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/shodan-cvedb-cve-lookup-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://www.shodan.io/)
- [Developer Portal](https://developer.shodan.io/)
- [Documentation](https://developer.shodan.io/)
- [API Reference](https://developer.shodan.io/api)
- [Pricing](https://account.shodan.io/billing)
- [Plans](plans/shodan-plans-pricing.yml)
- [Rate Limits](rate-limits/shodan-rate-limits.yml)
- [Sign Up](https://account.shodan.io/register)
- [Login](https://account.shodan.io/login)
- [Console](https://www.shodan.io/dashboard)
- [Authentication](https://developer.shodan.io/api/requirements)
- [Getting Started](https://help.shodan.io/the-basics/what-is-shodan)
- [Quickstart](https://help.shodan.io/the-basics/search-query-fundamentals)
- [Tutorials](https://help.shodan.io/)
- [Knowledge Center](https://help.shodan.io/)
- [Glossary](https://datapedia.shodan.io/)
- [Support](mailto:support@shodan.io)
- [Blog](https://blog.shodan.io/)
- [Status Page](https://status.shodan.io/)
- [Terms of Service](https://www.shodan.io/legal/tos)
- [Privacy Policy](https://www.shodan.io/legal/privacy)
- [Legal](https://www.shodan.io/legal)
- [X (Twitter)](https://x.com/shodanhq)
- [LinkedIn](https://www.linkedin.com/company/shodan)
- [YouTube](https://www.youtube.com/@shodanhq)
- [GitHub Organization](https://github.com/achillean)
- [GitHub Repository](https://github.com/achillean/shodan-python)
- [GitHub Repository](https://github.com/achillean/shodan-developer-docs)
- [GitHub Repository](https://github.com/achillean/shodan-ruby)
- [GitHub Repository](https://github.com/achillean/shodan-perl)
- [GitHub Repository](https://github.com/achillean/Shodan.NET)
- [GitHub Repository](https://github.com/achillean/steampipe-plugin-shodan)
- [C L I](https://help.shodan.io/command-line-interface/0-installation)
- [SDK](https://github.com/achillean/shodan-python)
- [SDK](https://github.com/picatz/shodanz)
- [SDK](https://github.com/ScadaExposure/Shodan-PHP-REST-API)
- [SDK](https://github.com/prophetl33t/ShodanCPP)
- [SDK](https://www.nuget.org/packages/Shodan/)
- [SDK](https://github.com/tparnell8/Shodan.Net)
- [SDK](https://github.com/shadowscatcher/shodan)
- [SDK](https://github.com/ns3777k/go-shodan)
- [SDK](https://github.com/iomonad/shodan)
- [SDK](https://github.com/fooock/jshodan)
- [SDK](https://github.com/jesusprubio/shodan-client.js)
- [SDK](https://github.com/Dudley5000/WWW-Shodan-API)
- [SDK](https://github.com/darkoperator/Posh-Shodan)
- [SDK](https://github.com/femiagbabiaka/shodan-rust)
- [SDK](https://github.com/PercussiveElbow/Shodan)
- [Tools](https://github.com/achillean/steampipe-plugin-shodan)
- [Tools](https://monitor.shodan.io)
- [Tools](https://maps.shodan.io)
- [Tools](https://images.shodan.io)
- [Tools](https://enterprise.shodan.io)
- [Tools](https://snippets.shodan.io)
- [Tools](https://github.com/BurtTheCoder/mcp-shodan)
- [Tools](https://github.com/ADEOSec/mcp-shodan)
- [Tools](https://github.com/Cyreslab-AI/shodan-mcp-server)
- [Tools](https://github.com/Vorota-ai/shodan-mcp)
- [Tools](https://github.com/mohdhaji87/Shodan-MCP)
- [Spectral Rules](rules/shodan-rules.yml)
- [Vocabulary](vocabulary/shodan-vocabulary.yml)
- [Fin Ops](finops/shodan-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
