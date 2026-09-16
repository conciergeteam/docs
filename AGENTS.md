# Documentation project instructions

## About this project

- This is the Concierge Product Guide, built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `npx mint dev` to preview locally
- Run `npx mint broken-links` to check links
- Source of truth for associate how-tos is the associate app UI (`associate_web_app`). Do not invent buttons.

## Terminology

- **Associate** / **team member** — someone on a customer team using the dashboard
- **Person** / **people** — guests on an event (not "customers" or "users")
- **List** — a named audience (the Lists page may say "groups" in the subtitle)
- **Event** — a Concierge event
- **Broadcast** — a scheduled or immediate outbound message
- **Inbox** — the Messages page (sidebar label Inbox)

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Prefer **How do I …?** H2s so live Mintlify search matches associate questions
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Numbered click paths from the real UI

## Content boundaries

- Document associate-facing dashboard pages only
- Do not document Auth0 sign-in, email verification, or inactive-account recovery
- Do not document account Phone Numbers or Integrations tabs (hidden in the UI)
- Note **Messages Only** / **Assigned Only** / **admin** when a page is hidden or restricted
- Cover import wizards on the parent page, not as separate nav items
