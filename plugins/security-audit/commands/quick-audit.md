---
description: Run a bounded quick-profile security review of the current codebase.
---

Use the `security-audit` skill. Run its `quick` full-audit profile against the current repository: one hunter wave, one final coverage-critic pass, and the reduced verifier path specified by the skill. Preserve the evidence bar and all sandbox restrictions. Report deferred coverage explicitly. Do not modify target source or test live systems.
