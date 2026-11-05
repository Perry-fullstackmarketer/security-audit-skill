---
description: Validate a findings JSON file using the bundled zero-dependency validator.
---

Use the `security-audit` skill's findings contract. Identify the requested `findings.json` path; if none is supplied, ask for it. Run:

```bash
node "${CLAUDE_PLUGIN_ROOT}/skills/security-audit/validate-findings.cjs" "<path-to-findings.json>"
```

Report the validator result and explain any errors. Do not edit the findings file automatically.
