# @officeos/skill-google

Google Workspace integration skill for [Office OS](https://github.com/officeos-co) — Google Calendar and Gmail operations.

## Install

```bash
eaos skill install google
```

Or from the Office OS dashboard under **Skills > Install**.

## Actions

- `list_events` — List upcoming calendar events
- `create_event` — Create a calendar event
- `list_messages` — List recent Gmail messages
- `send_message` — Send an email via Gmail

## Credentials

- **OAuth Client ID** and **Client Secret** — Create at [Google Cloud Console](https://console.cloud.google.com/apis/credentials)

## Development

```bash
npm install
# Skill is defined in skill.ts using @officeos/skill-sdk
```

## License

MIT
