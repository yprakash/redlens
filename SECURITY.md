# Security Policy

## Quick security contacts
- Responsible disclosure / report vulnerabilities: **yprakash.518@gmail.com**
- PGP key fingerprint: `TODO: add PGP fingerprint` (optional)
- If the report contains sensitive files (P0/P1), please encrypt using our PGP key.

## Scope
This policy covers:
- Vulnerabilities in the codebase and demo scripts.
- Issues that could lead to unauthorized data access, code execution, or unsafe demos.
- Any accidental or deliberate attempts to use this project against third-party targets.

## Safe reporting steps (recommended)
1. Do **not** post vulnerabilities publicly (issues, gists, Twitter).
2. Send an email to `yprakash.518@gmail.com` with:
   - Short summary and severity expectation.
   - Reproduction steps (local/demo reproduction only).
   - Proposed fixes or mitigations if available.
   - Attach logs or minimal repro code; encrypt if sensitive.
3. Maintainers will acknowledge within **3-4 days** and provide a timeline for remediation or response.

## What we ask of reporters
- Focus on reproducible, local-only demos. Do not run tests against third-party systems.
- Do not publicly disclose details until we coordinate a remediation timeline.
- Provide an advisory or writeup under coordinated disclosure if you wish to publish later.

## Maintainer response and timeline
- Acknowledge receipt within 72 hours.
- Triage and classify severity within 7 days.
- For critical issues, provide a coordinated remediation plan and timeline.
- We may publish a public advisory after fixes are released, crediting the reporter unless they request anonymity.

## Safe demo rules (project-specific)
- All demos MUST run on local or synthetic data only. Do not target external services.
- The repository will include explicit gates (prompts, flags) that must be used to enable any simulated “vulnerable” flow.
- Any reproduction instructions that could enable misuse are redacted from public branches and available only under explicit written permission.

## If you discover an active exploit in the wild
- Immediately cease interaction with live systems.
- Contact the appropriate affected party (owner of the system) and the project maintainers via `yprakash.518@gmail.com`.
- Follow responsible disclosure norms and preserve evidence.

_Last updated: 2025-10-18_
