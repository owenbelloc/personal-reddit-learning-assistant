# Personal Reddit Learning Assistant

A minimal, read-only UI prototype for a personal Reddit learning tool.

## Status

**Mock-data prototype only.** Reddit API access is being requested. No live Reddit or OpenAI integration is implemented. All example posts and comments are invented and are not copied from Reddit. This repository does not prove API approval or an authenticated connection.

## Run

Download the repository and open `index.html` in a modern browser. No installation, API keys, or build step is required.

## Implemented

- Keyword filtering across mock titles, bodies, and comments.
- Filtering for the planned communities: r/Machinists and r/CNC.
- Expandable example comments and a no-results state.
- Visible disclosure of prototype status, intended access scope, and data handling.

## Intended use

Occasional, user-initiated personal learning about machining and CNC. No commercial service, automated posting, commenting, voting, messaging, private content access, or user profiling is planned.

## Future architecture — not implemented

OpenAI Codex → local read-only connector (potentially MCP) → approved Reddit Data API OAuth access.

Selected public text would be supplied to OpenAI Codex for reading assistance and summarization, with original post links. Reddit must approve the proposed use and any applicable AI processing before live access. The connector would need to implement approved scopes, rate limits, secure credential storage, and applicable retention/deletion requirements. AI service data-use settings must also be reviewed.

## Current privacy behavior

The demo makes no network requests and uses no analytics, cookies, local storage, or server. Searches are processed locally in memory. Clicking the explicitly labeled community links navigates to Reddit normally.

## Manual verification

Open the demo; search `chatter` (one result), choose CNC (no matching result), clear the query (two CNC results), and expand comments. Search HTML-like text to confirm it displays only as input and is not interpreted as markup.

## API application

This repository documents the proposal and demonstrates the local UI. It contains no live API implementation. Approval is not guaranteed. Only access Reddit data after the required explicit approval.
