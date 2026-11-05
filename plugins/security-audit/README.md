# Security Audit — Claude Code Plugin

A Claude Code plugin packaging of the upstream Cloudflare security-audit skill. It preserves the original workflow, domain playbooks, report schema, and zero-dependency validators.

## Install from this marketplace

```text
/plugin marketplace add Perry-fullstackmarketer/security-audit-skill
/plugin install security-audit@perry-fullstackmarketer-marketplace
```

## Commands

- `/security-audit` — complete six-phase audit.
- `/quick-audit` — bounded quick profile.
- `/review-finding` — focused investigation of a candidate.
- `/validate-findings` — validate a findings JSON file.
- `/security-report` — generate reports from verified records.

The `security-audit` skill also activates for relevant security questions and reviews.

## Safety

Never probe live systems, external services, production identities, or shared infrastructure. Target-controlled execution is allowed only inside the OS-enforced sandbox described by the skill. If sandbox controls cannot be enforced, do not execute target code; report the blocker and safe validation plan. Do not modify target source.
