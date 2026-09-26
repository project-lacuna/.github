# Security Policy

## Report privately

Do not open a public issue for a suspected vulnerability, exposed credential, or sensitive security finding.

Organization members should contact the named owners or maintainers of a repository for potentially sensitive security findings. External reporters should use the security contact or private reporting mechanism listed on the organization profile or affected repository.

## Include

* A concise description of the issue.
* Affected repository, component, version, or commit where known.
* Reproduction steps or proof of concept that minimize harm.
* Potential impact and any suggested mitigation.

## Do not include

* Active credentials, access tokens, private keys, or passwords.
* Personal, customer, or production data.
* Broadly exploitable details in public issues, pull requests, discussions, or release notes before remediation.

## If a secret is committed

Treat the secret as exposed: revoke or rotate it immediately, limit further access, and report the incident through the private route. Removing a value from a later commit *does not make the original exposure safe*.

<div align="center">
<img src="./assets/project-lacuna-end-line.png" alt="Project Lacuna's butterfly logo with a decorative divider in sage green">

© 2026-<i>present</i> Project Lacuna, LLC</div>
