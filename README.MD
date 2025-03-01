# Archipylago Python meetup demo project

For a meetup held in March 2025

## Setup

```bash
uv sync
touch .env
# Add OPENAI_API_KEY to .env
# Add AZURE_OPENAI_API_BASE, AZURE_OPENAI_API_KEY to .env (or edit the litellm-config to drop them)
# Add GEMINI_API_KEY to .env (or edit the litellm-config to use OpenAI)
# Add TRACELOOP_API_KEY to .env (optional)
```

## Run

```bash
docker-compose up -d
UV_ENV_FILE=.env uv run poker.py
```

