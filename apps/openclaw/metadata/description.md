## OpenClaw

OpenClaw is a powerful self-hosted personal AI assistant that runs on your own server 24/7.

### Features

- **Multi-channel support**: Connect via WhatsApp, Telegram, Slack, Discord, iMessage and more
- **Model-agnostic**: Works with Claude (Anthropic), GPT (OpenAI), Gemini, Mistral, Groq, and local LLMs
- **Autonomous tasks**: Send emails, manage calendars, browse the web, run terminal commands
- **Memory & context**: Persistent memory across conversations
- **Secure sandbox**: Runs in Docker with isolated agent execution

### Setup

1. Install and open the app
2. Log in with your Setup Password
3. Complete the onboarding wizard to connect your messaging channels
4. Add your LLM API key (Anthropic, OpenAI, etc.)

### Notes

- Requires at least **2 GB RAM**
- Data is persisted in the app data directory
- Web UI runs on port 8080 (proxied by nginx)
