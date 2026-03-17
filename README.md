# DNS Dev Tool

A full-stack developer DNS analysis suite. Single-file, no backend — runs entirely in the browser using DNS-over-HTTPS.

🔗 **Live**: https://maniax.is/dns-dev-tool

## Features

- 🌳 **Resolution Tree** — animated Root → TLD → Auth NS → Answer chain with D3.js
- 📋 **All Records** — A, AAAA, MX, NS, TXT, CNAME, SOA
- 🗺️ **IP Geolocation** — world map with cloud provider detection & PTR reverse DNS
- 📧 **Email Security** — SPF, DKIM, DMARC analysis with A–F grade
- 🌍 **DNS Propagation** — check across global resolvers
- 🔐 **SSL/TLS Certificates** — cert transparency log, expiry, issuer, SANs
- 📑 **WHOIS Summary** — registrar, creation/expiry dates, registrant country
- 🛡️ **HTTP Security Headers** — CSP, HSTS, X-Frame-Options, Referrer-Policy + A–F grade
- 🔍 **Subdomain Discovery** — 35 common subdomains checked via passive DNS
- 📜 **CAA Records** — which Certificate Authorities can issue certs
- 🔑 **DNSSEC Validation** — DS + DNSKEY record inspection
- 🚫 **Zone Transfer Test** — AXFR security check
- 📤 **Export JSON** — download all findings

## Stack

- Vanilla JS (no framework)
- [D3.js v7](https://d3js.org/) + [TopoJSON](https://github.com/topojson/topojson) for maps
- DNS-over-HTTPS via `dns.google`
- Single self-contained HTML file

## Usage

Just open `dns-dev-tool.html` in any browser — or visit https://maniax.is/dns-dev-tool

No build step, no dependencies to install.
