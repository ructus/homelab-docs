---
tags:
  - template
  - guide
  - install
---
# [Service or Tool] Install Guide

<div class="hero-grid">
  <div class="hero-panel">
    <p class="eyebrow">Install Guide</p>
    <h2>[Service or Tool]</h2>
    <p>
      [One or two sentences describing what this install guide deploys and where it runs.]
    </p>
  </div>
  <div class="hero-panel hero-panel--accent">
    <p class="eyebrow">Deployment Details</p>
    <ul class="hero-list">
      <li>Platform: [K3s/Docker/VM/LXC/Bare Metal]</li>
      <li>DNS: [service.lab.local]</li>
      <li>Storage: [storage type]</li>
    </ul>
  </div>
</div>

## Overview

[Describe the target state, major components, and why this deployment exists.]

## Prerequisites

| Requirement | Value |
| --- | --- |
| Host / Cluster | `[host-or-cluster]` |
| DNS | `[record-or-n/a]` |
| Storage | `[path/storage-class/or-n/a]` |
| Credentials | `[secret-location]` |
| Repository | `[repo-or-n/a]` |

!!! warning
    Confirm prerequisites and backup or rollback options before changing production lab services.

## Phase 1 - Prepare DNS & Storage

1. Create or verify DNS:

   ```bash
   nslookup [service.lab.local]
   ```

2. Create required directories or storage objects:

   ```bash
   [storage-prep-command]
   ```

## Phase 2 - Prepare Namespace or Host

```bash
[namespace-or-host-prep-command]
```

Verify:

```bash
[prep-verification-command]
```

## Phase 3 - Configure Values

Create or update `[values-file]`:

```yaml
[configuration-example]
```

## Phase 4 - Install

```bash
[install-command]
```

Watch deployment status:

```bash
[status-command]
```

## Phase 5 - Verify Access

1. Confirm service health:

   ```bash
   [health-check-command]
   ```

2. Confirm DNS or ingress:

   ```bash
   [ingress-or-dns-command]
   ```

3. Open:

   ```text
   [service-url]
   ```

## Smoke Test

```bash
[smoke-test-command]
```

Expected result:

- [expected result]

## Rollback

```bash
[rollback-command]
```

Rollback notes:

- [data preservation note]
- [DNS or ingress cleanup note]
- [manual recovery note]

## Notes

[Version notes, source links, lab-specific decisions, or follow-up tasks.]

