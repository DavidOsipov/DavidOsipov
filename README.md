# Hey, I’m David Osipov 👋

I’m a B2B Product Leader and independent security researcher working at the intersection of cybersecurity, AI, open Internet infrastructure, and machine-readable trust.

I’m currently focused on two tracks:

- building and maintaining censorship-resilient Telegram infrastructure with the [Telemt](https://github.com/telemt) community;
- researching security, trust, and metadata failures in large Internet platforms.

I’m credited as the independent researcher behind **CVE-2026-14440**, a Cloudflare Universal SSL / CAA / RFC 8657 vulnerability involving automatic CAA management and end-to-end enforcement of `accounturi` / `validationmethods`.

- CVE: https://www.cve.org/CVERecord?id=CVE-2026-14440
- NVD: https://nvd.nist.gov/vuln/detail/CVE-2026-14440
- GitHub Advisory: https://github.com/advisories/GHSA-vrv9-rjp4-w93c
- Research write-up: https://david-osipov.vision/en/blog/cybersecurity/cloudflare-ssl-mitm-flaw-2026/

I’m also CPO at [The Flip](https://theflip.io), where we work on generative engine optimization, entity-level trust, machine-readable facts, and evidence-backed knowledge infrastructure.

---

## Current focus

### [`telemt/tdlib-obf`](https://github.com/telemt/tdlib-obf)

I created and maintain `tdlib-obf`, a security-hardened fork of TDLib for high-threat network environments.

The project focuses on MTProto traffic masking, anti-DPI transport behavior, and client-side support for censorship-resilient Telegram access. It is designed to work together with the Telemt Rust MTProxy server.

Status: alpha / pre-first official release.

### [`telemt/telemt`](https://github.com/telemt/telemt)

I contribute to `telemt`, a Rust + Tokio MTProxy server for Telegram.

Telemt is a fast, secure, production-oriented MTProxy implementation with a large user and operator community. I help with product direction, community operations, threat modeling, documentation, testing, and ecosystem development.

I’m one of the admins in the Telemt community, which has grown to 21k+ people on Telegram. The main `telemt/telemt` repository has around 5k GitHub stars.

---

## Security research

### CVE-2026-14440 — Cloudflare Universal SSL / CAA / RFC 8657

I discovered and coordinated the disclosure of a Cloudflare Universal SSL issue where automatic CAA management can supersede customer-configured CAA records at query time.

In affected Universal SSL configurations, RFC 8657 `accounturi` and `validationmethods` protections may not be enforced end-to-end. Successful exploitation is non-trivial and requires a strong network position, but the impact can include issuance of a browser-trusted TLS certificate and a man-in-the-middle window against the affected domain.

Official records:

- CVE Program: https://www.cve.org/CVERecord?id=CVE-2026-14440
- NVD: https://nvd.nist.gov/vuln/detail/CVE-2026-14440
- GitHub Advisory: https://github.com/advisories/GHSA-vrv9-rjp4-w93c
- NotCVE historical tracking: https://notcve.org/notcve/NotCVE-2026-0001

---

## Product background

I’ve worked across B2B SaaS, cybersecurity, enterprise software, mobility, and consulting.

Previously, I was Lead Product Manager at [DeskAlerts](https://alert-software.com), where I led the development of a new SaaS suite from scratch, worked with enterprise security requirements, and contributed to product growth.

Earlier roles included:

- Product Ops Analyst at DiDi Global
- Senior Business Analyst at Paragon Consulting
- freelance product and market research work for international companies

My product work usually combines market research, customer discovery, roadmap ownership, technical writing, data analysis, and systems thinking.

---

## Open knowledge and mapping

I care about public knowledge infrastructure.

I contribute to:

- OpenStreetMap and Mapillary
- Wikidata and Wikipedia
- MusicBrainz
- open cybersecurity datasets and anti-phishing communities

Selected public identifiers:

- ORCID: https://orcid.org/0009-0005-2713-9242
- ISNI: https://isni.org/isni/000000051802960X
- VIAF: https://viaf.org/viaf/139173726847611590332
- Website: https://david-osipov.vision

---

## Skills

**Product leadership:** B2B SaaS, roadmap strategy, discovery, market research, enterprise requirements, stakeholder management  
**Cybersecurity:** vulnerability research, TLS/PKI, CAA, CVE coordination, phishing intelligence, threat modeling, OSINT  
**Internet infrastructure:** MTProxy, Telegram transport, DPI resistance, DNS, certificate issuance, routing-risk analysis  
**AI and data:** AI-assisted research, prompt engineering, information extraction, structured metadata, knowledge graphs  
**Web and tooling:** Python, Astro, Tailwind CSS, schema markup, performance optimization, GitHub workflows  
**Languages:** Russian, English, Georgian, French, German


---

## Contact

- Website: https://david-osipov.vision
- LinkedIn: https://linkedin.com/in/david-osipov
- GitHub: https://github.com/DavidOsipov

Verify identity:

- Keyoxide: https://keyoxide.org/wkd/business@david-osipov.vision
- WKD / OpenPGP: https://openpgpkey.david-osipov.vision/.well-known/openpgpkey/david-osipov.vision/hu/pjmzw74d6on6w4o8hhtn9z5agk1cta8n
