---
tags:
  - template
  - services
  - platform
---
# [Service Name]

<div class="hero-grid">
  <div class="hero-panel">
    <p class="eyebrow">[Service Category]</p>
    <h2>[Service Name]</h2>
    <p>
      [One or two sentences explaining what the service does and why it exists in the lab.]
    </p>
  </div>
  <div class="hero-panel hero-panel--accent">
    <p class="eyebrow">Service Details</p>
    <ul class="hero-list">
      <li>DNS: [service.lab.local]</li>
      <li>Platform: [K3s/Docker/VM/LXC/Bare Metal]</li>
      <li>Owner: [owner]</li>
    </ul>
  </div>
</div>

## Overview

[Describe the service purpose, audience, and operational importance.]

## Service Configuration

| Field | Value |
| --- | --- |
| DNS Name | `[service.lab.local]` |
| IP / LoadBalancer | `[ip-address-or-n/a]` |
| Namespace / Host | `[namespace-or-host]` |
| Deployment Method | `[Helm/Docker Compose/Ansible/manual]` |
| Repository | `[repo-name-or-n/a]` |
| Storage | `[storage-class/path/or-n/a]` |

## Dependencies

<div class="callout-grid">
  <div class="callout-box">
    <strong>Identity</strong>
    <p>[identity-provider-or-n/a]</p>
  </div>
  <div class="callout-box">
    <strong>Ingress</strong>
    <p>[Traefik/NPM/direct/n-a]</p>
  </div>
  <div class="callout-box">
    <strong>Persistence</strong>
    <p>[database/storage]</p>
  </div>
</div>

## Access

| Access Path | Users | Notes |
| --- | --- | --- |
| `[url-or-command]` | `[user/group]` | [notes] |

## Operations

- Start/stop: `[command-or-location]`
- Logs: `[command-or-location]`
- Configuration: `[file/repo/path]`
- Backup: `[backup-method]`

## Verification

```bash
[health-check-command]
```

Expected result:

- [expected state]
- [expected response]

## Notes

[Known issues, upgrade notes, ownership notes, or planned improvements.]

