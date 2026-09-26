# Organization Repository Safety Standard

This document defines the minimum repository-safety requirements for Project Lacuna, LLC repositories.

## Purpose

Project Lacuna repositories may contain software, documentation, automation, configuration, reusable templates, and other organizational work product. This baseline protects people, data, credentials, intellectual property, and external systems while keeping contribution practices lightweight.

## Default classification

* Non-public repository content is **Internal** by default.
* Public material may be committed when public disclosure is intentional and its license or reuse terms are understood.
* Repository-specific policies may define additional classifications or stricter handling requirements.

## Non-negotiable rules

* Do not commit secrets, credentials, private keys, tokens, passwords, or `.env` files.
* Do not commit personal data, customer data, unredacted production records, or regulated data unless the repository's approved policy explicitly permits it.
* Use synthetic or fully sanitized fixtures, examples, screenshots, and logs.
* Do not rely on prompts, obscurity, or repository privacy as a security control for sensitive information.
* Do not publish, disclose, send, deploy, purchase, delete, change access, or otherwise perform consequential external actions without required human authorization.
* Track material third-party content, code, data, and prompts with sufficient provenance and license information to support their intended use.

## Policy precedence

1. Applicable law, contract, platform terms, and security obligations apply.
2. This organization baseline establishes minimum requirements.
3. Repository policies may add or clarify requirements.
4. Directory-level instructions and artifact manifests may further narrow permitted data or capabilities.

> ![IMPORTANT]
> A lower-level document cannot weaken a higher-level requirement without a written, authorized exception.

## Detailed guidance

* [Data handling](policies/data-handling.md)
* [External actions](policies/external-actions.md)
* [Third-party content](policies/third-party-content.md)
* [Contribution guidelines](CONTRIBUTING.md)
* [Security reporting](SECURITY.md)

## Uncertainty

When unsure whether information may be committed, shared, processed by an AI system, or used for an external action, stop and request review before acting.

<div align="center">
<img src="./assets/project-lacuna-end-line.png" alt="Project Lacuna's butterfly logo with a decorative divider in sage green">

© 2026-<i>present</i> Project Lacuna, LLC</div>
