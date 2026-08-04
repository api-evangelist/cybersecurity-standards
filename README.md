# Cybersecurity Standards (cybersecurity-standards)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cybersecurity Standards captures the public, machine-readable, and reference frameworks that establish best practices for protecting information systems, networks, software, and data from cyber threats. The landscape is anchored by NIST publications (CSF 2.0, SP 800-53, 800-171, 800-218 SSDF, RMF), ISO/IEC 27001 / 27002, the CIS Critical Security Controls and Benchmarks, OWASP Top 10 and ASVS, PCI DSS, HITRUST CSF, SOC 2 Trust Services Criteria, and FedRAMP / StateRAMP cloud authorizations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cybersecurity-standards/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Reference
- **Access:** 3rd-Party
- **x-type:** topic

## Tags

- CIS Controls, Compliance, CSF, Cybersecurity, FedRAMP, Frameworks, HIPAA, HITRUST, Information Security, ISO 27001, ISO 27002, NIST, NIST 800-171, NIST 800-218, NIST 800-53, OSCAL, OWASP, PCI DSS, Risk Management, SOC 2, SSDF, Standards

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs / Standards

### NIST Cybersecurity Framework (CSF) 2.0

Voluntary risk-based framework organizing cybersecurity activities into six core functions (Govern, Identify, Protect, Detect, Respond, Recover).

- **Human URL:** https://www.nist.gov/cyberframework

### NIST SP 800-53 Security and Privacy Controls (Rev. 5)

Catalog of security and privacy controls used as the basis of FedRAMP and RMF. Available in machine-readable OSCAL.

- **Human URL:** https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final

### NIST SP 800-171 Protecting CUI

Requirements for protecting Controlled Unclassified Information in non-federal systems. Foundation of CMMC.

- **Human URL:** https://csrc.nist.gov/publications/detail/sp/800-171/rev-3/final

### NIST SP 800-218 SSDF

Secure Software Development Framework referenced by EO 14028 procurement attestations.

- **Human URL:** https://csrc.nist.gov/publications/detail/sp/800-218/final

### ISO/IEC 27001

International standard for information security management systems (ISMS). 2022 revision aligns with ISO/IEC 27002:2022 controls.

- **Human URL:** https://www.iso.org/standard/27001

### CIS Critical Security Controls and Benchmarks

Prescriptive controls (v8.1) and benchmarks for OSes, cloud platforms, and applications.

- **Human URL:** https://www.cisecurity.org/controls

### OWASP Top 10 and ASVS

Web application and API risk lists plus the Application Security Verification Standard.

- **Human URL:** https://owasp.org/Top10/

### PCI DSS 4.0.1

Payment Card Industry Data Security Standard for cardholder data environments.

- **Human URL:** https://www.pcisecuritystandards.org/

### SOC 2 Trust Services Criteria

AICPA reporting framework against Security, Availability, Processing Integrity, Confidentiality, Privacy.

- **Human URL:** https://www.aicpa-cima.com/topic/audit-assurance/audit-and-assurance-greater-than-soc-2

### FedRAMP

Standardized approach for U.S. federal agencies to authorize cloud services, anchored on NIST 800-53 baselines.

- **Human URL:** https://www.fedramp.gov/

## Capabilities

- Map organizational controls to multiple frameworks (NIST, ISO, CIS, SOC 2)
- Author and exchange machine-readable controls via OSCAL
- Demonstrate FedRAMP, PCI DSS, SOC 2, ISO 27001 compliance
- Reference OWASP Top 10 in application security reviews
- Track CMMC alignment via NIST 800-171 implementation

## Use Cases

- Building a unified compliance program across cloud customers
- Procurement attestations for federal contracts (EO 14028, FedRAMP)
- Vendor risk assessments using SOC 2 / ISO 27001 reports
- Application security baselines using OWASP ASVS
- Translating CSF outcomes to control implementations in 800-53 / ISO 27002

## Common Resources

- [NIST CSF](https://www.nist.gov/cyberframework)
- [NIST CSRC](https://csrc.nist.gov/)
- [OSCAL Content](https://github.com/usnistgov/oscal-content)
- [ISO 27001](https://www.iso.org/standard/27001)
- [CIS](https://www.cisecurity.org/)
- [OWASP](https://owasp.org/)
- [PCI Security Standards Council](https://www.pcisecuritystandards.org/)
- [AICPA SOC 2](https://www.aicpa-cima.com/)
- [FedRAMP](https://www.fedramp.gov/)
- [HITRUST](https://hitrustalliance.net/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
