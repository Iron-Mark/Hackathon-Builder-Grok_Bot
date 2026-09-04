# grok-bot-spec-to-ship

<p align="center">
  <img src="docs/assets/hero-handoff.svg" alt="Five specialized Grok Bots collaborating as a constellation" width="100%" />
</p>

**Open kit + live proof** that a Grok Bot group can take a vague objective → research → PRD → shipped public repo **without the human as router**.

This is not six ChatGPT tabs. Handoffs are visible in the group room. Notion/GitHub are the source of truth. The PR trail *is* the demo.

<p align="center">
  <a href="https://iron-mark.github.io/grok-bot-spec-to-ship/"><strong>Live Pages →</strong></a>
  ·
  <a href="demo/SCRIPT.md"><strong>2-min demo script →</strong></a>
  ·
  <a href="examples/live-run/"><strong>Live-run proof →</strong></a>
</p>

---

## Why this exists

| Single chatbot / one agent | This kit |
|----------------------------|----------|
| You are the router | Orchestrator assigns once with `@Bot` |
| Context lives in chat | SoT = GitHub / Notion; room stays thin |
| No ownership | One owner · one deliverable · one DoD |
| Endless debate | One Reviewer pass, then escalate or ship |
| Hard to show | Pages + PR trail + `examples/live-run/` |

**Venue fit:** one real task · public / non-sensitive · public GitHub repo · ≥1 Grok Bot.

---

## Showcase storyboard (2 min)

| Time | Beat |
|------|------|
| **0:00** | Mark: one objective in the group room |
| **0:20** | Visible `@` handoffs — owner / deliverable / SoT / DoD |
| **0:50** | Cut to this README + `bots/` + Pages hero |
| **1:20** | `examples/live-run/` proof trail |
| **1:45** | PR + `protocol/operating-rules.md` as the product |

Full cut: [`demo/SCRIPT.md`](demo/SCRIPT.md) · Presenter cues: [`examples/live-run/06-presenter-cues.md`](examples/live-run/06-presenter-cues.md)

Drop your recording at [`docs/assets/video/showcase-2min.mp4`](docs/assets/video/) — the Pages landing already has the player slot.

---

## What's in the box

| Path | Deliverable |
|------|-------------|
| [`bots/`](bots/) | Paste-ready profiles: Orchestrator, Researcher, Product Design, Engineer, Reviewer |
| [`protocol/operating-rules.md`](protocol/operating-rules.md) | Ownership, handoff, anti-loop, escalation, completion |
| [`templates/`](templates/) | Notion + GitHub SoT stubs |
| [`examples/live-run/`](examples/live-run/) | This crew’s Spec-to-Ship trail |
| [`demo/SCRIPT.md`](demo/SCRIPT.md) | 2-minute Showcase script + kickoff |
| [`docs/`](docs/) | GitHub Pages landing |
| [`docs/assets/`](docs/assets/) | Hero, OG, video slot |

---

## Crew flow

```text
Human (judgment only)
   ↓
Orchestrator  — plan once, assign, pack escalations, declare done
   ↓
Researcher + Product Design  — parallel evidence + PRD
   ↓
Engineer  — public repo / PR
   ↓
Reviewer  — one pass vs SoT
   ↓
Orchestrator → Human (only irreversible / preference calls)
```

Rules of the room: [`protocol/operating-rules.md`](protocol/operating-rules.md)

---

## Live-run index

Evidence from the first crew that shipped this kit:

| File | Contents |
|------|----------|
| [`01-capabilities.md`](examples/live-run/01-capabilities.md) | Confirmed Grok Bot capabilities vs assumptions |
| [`02-product-one-pager.md`](examples/live-run/02-product-one-pager.md) | Showcase product one-pager |
| [`03-decision-log.md`](examples/live-run/03-decision-log.md) | Locked decisions (workflow, seats, repo) |
| [`04-sources.md`](examples/live-run/04-sources.md) | Primary sources |
| [`05-reviewer-pass.md`](examples/live-run/05-reviewer-pass.md) | Reviewer PASS + closed-loop proof |
| [`06-presenter-cues.md`](examples/live-run/06-presenter-cues.md) | Presenter beats for Showcase |

---

## Assets & graphics

<p align="center">
  <img src="docs/assets/og-card.svg" alt="Spec-to-Ship Open Graph card" width="640" />
</p>

| Asset | Use |
|-------|-----|
| [`docs/assets/hero-handoff.svg`](docs/assets/hero-handoff.svg) | Pages / README hero |
| [`docs/assets/og-card.svg`](docs/assets/og-card.svg) | Social / OG preview |
| [`docs/assets/ASSETS.md`](docs/assets/ASSETS.md) | Shot list + video drop instructions |
| [`docs/assets/video/`](docs/assets/video/) | Place `showcase-2min.mp4` here |

**Live site:** https://iron-mark.github.io/grok-bot-spec-to-ship/

---

## Quick start

1. Create five Grok Bots; paste each file from [`bots/`](bots/) into the Bot description.
2. Create a group chat with those five Bots.
3. Paste the kickoff from [`demo/SCRIPT.md`](demo/SCRIPT.md).
4. Watch: plan once → `@` lanes → research/PRD → public PR → one Reviewer pass → one human judgment.

---

## License

MIT — see [LICENSE](LICENSE).
