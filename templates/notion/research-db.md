# Research Database (template)

Paste-ready page body — not an outline. Create a Notion **database** with the properties below, then duplicate this page as the schema/instructions page (or paste it into a database **template** so every new row starts with the same body).

Keep **full** research in this database. In the Grok Bot group, post only a ≤5-line summary + link.

## How to use

1. In Notion, create a **full-page database** named `Research`.
2. Add every property in **Database properties** (name + type must match; Select options must be exact).
3. Open this markdown, copy the body, paste into a Notion page next to the database — or set it as the database **template** for new entries.
4. Copy the two **example rows** into the database so the crew can see a filled pattern, then archive them when you start a new kit.
5. Researcher owns rows until `Status = Ready`. Reviewer does **one pass** vs sources, not vibes.

## Database properties

Create these columns on the Notion database:

| Property | Type | Notes |
|----------|------|-------|
| Title | Title | Claim or research question |
| Question | Text | What we need to learn |
| Sources | URL / multi | Official docs first |
| Verdict | Select | Confirmed / Needs connector / Unsupported / Open |
| Evidence | URL / text | Link to live-run or Notion page |
| Owner | Person / text | Bot or human |
| Status | Select | Draft / Ready / Stale |

### Type notes (Notion)

- **Title** — the default Name column. Rename it to `Title` if you want the header to match this table.
- **Sources — URL / multi** — Notion’s URL property is one link. For several official docs, use **Text** (paste URLs) or a **Files & media** / related-page pattern. Prefer official docs first.
- **Evidence — URL / text** — use **URL** when you have one live-run or Notion link; use **Text** if you need a path plus a short cite.
- **Owner — Person / text** — use **Person** for humans in the workspace; use **Text** for Bot names (`Researcher`, `GBot Builder3`).
- **Verdict** Select options (create all four): `Confirmed`, `Needs connector`, `Unsupported`, `Open`.
- **Status** Select options (create all three): `Draft`, `Ready`, `Stale`.

## Example rows

**EXAMPLE — Spec-to-ship / Hackathon-Builder-Grok_Bot.** Copy these two rows into the database, then clear or archive them when you reuse the template.

| Title | Question | Sources | Verdict | Evidence | Owner | Status |
|-------|----------|---------|---------|----------|-------|--------|
| Grok Bot groups support 2–6 named Bots with `@` routing | Can a native Grok Bot group (not six chat tabs) run Spec-to-ship with 2–6 persistent Bots and visible `@Bot` / `@everyone` handoffs? | https://docs.x.ai/grok-bot | Confirmed | https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot/blob/main/examples/live-run/01-capabilities.md | Researcher | Ready |
| Localhost / stdio MCP is unsupported for Grok Bot Plugins | Can Day-1 Spec-to-ship attach a local MCP server (localhost or stdio) for Notion/GitHub structured ops? | https://docs.x.ai/grok-bot | Unsupported | https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot/blob/main/examples/live-run/01-capabilities.md | Researcher | Ready |

### Example row 1 — Confirmed (group 2–6)

- **Title:** Grok Bot groups support 2–6 named Bots with `@` routing
- **Question:** Can a native Grok Bot group (not six chat tabs) run Spec-to-ship with 2–6 persistent Bots and visible `@Bot` / `@everyone` handoffs?
- **Sources:** https://docs.x.ai/grok-bot (FAQ, chat-and-collaboration)
- **Verdict:** Confirmed
- **Evidence:** https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot/blob/main/examples/live-run/01-capabilities.md
- **Owner:** Researcher
- **Status:** Ready

Native facts locked on the live-run: persistent named Bots, shared cloud computer, group chats **2–6** Bots, async Bot→Bot handoffs, skills + routines. Do not design around “unlimited parallel GUI on one screen.”

### Example row 2 — Unsupported (localhost MCP)

- **Title:** Localhost / stdio MCP is unsupported for Grok Bot Plugins
- **Question:** Can Day-1 Spec-to-ship attach a local MCP server (localhost or stdio) for Notion/GitHub structured ops?
- **Sources:** https://docs.x.ai/grok-bot (Plugins) + Cursor forum on MCP
- **Verdict:** Unsupported
- **Evidence:** https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot/blob/main/examples/live-run/01-capabilities.md
- **Owner:** Researcher
- **Status:** Ready

Needs connector/MCP (separate claims, not this row): Notion, Drive, GitHub **structured** ops prefer a connector over the browser. Remote **HTTPS** MCP only. Slack/GitHub *event* routines use Cursor account integrations. Inventing X/Context7 without a live Plugin is out of scope.

## New-entry body (database template)

Paste this block into the Notion database **template** so every new research row has a place for the write-up. Room posts stay ≤5 lines + this page’s URL.

### Claim

_One sentence. What we believe or need to prove._

### Question

_What we need to learn. One question per row._

### Sources

- Official docs first:
- Secondary (forums, SDKs) only after docs:

### Evidence

_Link to live-run file, PR, or this Notion page’s child notes._

### Verdict rationale

_Confirmed / Needs connector / Unsupported / Open — and why. Cite the source, not chat memory._

### Handoff

- [ ] Verdict set
- [ ] Evidence URL filled
- [ ] Status = Ready
- [ ] `@NextBot` in the group with this page link + DoD, then stop

## Paste checklist for creating the DB in Notion

- [ ] New full-page database named `Research` in the kit’s Notion workspace
- [ ] Property `Title` exists (Title type) — claim or research question
- [ ] Property `Question` (Text)
- [ ] Property `Sources` (URL, or Text if you need multiple links)
- [ ] Property `Verdict` (Select) with options: Confirmed / Needs connector / Unsupported / Open
- [ ] Property `Evidence` (URL or Text)
- [ ] Property `Owner` (Person or Text)
- [ ] Property `Status` (Select) with options: Draft / Ready / Stale
- [ ] This page body pasted as a sibling page **or** saved as the database template
- [ ] Two example rows copied in (group 2–6 = Confirmed; localhost MCP = Unsupported)
- [ ] Database URL posted once in the Grok Bot group as SoT (not as a dump)
- [ ] Example rows archived when the crew starts a new kit
