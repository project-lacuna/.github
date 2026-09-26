# Data Handling Baseline

## Purpose

This policy defines the organization-wide minimum requirements for information stored in repositories or used in repository-managed workflows.

## Classification

| Class | Repository treatment |
| --- | --- |
| Public | Allowed when disclosure is intentional and provenance/license are known. |
| Internal | Default for non-public organizational work. Limit access to authorized collaborators. |
| Confidential | Do not commit raw content. Use an approved access-controlled source and store only a safe reference or non-sensitive metadata when needed. |
| Restricted | Prohibited from repositories. This includes secrets, credentials, private keys, sensitive personal/customer data, regulated data, and sensitive security material. |

## Requirements

- Classify information by the sensitivity and impact of unauthorized disclosure, modification, or loss.
- Keep confidential and restricted information in approved, access-controlled systems rather than Git.
- Use synthetic or fully sanitized fixtures, screenshots, examples, evaluation data, issue content, PR descriptions, and logs.
- Treat derived artifacts according to the sensitivity of their sources when they can disclose or reconstruct sensitive information.
- Apply the same rules to Git history, branches, tags, pull requests, issues, Actions logs, packages, releases, and artifacts.

## AI use

Do not send Confidential or Restricted information to AI services unless the repository-specific policy and an approved service arrangement explicitly allow that use. Prompts, retrieval context, embeddings, model outputs, telemetry, and transcripts can all carry sensitive information.

## Incident response

If prohibited information is committed or shared, stop further distribution, revoke or rotate affected credentials, report the event privately, and follow the applicable response procedure.
