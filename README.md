# AutoServer

Talk to your VPS. An AI installer plus skills (panels, bots, and more) that run on your machine.

An AI installer and operator as root user that runs on your machine.

## Install

1. Create an free API key at [autoserver.org](https://autoserver.org).
2. On your linux VPS as root:

```bash
curl -fsSL https://autoserver.org/install.sh | bash -s -- --key as_live_xxxx
```

Do not `git clone` this repository onto the server.

## What you get

- Chat UI on the VPS Server to inspect and change the server
- BYOK models: OpenAI, Groq, Gemini, Claude, OpenRouter, or local Ollama
- Skills framework
- Give any command to your AI to manage the server.

## Safety

Root access via AI is powerful and dangerous. Use a strong password, HTTPS, and keep keys private. See security notes.

⚠️ WARNING: AI Has Full Root Access
You are giving an AI full root access to your VPS.

The AI can execute commands, modify or delete files, change configurations, stop services, and potentially damage or completely disable your server.

Use only an AI model you fully trust.

You are solely responsible for all actions performed by the AI. Any loss, damage, data loss, or downtime is entirely at your own risk.

Your server. Your rules. Your responsibility.

## License

See [LICENSE](LICENSE). Copying, redistributing, or reselling this product is not allowed.
