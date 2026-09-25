# Myles Control Center — OWNER LOCK

This repository is the owner's canonical production dashboard.

## Non-negotiable
- Continuous/self-improvement jobs MUST NOT redesign, rewrite, replace, commit, push, or publish this repository.
- Runtime status belongs on the live tower bridge, not in Git commits.
- No generic admin templates, Bootstrap replacement dashboards, mock/random data, fake prices, fake API endpoints, light mode, or placeholder telemetry.
- Preserve the dark mobile-first Control Center, phone bridge, chat, tasks, systems, Scalp Terminal, Auto Bot, research, funding, and advanced risk views.
- Only an explicit owner-requested dashboard task may modify production, and that task must use a candidate copy, validate it, and deliberately unlock the local git hooks for the one verified commit/push.
- PineTree remains off-limits to Myles.

## Canonical repository map
- Owner UI: `JoshuaDuskin/MylesDashboard`
- Quant source: `JoshuaDuskin/trading-dashboard`
- Live runtime/chat/trading telemetry: authenticated tower bridge
- Never create another Myles dashboard, control-center, progress, runtime-status, or live-status repository.
- Before any explicit owner-approved GitHub work, reuse the canonical repository for that project instead of creating a new repository.
