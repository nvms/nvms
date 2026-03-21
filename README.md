# nvms

Hello.

## Projects

### [@eaccess/auth](https://github.com/nvms/eaccess)

Postgres-backed auth for Express. Sessions, remember-me, email verification, password reset, OAuth (GitHub/Google/Azure), role bitmasks, 2FA (TOTP + email/SMS OTP + backup codes), activity logging.

### [@threaded/ai](https://github.com/nvms/threaded)

Composable, provider-agnostic LLM workflow library. Functional pipelines over immutable conversation contexts. Supports OpenAI, Anthropic, Gemini, xAI, Ollama. Tool execution with approval, streaming, structured outputs, threads, embeddings, image generation, MCP integration.

### [trend](https://github.com/nvms/trendr)

Terminal UI renderer with JSX components and SolidJS-style signals. Direct-mode rendering with flexbox layout, double-buffered cell diffing, and minimal ANSI output. Zero dependencies.

### prsm

Small, focused utilities. All ESM, zero or minimal dependencies.

| Package | | | Description |
|---------|---|---|-------------|
| [@prsm/realtime](https://github.com/nvms/realtime) | ![test](https://github.com/nvms/realtime/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/realtime) | Distributed WebSocket framework with Redis-backed rooms, records, presence, channels, collections, and persistence |
| [@prsm/devtools](https://github.com/nvms/devtools) | | ![npm](https://img.shields.io/npm/v/@prsm/devtools) | Read-only Express middleware dashboard for observing @prsm infrastructure at runtime |
| [@prsm/cron](https://github.com/nvms/cron) | ![test](https://github.com/nvms/cron/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/cron) | Redis-backed distributed cron scheduler with leader election and cron expression support |
| [@prsm/queue](https://github.com/nvms/queue) | ![test](https://github.com/nvms/queue/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/queue) | Redis-backed distributed task queue with per-tenant grouped concurrency |
| [@prsm/lock](https://github.com/nvms/lock) | ![test](https://github.com/nvms/lock/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/lock) | Distributed locking primitives for Redis - mutex and semaphore |
| [@prsm/cells](https://github.com/nvms/cells) | ![test](https://github.com/nvms/cells/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/cells) | Reactive computation graph with async-first distributed coordination via Redis |
| [@prsm/limit](https://github.com/nvms/limit) | ![test](https://github.com/nvms/limit/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/limit) | Redis-backed rate limiting - token bucket, sliding window, leaky bucket |
| [@prsm/from](https://github.com/nvms/from) | ![test](https://github.com/nvms/from/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/from) | Fluent, immutable query builder for arrays of objects |
| [@prsm/fsm](https://github.com/nvms/fsm) | ![test](https://github.com/nvms/fsm/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/fsm) | Non-deterministic finite state machine with persistence |
| [@prsm/workflow](https://github.com/nvms/workflow) | ![test](https://github.com/nvms/workflow/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/workflow) | Durable workflow engine with explicit steps, persisted execution state, retries, and inspectable history |
| [@prsm/hash](https://github.com/nvms/hash) | ![test](https://github.com/nvms/hash/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/hash) | Salted string hashing with self-describing hash format |
| [@prsm/ids](https://github.com/nvms/ids) | ![test](https://github.com/nvms/ids/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/ids) | Reversible integer-to-short-string obfuscation |
| [@prsm/ms](https://github.com/nvms/ms) | ![test](https://github.com/nvms/ms/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/ms) | Human-friendly time expression parser |
