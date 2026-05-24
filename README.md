# H3AD-X

**Threat Intelligence Hub**

H3AD-X is the threat intelligence module of the H3AD-SEC portfolio platform. It houses a suite of analyst-focused tools for IOC enrichment, artifact extraction, and deep IP intelligence — all client-side or proxied, no data retention.

Live at: [h3ad-sec.github.io/H3AD-X](https://h3ad-sec.github.io/H3AD-X/)

---

## Tools

### [VERDIKT](https://h3ad-sec.github.io/VERDIKT/)
Bulk IOC enrichment across 6 intelligence sources. Paste IPs, domains, URLs, or hashes and get a consolidated verdict (MALICIOUS / SUSPICIOUS / BENIGN / UNKNOWN) with a normalized risk score, confidence level, and recommended action. Supports BYOK and managed modes.

### [X-VERDIKT](https://h3ad-sec.github.io/X-VERDIKT/)
Deep IOC enrichment across 11+ sources. Two modes: standard enrichment for all IOC types with per-source scoring, and IP Intel mode for full geolocation, ASN, privacy flag, and reputation context per IP. Managed mode only.

### [PARSE-X](https://h3ad-sec.github.io/PARSE-X/)
Artifact extractor from raw text. Paste any incident report, threat intel write-up, log snippet, or email body and extract all relevant forensic artifacts: IPs, domains, URLs, hashes, registry keys, processes, DLLs, CVEs, MITRE ATT&CK techniques, MAC addresses, and ports. Fully client-side, no data leaves the browser.

### [DNSCOPE](https://h3ad-sec.github.io/DNSCOPE/)
Domain and IP infrastructure mapper across 8 sources. Surfaces ASN, passive DNS history, TLS certificates, subdomains, co-hosted domains, cloud provider, CDN, and WAF context. Proxied through serverless functions — no API keys required.

---

## Part of H3AD-SEC

H3AD-X is one module of the [H3AD-SEC](https://h3ad-sec.github.io) platform — a SOC analyst and detection engineering portfolio covering threat intelligence, detection engineering, threat hunting, and incident response tooling.

Other modules: H3AD-DETECT · H3AD-HUNT · H3AD-OPS · H3AD-DF · H3AD-IR

## H3AD-SEC Platform Modules

| Module | Tools |
|--------|-------|
| [H3AD-X](https://h3ad-sec.github.io/H3AD-X/) | X-VERDIKT, PARSE-X, DNSCOPE |
| [H3AD-AI](https://h3ad-sec.github.io/H3AD-AI/) | INSIGHT-AI, QUERYCRAFT-AI, FPLENS-AI, ATTMAP-AI, CHRONO-AI, MALBRIEF-AI |
| [H3AD-DETECT](https://h3ad-sec.github.io/H3AD-DETECT/) | TRACERULES |
| [H3AD-HUNT](https://h3ad-sec.github.io/H3AD-HUNT/) | HYPOS, PIVEX, TRACEPULSE |
| [H3AD-OPS](https://h3ad-sec.github.io/H3AD-OPS/) | QUICKTRACE, SHIFTLOG, PHISHOPS |
| [H3AD-DF](https://h3ad-sec.github.io/H3AD-DF/) | REGSCOPE |
| [H3AD-IR](https://h3ad-sec.github.io/H3AD-IR/) | — |
