# External Actions Baseline

## Purpose

This policy governs automated or AI-assisted actions that affect systems, people, money, access, data, or public communications outside the current working context.

## Default

Read-only work within authorized access is allowed unless a repository policy says otherwise. External or consequential write actions require appropriate human authorization.

## Action categories

| Category | Examples | Default |
| --- | --- | --- |
| Read-only | Search, inspect, analyze, draft without saving | Allowed within authorized access |
| Reversible internal write | Create a branch, draft pull request, sandbox record | Allowed only when declared and authorized by repository rules |
| Material write | Send a message, change shared configuration, create a non-draft record, publish documentation | Explicit approval immediately before execution |
| High-impact action | Deploy, delete data/resources, alter access, spend money, accept terms, merge protected branches, publish externally | Explicit approval from an authorized person; additional repository controls may apply |

## Requirements

- Use the least privilege and narrowest credentials practical.
- Resolve the intended target before requesting approval.
- Present the exact target, action, and payload or diff to the approver.
- Treat approval as single-use and specific to that target and payload.
- Obtain new approval if target, payload, scope, or impact changes.
- Log or record material actions where the repository or service supports it.
