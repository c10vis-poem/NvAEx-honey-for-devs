# MEMORY.md — NoVa-honey-for-devs
Durable facts about this repo. Dated; newest first. Updated at session wrap-up.

## 2026-10-01
- The log-compress PostToolUse hook routes crushed rows through the ESON converter (falls back to JSON); tests 12/12. Written 2026-09-22, committed 2026-10-01.
- The Honey plugin installed in Claude Code comes from the plugin cache (`greenpt/honey` 1.3.1), not from this fork. Changes reach upstream via PR.

## 2026-10-23
- Merged since 2026-10-01: #1 ESON logcompress, #3 eson-on-PATH guard in session hook, #4/#6 terseness reminder every 3rd tool call (obs 0001). All PRs target `main`; branch protection requires status checks.
- AGENTS.md is generated from `skills/honey/SKILL.md` via `scripts/build-rules.js`.
