# Настройка локального ИИ (Local LLM)

ИИ запускается в Docker (Ollama / Local LLM Server) и связывается с Home Assistant через интеграцию **Local OpenAI LLM**.

## Параметры Conversation Agent

- **Model:** `home-agent`
- **Temperature:** `0.6`
- **Max message history:** `0` (без ограничений)
- **Parallel tool calling:** Включено

## Системный промпт (System Prompt)

```text
You are a voice assistant for Home Assistant.
Answer questions about the world truthfully.
Answer in plain text. Keep it simple and to the point.