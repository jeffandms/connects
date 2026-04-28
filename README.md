# Professional impact tracker

This repo is set up to be a durable working record for professional impact, not just a place to dump Connect text at review time.

## How it is organized

| Path | Purpose |
| --- | --- |
| `CLAUDE.md` | Repo-level instructions for how Claude should maintain the tracker |
| `.claude\commands\` | Reusable Claude workflows for recurring updates |
| `docs\tracker\current-focus.md` | What is active now, plus risks and evidence gaps |
| `docs\tracker\impact-log.md` | Dated evidence log of wins, leverage, incidents, mentoring, and outcomes |
| `docs\tracker\promotion-case.md` | Synthesized case grouped by the themes your boss values |
| `docs\tracker\summary.md` | Rolling manager-facing summary of concrete review-cycle results and metrics |
| `docs\connects\previous-connects.md` | Historical baseline distilled from prior Connect PDFs |
| `docs\connects\next-connect.md` | Working draft for the next Connect |

## Suggested iteration rhythm

1. **Weekly or every other week:** run `/weekly-update latest`.
2. **After something notable happens:** run `/capture-win ...` with rough notes.
3. **Before a manager sync or review checkpoint:** run `/manager-brief`.
4. **When Connect season starts:** run `/prepare-connect`.

That cadence keeps evidence current without making the repo a daily chore.

## Sources this setup expects

- Notes you paste directly into chat
- Existing tracker files in this repo
- Historical Connect PDFs already in the repo
- WorkIQ sources like email, Teams, calendar, or files when you explicitly want the latest external evidence pulled in

## Working principle

Raw evidence belongs in the tracker docs first. Polished review language comes later from that evidence.
