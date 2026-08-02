# 🐦 Birb

Birb is a Discord staff-management bot for moderation, activity tracking, tickets, and community workflows.

## Features

- Tickets and modmail
- Staff activity quotas and leaderboards
- Leave-of-absence tracking
- Daily questions
- Roblox Group and ERM integrations
- Staff punishments, suspensions, and promotions
- Forums, feedback, suggestions, and auto-responses
- Staff list and staff panel
- Custom commands and connection roles

## Staff commands

These commands are available when the user ID is included in the `STAFF` environment variable:

- `!!guilds`
- `!!leave`
- `!!whitelist`
- `!!unwhitelist`
- `!!sync` (owner only)

## Run locally

Birb is a Python bot. Create a virtual environment, install the dependencies, configure the required environment variables, and start the bot:

```bash
python -m venv .venv
.venv\Scripts\activate  # Windows
python -m pip install -r requirements.txt
python main.py
```

`main.py` loads environment variables with `python-dotenv`. Keep bot tokens, database URLs, and service credentials in a secret manager or local `.env` file; never commit them.

## License

Birb © 2023 Bugsbirb.

Licensed under the Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International license (CC BY-NC-SA 4.0). See [`LICENSE`](./LICENSE).