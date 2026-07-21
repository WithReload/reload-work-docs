# Documentation project instructions

Rules for anyone, human or AI, editing the Reload user guide.

## About this project

- This repository is the source for the Reload user guide, published at `https://reload.work`.
- Pages are MDX files with YAML frontmatter.
- Site configuration lives in `docs.json`: navigation, theme, colors, and links.
- Preview locally as described in `README.md`.

## About the product

Reload is an agentic team operating system. A person signs up, creates a workspace, and meets a Chief of Staff agent that helps them hire a team of AI agents from ready-made persona packs or build bespoke ones. Agents and people work together in chat channels, run tasks and scheduled routines, share a memory and a wiki, connect to outside tools, can be reached over external messaging, and can bring in agents that already run elsewhere. Work is metered in credits.

## Terminology

- Say "workspace", not "project" or "organization".
- Say "member" for a person, "agent" for an AI teammate, and "your team" for the agents you have hired.
- Say "channel" for a chat space, "task" for a tracked piece of work, and "routine" for scheduled work.
- Say "hire" an agent, not "buy" or "install".
- Say "Chief of Staff" for the agent that helps you run the workspace.
- Say "credits" for how work is metered.
- Use the real URLs: the site is `https://reload.work`, the app is `https://app.reload.work`.

## Style preferences

- Write in the second person ("you"), active voice, benefit first.
- Keep sentences short, one idea each. Lead with what the reader does.
- Use sentence case for headings.
- Bold for UI elements: open **Settings**.
- Code formatting for handles, commands, and paths.
- No em dashes, no emoji, no exclamation marks, no hype words.

## Content boundaries

- This is a user guide, not an engineering document. Describe what the reader does and what happens, never how it is built.
- Never name the vendors, services, protocols, model providers, or infrastructure behind a feature. Name the user-facing capability instead, for example "connect Slack" or "reach your agents on WhatsApp".
- Do not document admin-only internals, feature flags, or anything a normal user cannot see or do.
- Do not invent features. If the product does not do it, do not write it.
