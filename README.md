# Copa (Project Copacetic)

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

Project Copacetic (Copa) is an open source command line tool that patches container images directly using BuildKit, without requiring a full image rebuild. Copa parses vulnerability scan reports from Trivy and other scanners, applies the corresponding OS package updates via the appropriate package manager (apt, apk, dnf, tdnf, yum, zypper), and produces a new container image with a patched layer. Copa supports multi-platform images, distroless images, and custom scanner plugins through the Vulnerability Exchange (VEX) and pluggable scanner interface.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/copa/refs/heads/main/apis.yml)

## Tags

- BuildKit, CLI, CNCF Sandbox, Container Patching, Containers, Open Source, Security, Trivy, Vulnerability Management

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### Copa CLI
The copa command line interface used to patch container images. The core subcommand `copa patch` accepts an image reference and an optional vulnerability report and produces a new tagged image with OS-level package vulnerabilities remediated via BuildKit.

**Human URL:** [https://project-copacetic.github.io/copacetic/website/](https://project-copacetic.github.io/copacetic/website/)

#### Tags
- CLI, Patching

#### Properties
- [Documentation](https://project-copacetic.github.io/copacetic/website/)
- [Quick Start](https://project-copacetic.github.io/copacetic/website/quick-start/)
- [GitHubRepository](https://github.com/project-copacetic/copacetic)
- [License](https://github.com/project-copacetic/copacetic/blob/main/LICENSE)
- [Issue Tracker](https://github.com/project-copacetic/copacetic/issues)

### Copa Scanner Plugin Interface
Copa exposes a plugin interface that allows third-party vulnerability scanners to feed reports into the patcher.

**Human URL:** [Scanner plugins](https://project-copacetic.github.io/copacetic/website/scanner-plugins/)

#### Tags
- Plugins, Scanners, Trivy

### Copa VEX Output
Copa can emit a Vulnerability Exchange (VEX) document describing which CVEs were patched.

**Human URL:** [Output options](https://project-copacetic.github.io/copacetic/website/output/)

#### Tags
- OpenVEX, SBOM, VEX

## Common Properties

- [Website](https://project-copacetic.github.io/copacetic/website/)
- [Quick Start](https://project-copacetic.github.io/copacetic/website/quick-start/)
- [GitHubRepository](https://github.com/project-copacetic/copacetic)
- [GitHub Organization](https://github.com/project-copacetic)
- [Issue Tracker](https://github.com/project-copacetic/copacetic/issues)
- [Change Log](https://github.com/project-copacetic/copacetic/releases)
- [License](https://github.com/project-copacetic/copacetic/blob/main/LICENSE)
- [Community](https://github.com/project-copacetic/copacetic/blob/main/CONTRIBUTING.md)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
