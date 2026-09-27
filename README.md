# OpenAI Agents SDK with Claude

Hands-on examples of building AI agents using the **OpenAI Agents SDK** with **Claude** as the LLM provider.

## What This Covers

* Creating AI agents with Claude
* Running agents with `Runner`
* Custom tools with `@function_tool`
* External API integration with Pushover
* Agent tracing with `trace`
* Conversation context and memory
* Persistent sessions with `SQLiteSession`

## Tech Stack

* Python
* OpenAI Agents SDK
* Anthropic Claude
* OpenAI SDK
* Pushover
* SQLite
* uv

## Setup

Install the dependencies:

```bash
uv sync
```

Create a `.env` file with your API credentials:

```env
ANTHROPIC_API_KEY=your_anthropic_api_key
PUSHOVER_USER=your_pushover_user
PUSHOVER_TOKEN=your_pushover_token
```

Then run the project using your preferred Python environment.

## Purpose

A practical introduction to the core building blocks of **AI agents, tool calling, external integrations, tracing, and conversation memory** using the OpenAI Agents SDK.
