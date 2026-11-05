---
description: Run a complete six-phase defensive security audit of the current codebase.
---

Use the `security-audit` skill and its full-audit workflow. Audit the current repository unless the user specifies another local target. Perform all six phases in order, use the standard profile by default, and produce the structured findings and Markdown reports required by the skill. Enforce every OS-sandbox requirement before target-controlled execution. Never probe live or shared systems. If the sandbox cannot be enforced, do source-only review and report exact needs-validation blockers. Do not modify target source.
