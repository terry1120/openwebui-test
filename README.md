# Open WebUI Test Environment

This is a test environment for Open WebUI.

## Setup

1. Copy the environment file and configure your API keys:
   ```bash
   cp .env.example .env
   ```

2. Edit `.env` file with your OpenAI API key or Ollama configuration.

3. Start the service:
   ```bash
   docker-compose up -d
   ```

4. Access Open WebUI at: http://localhost:3000

## Stop the service

```bash
docker-compose down
```

## View logs

```bash
docker-compose logs -f open-webui
```
