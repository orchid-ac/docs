# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- "connection key" (`osk_...`), not "API key": an Orchid API key is a person's, for model calls.
- "event", "kind", "thread", "content", as in getting-started/concepts.mdx.
- "counted", "estimated", "reported" for where a figure comes from.
- Console locations in bold with › : **Admin › Developers**.

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document only what the developer API does today, read from orchid-conductor's code. Nothing planned.
- No client names, no real people, no figures presented as real: examples are illustrations.
- Nothing internal: no infrastructure, no Orchid's own deployment details, nothing from the private handbook.
- The old model API, CLI, IDE integrations and self-hosting guides are retired; their URLs redirect.
