# Copa (Project Copacetic)

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
