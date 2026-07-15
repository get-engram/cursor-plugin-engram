# Engram — Persistent Memory for AI Agents

Give your AI coding agent long-term memory. Engram stores complete conversation transcripts and makes them searchable via semantic search, so your agent remembers decisions, bugs, and context across sessions.

## What it does

- **Search** past conversations with natural language queries
- **Store** decisions, bug investigations, and architecture discussions
- **Recall** context automatically at the start of every session
- **Share** memory across agents and team members

## Setup

1. Install the plugin from the Cursor Marketplace
2. Get an API key at [getengram.app](https://getengram.app/signup?ref=cursor)
3. Add your API key to Cursor settings:
   - Open Settings > MCP
   - Set `ENGRAM_API_KEY` to your key

## MCP Tools

| Tool | Description |
|------|-------------|
| `search` | Semantic search across all stored conversations |
| `create_conversation` | Start a new conversation record |
| `append_messages` | Add messages to an existing conversation |
| `list_conversations` | Browse stored conversations |
| `get_conversation` | Retrieve a full conversation with messages |
| `delete_conversation` | Remove a conversation |

## Usage

The plugin automatically instructs your agent to:
- Search Engram for relevant context when you start a task
- Store important decisions and work as you go

You can also invoke `/engram <query>` to manually search your memory.

## Links

- [Website](https://getengram.app)
- [Documentation](https://getengram.app/docs)
- [GitHub](https://github.com/get-engram/engram)
