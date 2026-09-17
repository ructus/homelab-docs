---
tags:
  - template
  - runbook
  - operations
---
# [Runbook Name]

## Purpose

[Describe when this runbook should be used and what outcome it produces.]

## Scope

| Area | Details |
| --- | --- |
| Services | `[service-list]` |
| Hosts / Cluster | `[hosts-or-cluster]` |
| Risk Level | `[low/medium/high]` |
| Owner | `[owner]` |

## Preconditions

- [precondition]
- [precondition]
- [backup or snapshot requirement]

!!! warning
    Stop if the preconditions are not met or if the current incident differs from this runbook.

## Procedure

### 1. Validate Current State

```bash
[status-command]
```

Expected:

- [expected status]

### 2. Execute Change

```bash
[change-command]
```

### 3. Monitor

```bash
[monitoring-command]
```

Expected:

- [expected status]

## Verification

| Check | Command / Location | Expected Result |
| --- | --- | --- |
| [check name] | `[command-or-url]` | [expected result] |

## Rollback

```bash
[rollback-command]
```

Rollback validation:

```bash
[rollback-validation-command]
```

## Follow-up

- Capture timeline.
- Record root cause.
- Create prevention tasks.
- Update this runbook with lessons learned.

## Notes

[Known issues, edge cases, escalation contacts, or related pages.]

