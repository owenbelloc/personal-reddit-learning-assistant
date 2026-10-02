# Personal Reddit Learning Assistant

## Project status
Planning stage. Reddit API access is being requested. No Reddit API integration has been implemented, and this repository currently contains documentation only.

## Purpose
A personal, non-commercial, read-only tool to help me learn about machining and CNC by finding and reading public discussions in r/Machinists and r/CNC.

## Planned functionality
- Search public posts in the approved communities when I explicitly request it.
- Retrieve selected posts and comments.
- Provide selected text to OpenAI Codex for reading assistance and summarization.
- Include original Reddit links so I can check the source discussions.

## Intended architecture
OpenAI Codex would use a locally operated connector, potentially an MCP server, to call the Reddit Data API using approved OAuth access. The connector has not yet been selected or implemented.

## Scope and data handling
The tool is intended only for my own learning, with occasional, user-initiated requests. It will not post, comment, vote, send messages, access private communities, or build user profiles.

It is not intended for bulk collection, commercial use, or model training or fine-tuning. Before implementation, I will review the AI service's data-use settings and ensure that processing, retention, and deletion comply with Reddit's approval and applicable requirements.

Implementation and API use will proceed only after Reddit grants the required access.
