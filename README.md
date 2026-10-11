# Sarvam Personal Call Assistant

Minimal Sarvam chat API example and configuration notes for a browser voice prototype.

## Run the chat example

```sh
python3 -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
```

Create `.env` with `SARVAM_API_KEY=` and add your key locally. Then run:

```sh
.venv/bin/python chat.py
```

The script uses `sarvam-105b-conversations` and prints the reply. The first API call succeeded with `Hello!`. `.env` and `.venv/` are excluded from Git.

## Browser voice prototype

The hosted agent is configured in Sarvam Voice Agents. See [assistant.md](assistant.md) for its greeting, instructions, and test steps. This repository documents that configuration; it does not deploy or run the hosted voice agent locally.

No phone number was purchased. Phone transfers, calendar integration, persisted summaries, and notifications are not implemented. Live browser audio has not been verified by this project.
