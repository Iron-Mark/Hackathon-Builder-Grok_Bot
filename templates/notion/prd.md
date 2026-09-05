# PRD (template)

Paste-ready page body — not an outline. Duplicate this Notion page for each Spec-to-ship kit. Keep headings. Replace or delete every **EXAMPLE** block.

> **EXAMPLE — Hackathon-Builder-Grok_Bot / Spec-to-ship.** The filled copy below is the first live-run, so a new crew can see a complete PRD. Clear the example text under each heading and reuse the structure. Evidence: https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot · live-run: https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot/tree/main/examples/live-run

## Problem

> **EXAMPLE (clear this block):** Most “multi-agent” demos are six ChatGPT tabs with a human as the router. Context lives in chat memory, handoffs are invisible, and the demo is a slide deck. Judges cannot tell whether the bots actually shipped.

## Goal / one-liner

> **EXAMPLE (clear this block):** Open kit + live proof that a Grok Bot group can take a vague objective → research → PRD → shipped PR **without Mark as router.**
>
> Repo: `Hackathon-Builder-Grok_Bot` · Workflow name: Spec-to-ship · License: MIT · Pages: https://iron-mark.github.io/Hackathon-Builder-Grok_Bot/

## Users

> **EXAMPLE (clear this block):**

| Who | Job in this kit |
|-----|-----------------|
| Human (Mark) | Judgment only: publish, spend, auth/2FA, preference. Not the router. |
| Orchestrator | Plan once, assign owner / deliverable / SoT / DoD, pack escalations, declare done. |
| Researcher | Evidence into Notion/GitHub; ≤5-line room summary + link. |
| Product Design | PRD, flows, acceptance, demo script. |
| Engineer | Scaffold + public PR. The PR trail is the demo. |
| Reviewer | One pass vs SoT; verdict + gaps; no rewrite ownership. |
| Hackathon viewers / judges | Watch native group handoffs + connectors; open the public repo. |

## MVP ships

Numbered. Each ship has one owner when the Orchestrator assigns.

> **EXAMPLE (clear this list after you write your own):**

1. Paste-ready Bot profiles (`bots/*.md`) — Orchestrator, Researcher, Product Design, Engineer, Reviewer.
2. Room operating protocol (`protocol/operating-rules.md`) — ownership, handoff, anti-loop, escalation, completion.
3. Notion + GitHub templates (`templates/`) — research DB, this PRD, decision log, issue template, PR checklist.
4. `/examples/live-run/` evidence pack from **this** crew’s first Spec-to-ship.
5. 2–5 min demo script (`demo/SCRIPT.md`) usable for kickoff without Mark as router.

## Acceptance criteria

Reviewer checks these against GitHub/Notion — not vibes. One pass per deliverable.

> **EXAMPLE (clear this list after you write your own):**

- [ ] Five paste-ready files under `bots/` (Orchestrator, Researcher, Product Design, Engineer, Reviewer).
- [ ] `protocol/operating-rules.md` covers ownership, handoff, anti-loop, escalation, completion.
- [ ] GitHub templates under `templates/github/` (issue + PR checklist).
- [ ] Notion templates under `templates/notion/` are **paste-ready page bodies**, not outlines.
- [ ] `examples/live-run/` includes capabilities, one-pager, decisions, sources, Reviewer pass, presenter cues.
- [ ] `demo/SCRIPT.md` is a 2-min Showcase cut with a pasteable `@everyone` kickoff.
- [ ] Public repo URL is the SoT for the kit: https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot
- [ ] No secrets committed. Human is not used as router.

## Out of scope

> **EXAMPLE (clear this block):** Out of Day-1: Context7, X, custom MCP, maintenance bots, marketing launch kit. Do not design around Bots as a security boundary, Bot→group binary attachments, memory as source of truth, unlimited parallel GUI on one screen, or inventing X/Context7 without a live Plugin. Localhost/stdio MCP is unsupported for Plugins — remote HTTPS MCP only.

## Demo UX (beats)

Present from **Pages + the group room**, not a slide deck. Times are Showcase-cut targets.

> **EXAMPLE (clear this table after you write your own beats):**

| Time | Beat |
|------|------|
| **0:00** | Human: one objective in the group — “Ship Hackathon-Builder-Grok_Bot kit.” |
| **0:20** | Visible `@` handoffs — Orchestrator assigns owner / deliverable / SoT / DoD. |
| **0:50** | Cut to repo README + `bots/` — paste-ready profiles. |
| **1:20** | `examples/live-run/` proof (capabilities → one-pager → decisions → Reviewer pass). |
| **1:45** | PR trail + `protocol/operating-rules.md` as the product — not six chat tabs. |

Kickoff paste (group):

```
@everyone Spec-to-ship live run. Objective: ship public repo Hackathon-Builder-Grok_Bot — Bot profiles, operating protocol, Notion+GitHub templates, examples/live-run/ from this run, and demo/SCRIPT.md. Orchestrator owns plan/assign. Researcher → one-pager evidence pack. Product Design → paste-ready profiles + PRD for the kit. Engineer → scaffold + PR. Reviewer → one pass on each artifact vs SoT. Room: assignment/handoff/blocker/verdict only. Mark: judgment only. Go.
```

## SoT rules

Source of truth is **Notion and/or GitHub** (and Drive when the artifact lives there). **Never chat memory.**

- Every live task: **one owner**, **one deliverable**, **one SoT URL**, **one definition of done**.
- Orchestrator assigns with `@Bot` + those four. Specialists do not re-delegate.
- Room posts = assignment / handoff / blocker / review verdict only.
- Long research/tool dumps → this Notion workspace or the public repo; room gets ≤5-line summary + link.
- Attachments: text-only in group; images/files via DM or shared SoT.
- Reviewer checks claims against Notion/GitHub, not the last message in the thread.

> **EXAMPLE SoT URLs (clear when you reuse):** Repo https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot · Pages https://iron-mark.github.io/Hackathon-Builder-Grok_Bot/ · live-run https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot/tree/main/examples/live-run · this PRD page (Notion) · decision log (Notion).

## Escalation (what needs human)

Orchestrator packs **options + recommendation**. Not status noise.

Escalate to the human only for:

- Irreversible externals: publish, spend, delete, force-push
- Preference / judgment calls (name, license, brand, scope)
- Auth / 2FA / CAPTCHA / password
- Connector missing (or localhost MCP — unsupported; do not wait on it)
- Unresolved A↔B disagreement after **one** Reviewer pass

Do **not** escalate: progress, “still working,” or re-asking a locked decision.

> **EXAMPLE (clear this block):** Venue + crew recommendation was keep **public + MIT**. Mark presenting from this repo. Repo name `Hackathon-Builder-Grok_Bot` was locked by Mark in the hackathon room — not a Bot preference.

## Definition of Done

Orchestrator declares done when all DoDs are met **and** Reviewer has passed (or the human overrides).

> **EXAMPLE (clear this list after you write your own):**

- [ ] All five MVP ships are in the public repo.
- [ ] Reviewer posted pass/fail + gaps vs this PRD (max one pass per deliverable).
- [ ] Decision log has one row per locked call, with links to PR/Pages when applicable.
- [ ] Evidence lives in GitHub (`examples/live-run/` + PR trail), not in chat history.
- [ ] Demo script can be pasted as kickoff without the human routing specialists.
- [ ] Human-only items (publish, license, repo name) are recorded as outcomes, not reopened in the room.
