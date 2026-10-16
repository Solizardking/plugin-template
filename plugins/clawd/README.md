# Clawd for Cursor

Clawd is a Solana agent toolkit: a six-law safety harness, a paper-first OODA trading loop, market-data MCP servers and a catalog of ready agents. Live trading is never on by default. Every swap or order passes a confirmation hook first.

## What's included
- `rules/`: safety harness, Go runtime standards, trading safety, MoonPay URL signing
- `skills/`: runtime, trading, catalog, Cheshire Terminal, MoonPay widget URLs
- `agents/`: constitution reviewer, trading-risk reviewer
- `commands/`: catalog, paper OODA sim, release check, spawn, discovery, MoonPay sign
- `hooks/hooks.json`: formatting after edits, confirmation before swaps and risky shell
- `mcp.json`: hosted MCP servers only (Solana docs, Cheshire Terminal)
- `mcp.local.example.json`: optional local servers for people running the Clawd stack themselves

## Setup
1. Install the plugin from the marketplace.
2. Optional: set `CHESHIRE_API_KEY` to use the authenticated Cheshire MCP.
3. Optional: merge entries from `mcp.local.example.json` into your MCP config and set the matching `*_ROOT` paths.

## Links
- Site: https://musebook.trade
- Live paper desk: https://fomo.musebook.trade/paper
- Arena: https://fomo.musebook.trade/arena

## License
MIT
