# Reload documentation

This repository holds the source for the Reload user guide, published at [reload.work](https://reload.work).

Reload is an agentic team operating system. You create a workspace, meet a Chief of Staff, and hire a team of AI agents that work alongside you in chat channels. Together you run tasks and scheduled routines, share a memory and a wiki, connect the tools you already use, and reach your agents wherever you work. Work is metered in credits.

## What is here

- `*.mdx` — the guide pages, written in Markdown with frontmatter.
- `docs.json` — site configuration: navigation, theme, colors, and links.
- `logo/`, `favicon.svg` — brand assets for the site.
- `AGENTS.md` — writing and content rules for anyone, human or AI, editing these docs.

## Preview locally

Install the preview CLI, then run it from the repo root where `docs.json` lives:

```bash
npm i -g mint
mint dev
```

The preview opens at `http://localhost:3000`.

## Making changes

- Edit or add `.mdx` pages, then register new pages in the `navigation` section of `docs.json`.
- Read `AGENTS.md` first. It covers the terminology, voice, and content boundaries these docs must follow.
- Open a pull request for review. Changes merged to `main` are published automatically.

## Support

Questions about the product go to [support@reload.work](mailto:support@reload.work).
