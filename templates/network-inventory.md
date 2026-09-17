---
tags:
  - template
  - networking
  - inventory
---
# [Network Inventory Name]

## Overview

[Describe what network scope this page covers.]

## Hosts

| Name | DNS Name | IP Address | OS / Service | Notes |
| --- | --- | --- | --- | --- |
| [host-name] | `[host.lab.local]` | `[ip-address]` | [os/service] | [notes] |

## DNS Records

| Record | Type | Target | Owner | Notes |
| --- | --- | --- | --- | --- |
| `[record.lab.local]` | A | `[ip-address]` | [owner] | [notes] |

## Network Segments

| Segment | CIDR | Gateway | Purpose | Notes |
| --- | --- | --- | --- | --- |
| `[segment-name]` | `[cidr]` | `[gateway]` | [purpose] | [notes] |

## Ports & Access

| Source | Destination | Port / Protocol | Purpose |
| --- | --- | --- | --- |
| `[source]` | `[destination]` | `[port/protocol]` | [purpose] |

## Dependencies

- [dependency]
- [dependency]

## Verification

```bash
nslookup [record.lab.local]
ping [ip-address]
```

## Notes

[Operational notes, pending cleanup, stale records, or planned changes.]

