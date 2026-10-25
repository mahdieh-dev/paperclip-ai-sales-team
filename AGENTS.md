# AGENTS.md — MahiDev Paperclip AI sales team tutorial

This is an educational, documentation-first repository, NOT the Paperclip application source tree.

## Goal
Help the user set up the four-agent Paperclip sales analysis demonstration using the provided synthetic sample data, with a Codex-based CEO and three specialists.

## Read order
1. `README.md`
2. `docs/راهنمای-قدم-به-قدم.md`
3. `sample-data/business-facts.md` and `sample-data/sample-conversations.csv`
4. Relevant job descriptions in `prompts/`

## Operating rules
- Reply to the end user in clear Persian unless requested otherwise.
- Before proposing installation, check OS, available CLI tools, versions, and user permissions.
- Do one setup stage at a time; confirm the command output before proceeding.
- Never invent test results, UI screens, output reports, or completion claims.
- This repo provides instructions and prompts only. Paperclip and Codex must be installed separately using current official docs.
- Do not execute unreviewed remote scripts; ask for approval before installation, network access, permission escalation, cost-incurring tasks, or modifications outside the tutorial workspace.
- Never expose or request passwords, login tokens, API keys, or personal customer records in chat or commits.
- Use only synthetic sample data during the first run. No posting to Instagram, external messaging, email, buying, granting discounts, or real customer actions without explicit user approval.
- Verify each agent is present, correct manager relationship, and the first task has traceable outcomes before saying setup succeeded.
- If the guide and a current official Paperclip page differ, surface the conflict explicitly; do not silently replace user documentation.
- Do not add more agents or scope beyond the initial CEO, analyst, sales strategist and quality reviewer without approval.

## Acceptance checks
1. Paperclip is reachable locally.
2. Codex CLI is installed and logged in using the user's own eligible account.
3. Company `Sales Insight Lab` exists.
4. CEO + three agents exist with expected reports-to relationships.
5. They can access the two sample files via intended project/task scope.
6. A first test task runs; the findings cite synthetic conversation IDs and do not assert unsupported causes.
7. User approves any spending, external access, or risky actions.
