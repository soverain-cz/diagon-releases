# Security policy

**Product:** Diagon release artifacts — installers and update manifests (this is a public repository)
**Maintainer:** Soverain s.r.o., Prague, Czech Republic

## Reporting a vulnerability

Email **security@soverain.cz**. The mailbox is monitored. You will get a human acknowledgement within two business days, and we will keep you informed while we work on the report.

Please include the product and version (or commit), steps to reproduce or a proof of concept, what an attacker gains, and how you would like to be credited, if at all. English or Czech is fine. Do not put the details in a public issue, pull request or discussion.

This repository is public: never put vulnerability details in an issue, discussion or pull request here.

## What happens next

- We confirm the report, agree a severity with you, and fix it. A compromised or mis-signed artifact is treated as critical and pulled the same day.
- We tell affected customers about confirmed incidents within 48 hours of confirming them, as set out in our [Security Statement](https://www.soverain.cz/legal/security).
- We credit reporters who want credit once a fix has shipped. We do not run a paid bug-bounty programme today.

## Supported versions

The latest published release.

## Good-faith research

We welcome good-faith security research and will not pursue anyone who tests only against the published files and your own installation; does not access, change or delete data that is not their own; avoids denial of service, spam and social engineering; and gives us reasonable time to fix before disclosing. If you are unsure whether something is in scope, ask first at the same address.

## Scope

In scope: the integrity of the published installers and update manifests — signatures, checksums, tampering, the update path. The application code lives in the private `diagon` repository; report code issues to the same address.
