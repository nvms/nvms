# nvms

Hello.

## Projects

### [mesh-kit](https://github.com/nvms/mesh)

Distributed WebSocket server + client built on Redis. Rooms, pub/sub channels with history, versioned records with JSON Patch diffs, presence, collections. Multi-instance routing via Redis pubsub.

### [@eaccess/auth](https://github.com/nvms/eaccess)

Postgres-backed auth for Express. Sessions, remember-me, email verification, password reset, OAuth (GitHub/Google/Azure), role bitmasks, 2FA (TOTP + email/SMS OTP + backup codes), activity logging.

### [@threaded/ai](https://github.com/nvms/threaded)

Composable, provider-agnostic LLM workflow library. Functional pipelines over immutable conversation contexts. Supports OpenAI, Anthropic, Gemini, xAI, Ollama. Tool execution with approval, streaming, structured outputs, threads, embeddings, image generation, MCP integration.

### [trend](https://github.com/nvms/trendr)

Terminal UI renderer with JSX components and SolidJS-style signals. Direct-mode rendering with flexbox layout, double-buffered cell diffing, and minimal ANSI output. Zero dependencies.

### prsm

Small, focused utilities. All ESM, zero or minimal dependencies.

| Package | Description |
|---------|-------------|
| [@prsm/cron](https://github.com/nvms/cron) | Redis-backed distributed cron scheduler with leader election and cron expression support |
| [@prsm/queue](https://github.com/nvms/queue) | Redis-backed distributed task queue with per-tenant grouped concurrency |
| [@prsm/limit](https://github.com/nvms/limit) | Redis-backed rate limiting - token bucket, sliding window, leaky bucket |
| [@prsm/from](https://github.com/nvms/from) | Fluent, immutable query builder for arrays of objects |
| [@prsm/fsm](https://github.com/nvms/fsm) | Non-deterministic finite state machine with persistence |
| [@prsm/workflow](https://github.com/nvms/workflow) | Durable workflow engine with explicit steps, persisted execution state, retries, and inspectable history |
| [@prsm/hash](https://github.com/nvms/hash) | Salted string hashing with self-describing hash format |
| [@prsm/ids](https://github.com/nvms/ids) | Reversible integer-to-short-string obfuscation |
| [@prsm/ms](https://github.com/nvms/ms) | Human-friendly time expression parser |
