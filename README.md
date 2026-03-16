# nvms

## Projects

### mesh-kit

Distributed WebSocket server + client built on Redis. Rooms, pub/sub channels with history, versioned records with JSON Patch diffs, presence, collections. Multi-instance routing via Redis pubsub.

### @eaccess/auth

Postgres-backed auth for Express. Sessions, remember-me, email verification, password reset, OAuth (GitHub/Google/Azure), role bitmasks, 2FA (TOTP + email/SMS OTP + backup codes), activity logging.

### @threaded/ai

Composable, provider-agnostic LLM workflow library. Functional pipelines over immutable conversation contexts. Supports OpenAI, Anthropic, Gemini, xAI, Ollama. Tool execution with approval, streaming, structured outputs, threads, embeddings, image generation, MCP integration.

### trend

Terminal UI renderer with JSX components and SolidJS-style signals. Direct-mode rendering with flexbox layout, double-buffered cell diffing, and minimal ANSI output. Zero dependencies.

### prsm

Small, focused utilities. All ESM, zero or minimal dependencies.

| Package | Description |
|---------|-------------|
| @prsm/queue | Redis-backed distributed task queue with per-tenant grouped concurrency |
| @prsm/limit | Redis-backed rate limiting - token bucket, sliding window, leaky bucket |
| @prsm/from | Fluent, immutable query builder for arrays of objects |
| @prsm/fsm | Non-deterministic finite state machine with persistence |
| @prsm/hash | Salted string hashing with self-describing hash format |
| @prsm/ids | Reversible integer-to-short-string obfuscation |
| @prsm/ms | Human-friendly time expression parser |
