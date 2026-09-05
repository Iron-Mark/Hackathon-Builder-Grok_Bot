# Decision log (template)

Paste-ready page body — not an outline. Duplicate this Notion page (or convert the table into a database with the same columns). **One decision per row.** When the outcome is a PR or Pages URL, put that link in **Outcome / link**.

## How to use

1. Create a Notion page named `Decision log` (or a full-page database with the columns below).
2. Paste this body. Keep the table headers. Delete the **EXAMPLE** rows after you copy the pattern — or leave them as the Spec-to-ship worked example for this kit.
3. Orchestrator (or the human) adds a row **when a call is locked**, not when it is still being debated.
4. Room posts stay short: “Decision locked → [this page].” Full options live here.
5. Reviewer treats this page as SoT for preference calls. Do not relitigate a row in chat.

### Rules

- **One decision per row.** Split “name + license + workflow” into three rows.
- Link to the **PR** or **Pages** URL in Outcome / link when that is how the decision shipped.
- Do not use chat memory as the log. If it is not in this table, it is not locked.
- Owner is the Bot or human who owns the call — not everyone who opined.

## Table columns

| Date | Decision | Options considered | Chosen | Owner | Outcome / link |
|------|----------|--------------------|--------|-------|----------------|
| YYYY-MM-DD | What we had to pick | A; B; C | The locked choice | Bot or human | PR / Pages / Notion / path |

Column intent:

| Column | What belongs here |
|--------|-------------------|
| Date | Calendar day the call locked (ISO `YYYY-MM-DD`) |
| Decision | The question, not the answer |
| Options considered | Distinct alternatives, separated by semicolons |
| Chosen | Exactly one value |
| Owner | Who locked it (`Mark`, `Orchestrator`, …) |
| Outcome / link | Proof: PR, Pages, LICENSE path, live-run file |

## Example rows

**EXAMPLE — Grok Bot Hackathon / Hackathon-Builder-Grok_Bot.** Three locked calls from the first Spec-to-ship live-run. Copy the pattern; clear these rows when you start a new kit.

| Date | Decision | Options considered | Chosen | Owner | Outcome / link |
|------|----------|--------------------|--------|-------|----------------|
| 2026-09-04 | Which showcase workflow to run for the hackathon | Spec-to-ship; six chat-tab demo; Zapier-style pipeline; one mega-agent | Spec-to-ship | Orchestrator + Mark | https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot/blob/main/examples/live-run/03-decision-log.md |
| 2026-09-04 | Public GitHub repo name for the kit | grok-bot-spec-to-ship; Hackathon-Grok-Bot-Meetup_Manila; Hackathon-Builder-Grok_Bot | Hackathon-Builder-Grok_Bot | Mark (locked in the hackathon room) | https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot |
| 2026-09-04 | Visibility and license for the entry | private repo; public + proprietary; public + MIT | public + MIT | Mark (human judgment after Reviewer escalation) | https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot/blob/main/LICENSE · Pages https://iron-mark.github.io/Hackathon-Builder-Grok_Bot/ |

### Row notes (example — delete with the rows)

1. **Spec-to-ship winner** — Highest orchestration + Grok Bot showcase value. Viewers see native group handoffs; the PR trail *is* the demo. Not six ChatGPT tabs.
2. **Repo name `Hackathon-Builder-Grok_Bot`** — Locked by Mark in the hackathon room. Spec-to-ship stays the **workflow** name, not the GitHub slug.
3. **Public + MIT** — Venue + crew recommendation after Reviewer escalation. Mark presenting from this repo. LICENSE in git; Pages is the public demo surface.

## Blank row (copy)

| Date | Decision | Options considered | Chosen | Owner | Outcome / link |
|------|----------|--------------------|--------|-------|----------------|
|  |  |  |  |  |  |

## Paste checklist

- [ ] Page or database created in the kit’s Notion workspace
- [ ] Columns match: Date / Decision / Options considered / Chosen / Owner / Outcome / link
- [ ] One decision per row
- [ ] Example rows copied or replaced
- [ ] Outcome cells link to PR or Pages when the decision shipped that way
- [ ] Page URL posted once in the Grok Bot group as SoT
