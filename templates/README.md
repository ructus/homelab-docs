---
tags:
  - reference
  - documentation
  - templates
---
# Homelab Docs Templates

Use these templates when adding new pages to the homelab documentation.

## Template Map

| Template | Use for | Destination examples |
| --- | --- | --- |
| `hardware-profile.md` | Physical devices, servers, NAS, switches, routers, workstations | `docs/hardware/` |
| `service-profile.md` | Applications and platform services such as GitLab, Harbor, Keycloak, Open-WebUI | `docs/platform/`, `docs/install-docs/`, `docs/network/` |
| `install-guide.md` | Repeatable software or infrastructure installation procedures | `docs/install-docs/<service>/` |
| `runbook.md` | Operational procedures, incident response, maintenance, recovery | `docs/operations/` |
| `network-inventory.md` | Host lists, DNS records, subnets, ports, service maps | `docs/network/` |
| `diagram-page.md` | Mermaid diagrams, topology pages, system relationship pages | `docs/diagrams/` |
| `reference-page.md` | Standards, notes, conventions, long-lived reference material | `docs/reference/` |
| `platform-page.md` | Platform overview, architecture, shared service narratives | `docs/platform/` |

## Style Rules

- Use one topic per page.
- Lead with purpose and scope.
- Keep headings in this order when possible: overview, configuration, dependencies, procedure, verification, rollback, notes.
- Put warnings before procedures.
- Use numbered steps for operational work.
- Include verification and rollback for install guides and runbooks.
- Use the existing `hero-grid`, `hero-panel`, `callout-grid`, `callout-box`, `cards`, and `hero-list` classes for visual consistency.
- Prefer local images from `docs/img/` when documenting hardware or architecture.
- Keep DNS names, IP addresses, namespaces, storage paths, and repository names in tables where they need to be scanned.

## Placeholder Convention

Replace bracketed placeholders such as `[service-name]`, `[owner]`, and `[ip-address]` before publishing a page.

