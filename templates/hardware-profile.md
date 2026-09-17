---
tags:
  - template
  - hardware
  - inventory
---
# [Hardware Name]

<div class="hero-grid">
  <div class="hero-panel">
    <p class="eyebrow">[Hardware Category]</p>
    <h2>[Hardware Name]</h2>
    <p>
      [One or two sentences describing the role this device plays in the homelab.]
    </p>
  </div>
  <div class="hero-panel hero-panel--accent">
    <p class="eyebrow">System Details</p>
    <ul class="hero-list">
      <li>Hostname: [hostname.lab.local]</li>
      <li>IP: [ip-address]</li>
      <li>Role: [primary-role]</li>
    </ul>
  </div>
</div>

<div style="text-align: center; margin: 2rem 0;">
  <img src="../img/[image-file]" alt="[Hardware Name]" style="max-width: 300px; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>

## Host Configuration

| Field | Value |
| --- | --- |
| Hostname | `[hostname.lab.local]` |
| IP Address | `[ip-address]` |
| Management URL | `[url-or-n/a]` |
| Location | `[rack/room/shelf]` |
| Owner | `[owner]` |

## Hardware Specifications

<div class="callout-grid">
  <div class="callout-box">
    <strong>CPU</strong>
    <p>[cpu-model-or-n/a]</p>
  </div>
  <div class="callout-box">
    <strong>Memory</strong>
    <p>[memory]</p>
  </div>
  <div class="callout-box">
    <strong>Storage</strong>
    <p>[storage]</p>
  </div>
</div>

## Network & Platform

<div class="callout-grid">
  <div class="callout-box">
    <strong>Network</strong>
    <p>[interfaces/speed/vlan]</p>
  </div>
  <div class="callout-box">
    <strong>Operating System</strong>
    <p>[os-or-firmware]</p>
  </div>
  <div class="callout-box">
    <strong>Management</strong>
    <p>[console/ui/ssh]</p>
  </div>
</div>

## Primary Workloads

- **[workload-name]**: [purpose]
- **[workload-name]**: [purpose]
- [additional workload]

## Dependencies

| Dependency | Purpose | Notes |
| --- | --- | --- |
| `[service-or-device]` | [purpose] | [notes] |

## Backup & Recovery

- Backup source: `[backup-source]`
- Backup target: `[backup-target]`
- Recovery owner: `[owner]`
- Recovery notes: [restore notes]

## Notes

[Operational notes, lifecycle status, known limitations, or planned changes.]

