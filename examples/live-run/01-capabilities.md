# Confirmed Grok Bot capabilities (live-run)

Sources: docs.x.ai/grok-bot (FAQ, chat-and-collaboration, computer-and-apps, skills-routines, approvals) + Cursor forum on MCP.

## Confirmed native
- Persistent named Bots (profile + per-Bot memory/conversation)
- Shared account cloud computer (files/browser/logins — not a security boundary)
- Group chats 2–6 Bots; `@Bot` / `@everyone` / natural routing
- Async Bot→Bot handoffs (visible); parallel work (one computer-use task per Bot screen)
- Skills (shared) + routines (schedule or Cursor event triggers)
- Browser + terminal + filesystem; approvals/Auto-review; human takeover for password/2FA/CAPTCHA
- Teach-a-task → draft skill; Bot share links (config only)

## Needs connector/MCP
- Notion, Drive, GitHub structured ops — prefer connector over browser
- Remote HTTPS MCP only; localhost/stdio MCP unsupported for Plugins
- Slack/GitHub *event* routines use Cursor account integrations

## Do not design around
- Bots as isolation; Bot→group attachments (text-only today)
- Memory as source of truth; unlimited parallel GUI on one screen
- Inventing X/Context7 without a live Plugin
