# Orchid developer docs

The public docs for Orchid's developer API: sending your own agents' and systems' events to Orchid,
reading the record and your figures with code, and acting on what happens (webhooks, alerts, insight
actions, AI employee runs). Built with [Mintlify](https://mintlify.com).

The API itself is in `orchid-conductor` (`app/developer.py`, `app/sources.py`, `app/subscriptions.py`,
`app/events.py`); its engineering notes are `docs/developer-api.md` there. When the API changes, change
these pages in the same week.

## Preview

```bash
npm i -g mint
mint dev
```

`mint broken-links` checks every link.

## Layout

- `getting-started/` -- quickstart, keys and scopes, concepts, deployments
- `send/` -- events, event types, agents, the audit record, contents
- `read/` -- the record, metrics and agents, cost and savings, alerts
- `act/` -- webhooks, working alerts, insight actions, AI employee runs
- `reference/` -- every endpoint, every event kind, errors and limits
