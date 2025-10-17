# Ethics & Responsible Use Statement

## Purpose
RedLens — LLM Red-Team Kit is explicitly a **defensive, research-oriented** toolkit. Its purpose is to help engineers, auditors, and defenders understand adversarial patterns against LLM-based systems and build mitigations — not to enable real-world attacks.

## Core principles
1. **Local-first & synthetic:** All experiments, examples, and tests must target local mock models, local model runtimes, or in-repo synthetic data only. No live third-party targets.
2. **Non-maleficence:** Do not use project materials to cause harm, violate privacy, or facilitate illegal activity.
3. **Consent & authorization:** Obtain written permission before testing systems you do not own. For research involving other organizations, use coordinated disclosure and signed authorization.
4. **Human oversight:** High-risk outputs must require explicit human review or operator approval. Never allow automatic execution of high-impact actions in demos.
5. **Transparency & provenance:** All retrieved or external content used in experiments must be labeled with provenance (source, date, confidence). Sanitization steps must be logged.
6. **Minimal disclosure:** Avoid publishing exploit-capable payloads in public branches. Use gated or redacted forms and require reviewer access for sensitive material.

## Demonstration guardrails
- The repository contains "vulnerable" flows for educational purposes. These flows are intentionally isolated and flagged. To run them, a developer must switch `ModelAdapter` to `mock` and use the `--enable-vulnerable` flag. This prevents accidental execution of harm-oriented logic.
- Any real-world testing or third-party engagement requires:
  - Written permission from the owner.
  - A defined scope, duration, and safe rollback plan.
  - Responsible disclosure procedures.

## Responsible disclosure & publication
- If you discover a vulnerability while using RedLens, follow the `SECURITY.md` reporting process.
- When publishing research that extends this repo:
  - Avoid publishing full exploit payloads capable of immediate misuse.
  - Prefer generalized descriptions and mitigations.
  - Coordinate with affected parties when relevant.

## Educational use
This project is intended for learning and defensive research. If you are using it for instruction, ensure all participants understand and agree to the guardrails above.

## Contact & governance
For ethical questions, clarifications, or to request permission for a controlled experiment, contact: `yprakash.518@gmail.com`.

_Last updated: 2025-10-18_
