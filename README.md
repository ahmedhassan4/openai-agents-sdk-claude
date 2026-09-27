\# OpenAI Agents SDK with Claude



Hands-on examples of building AI agents using the \*\*OpenAI Agents SDK\*\* with \*\*Claude\*\* as the LLM provider.



\## What This Covers



\* Creating AI agents with Claude

\* Running agents with `Runner`

\* Custom tools with `@function\_tool`

\* External API integration with Pushover

\* Agent tracing with `trace`

\* Conversation context and memory

\* Persistent sessions with `SQLiteSession`



\## Tech Stack



\* Python

\* OpenAI Agents SDK

\* Anthropic Claude

\* OpenAI SDK

\* Pushover

\* SQLite

\* uv



\## Setup



Install the dependencies:



```bash

uv sync

```



Create a `.env` file with your API credentials:



```env

ANTHROPIC\_API\_KEY=your\_anthropic\_api\_key

PUSHOVER\_USER=your\_pushover\_user

PUSHOVER\_TOKEN=your\_pushover\_token

```



Then run the project using your preferred Python environment.



\## Purpose



A practical introduction to the core building blocks of \*\*AI agents, tool calling, external integrations, tracing, and conversation memory\*\* using the OpenAI Agents SDK.



