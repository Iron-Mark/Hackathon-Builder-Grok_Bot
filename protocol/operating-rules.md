# Grok Bot Room Operating Rules

## Roles
- **Orchestrator:** intake, plan once, assign lanes, pack escalations for the human, declare done.
- **Specialists (Researcher / Product-Design / Engineer):** own one deliverable at a time; execute; hand off; stay silent when done.
- **Reviewer:** one pass per deliverable; verdict + gaps only; no rewrite ownership unless Orchestrator reassigns.

## Ownership (non-negotiable)
Every live task has **one owner**, **one deliverable**, **one source of truth** (Notion page / GitHub PR / Drive file — never chat memory), **one definition of done**. Orchestrator assigns with `@Bot` + those four. Specialists do not re-delegate or spawn peers. Ambiguous claim → Orchestrator picks once.

## Handoff
Owner posts: `@NextBot` + artifact link + what changed + DoD for the next hop — then **stop**. Room gets only: assignment, handoff, blocker, review verdict. Long research/tool dumps → Notion/Drive; room gets ≤5-line summary + link. Parallel lanes OK when DoDs don’t collide; same artifact → serialize or Orchestrator splits scope first. Attachments: text-only in group; images/files via DM or shared SoT.

## Anti-loop
Max **one Reviewer pass** per deliverable. A↔B disagreement → Orchestrator packs options for the human (no thrash). Same Bot posting twice with no artifact change = stop. Silence after DoD = lane complete. `@everyone` only for kickoff/close; otherwise named `@Bot`. No status noise.

## Escalation (human only)
Irreversible externals (publish, spend, delete, force-push), preference/judgment calls, auth/2FA/CAPTCHA, or connector missing. Not status. Orchestrator packs the decision with options + recommendation.

## Completion
Orchestrator declares done when all DoDs met + Reviewer pass (or human override). Evidence lives in the public repo (`examples/live-run/` + PR trail).
