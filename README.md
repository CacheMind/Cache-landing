# Cache — Save anything. Your AI remembers it.

Cache is a personal memory layer for AI. Save articles, tweets, videos, PDFs, and highlights from anywhere — and every AI you use (ChatGPT, Claude, Cursor) automatically gets the context it needs.

🌐 **Live:** [cachemind.github.io/Cache-landing](https://cachemind.github.io/Cache-landing/)

## How it works

1. **Save anything** — One click or keyboard shortcut from any website
2. **Cache processes it** — Automatic summarization, key-point extraction, and semantic embedding
3. **Your AI just knows** — When you ask ChatGPT or Claude anything, Cache finds relevant saved content and injects it automatically

## The problem

Power users consume content all day — articles, threads, papers, videos. When they later talk to AI, none of that context is available. They either copy-paste (high friction), describe from memory ("there was this article…"), or accept generic answers.

Cache closes that gap automatically.

## Tech stack

- **Extension:** Chrome MV3
- **Backend:** Cloudflare Workers + Supabase (Postgres + pgvector)
- **AI:** OpenAI text-embedding-3-small (embeddings), GPT-4o-mini (summarization)
- **Integration:** MCP (Model Context Protocol) for vendor-neutral AI access

## Status

🚧 Pre-launch — actively building. Join the waitlist on the landing page.

## License

MIT © 2026 CacheMind
