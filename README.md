# Invitae (invitae)

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

Invitae, now Labcorp Invitae after Labcorp's 2024 acquisition of select Invitae assets, is a United States medical genetics and healthcare-technology company providing clinical-grade hereditary and somatic genetic testing across oncology, women's health, cardiology, neurology, pediatrics, and rare disease. It offers providers an online ordering portal, licensed genetic counseling, and the Gia digital assistant.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/invitae/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/invitae/refs/heads/main/apis.yml)

## API Posture

Invitae publishes no API. Contract discovery run on 2026-08-15 against every Invitae host found no developer portal, no OpenAPI or Swagger, no GraphQL endpoint, no MCP server, no A2A agent card, no FHIR CapabilityStatement, no SMART-on-FHIR configuration, no webhooks, no client SDK and no `/.well-known/` document (37 path probes across four hosts, zero documents). `api.invitae.com` resolves and terminates TLS but returns a blanket nginx `403 Forbidden` for every path including the root — a private application backend, not a published API — and `developer.`, `docs.`, `fhir.`, `apis.`, `portal.` and `status.invitae.com` do not resolve. The live site markets no API, no partner integration programme and no "request API access" form. Earlier profiles of this company cited Epic Aura / HL7 order-result feeds from 2019 third-party reporting; nothing on invitae.com restates that today, so it is no longer asserted here. The public GitHub organization is genuine but every substantive repository is a fork of an upstream bioinformatics project.

## Tags

- Healthcare
- United States
- Genomics
- Genetic Testing
- Precision Medicine
- Life Sciences
- EHR
- Interoperability
- HL7
- Diagnostics

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## Links

- [Website](https://www.invitae.com/)
- [Provider Portal](https://www.invitae.com/us/providers)
- [Blog](https://blog.invitae.com/)
- [GitHub Organization](https://github.com/invitae)
- [Privacy Policy](https://www.invitae.com/privacy)
- [Terms of Service](https://www.invitae.com/terms)

## Home Market

United States

## Maintainers

- Kin Lane — kin@apievangelist.com
