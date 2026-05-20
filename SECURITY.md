# Security Policy

## Repository Structure

pomo infrastructure is intentionally separated across multiple repositories:

| Repository | Purpose |
|---|---|
| `pomo-mac` | Private source code repository |
| `pomo` | Public release distribution repository |
| `pomo-updates` | Public Sparkle update feed and appcast delivery |
| Website repositories | Public marketing and informational websites |

This repository does **not** contain the primary application source code.

---

## Supported Releases

Only the latest stable release is officially supported for security updates.

| Version | Supported |
|---|---|
| Latest Release | ✅ |
| Older Releases | ❌ |

---

## Reporting a Vulnerability

If you discover a security vulnerability related to:

- application behavior,
- update delivery,
- Sparkle integration,
- release artifacts,
- website infrastructure,
- or signed binaries,

please report it privately.

Do not open public GitHub issues for security disclosures.

### Contact

Send a report to:

- GitHub Security Advisory (preferred)
- or direct contact via GitHub profile:
  `https://github.com/SourodeepSarkar`

Include:

- vulnerability description,
- reproduction steps,
- affected version,
- screenshots/logs if relevant,
- and potential impact assessment.

---

## Scope

This repository may contain:

- release binaries,
- release notes,
- update metadata,
- website assets,
- public distribution infrastructure,
- and Sparkle update configuration.

The following are intentionally excluded from public distribution:

- private application source code,
- internal tooling,
- signing infrastructure,
- build pipelines,
- private certificates,
- Sparkle private signing keys,
- and unreleased application components.

---

## Update Security

pomo releases are distributed using signed update mechanisms.

Security measures include:

- Sparkle EdDSA signing,
- notarized macOS builds,
- GitHub release delivery,
- isolated update feed infrastructure,
- and repository separation between source and distribution systems.

Users should only install updates from official pomo distribution channels.

---

## Responsible Disclosure

Please allow reasonable time for investigation and remediation before publicly disclosing vulnerabilities.

Reports made in good faith will be treated respectfully and investigated as resources permit.

---

## Legal

Unauthorized redistribution, impersonation, tampering, malicious repackaging, or fraudulent distribution of pomo binaries or branding may result in takedown requests or further action where applicable.
