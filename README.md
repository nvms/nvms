# nvms

Hello.

## Projects

### [trend](https://github.com/nvms/trendr)

Terminal UI renderer with JSX components and SolidJS-style signals. Direct-mode rendering with flexbox layout, double-buffered cell diffing, and minimal ANSI output.

### [pico](https://github.com/nvms/pico)

![npm](https://img.shields.io/npm/v/picocode)

Terminal-native coding agent with multi-provider model support, persistent and rewindable sessions, project-aware instructions, integrated development tools, MCP integration, and extensible commands and skills. Built with [trend](https://github.com/nvms/trendr) and [@prsm/ai](https://github.com/prsmjs/ai).

### [siggie](https://github.com/nvms/siggie)

![npm](https://img.shields.io/npm/v/siggie)

Small, high-performance reactive runtime for JavaScript with signals, lazy computed values, effects, batching, and dynamic dependency tracking.

### [prsm](https://github.com/prsmjs)

Small, focused utilities. All ESM.

| Package | | | Description |
|---------|---|---|-------------|
| [@prsm/ai](https://github.com/prsmjs/ai) | ![test](https://github.com/prsmjs/ai/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/ai) | Composable LLM inference with multi-provider support, tool execution, streaming, structured output, and approval workflows |
| [@prsm/auth](https://github.com/prsmjs/auth) | ![test](https://github.com/prsmjs/auth/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/auth) | PostgreSQL-backed Express authentication: sessions, OAuth, roles, two-factor, and audited impersonation |
| [@prsm/cache](https://github.com/prsmjs/cache) | ![test](https://github.com/prsmjs/cache/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/cache) | Distributed cache with stampede prevention, stale-while-revalidate, and tag invalidation |
| [@prsm/cells](https://github.com/prsmjs/cells) | ![test](https://github.com/prsmjs/cells/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/cells) | Reactive computation graph with async-first distributed coordination via Redis |
| [@prsm/cron](https://github.com/prsmjs/cron) | ![test](https://github.com/prsmjs/cron/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/cron) | Redis-backed distributed cron scheduler with leader election and cron expression support |
| [@prsm/devtools](https://github.com/prsmjs/devtools) | | ![npm](https://img.shields.io/npm/v/@prsm/devtools) | Read-only Express middleware dashboard for observing @prsm infrastructure at runtime |
| [@prsm/embed](https://github.com/prsmjs/embed) | ![test](https://github.com/prsmjs/embed/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/embed) | Text embeddings with multi-provider support, batching, and cosine similarity |
| [@prsm/entitle](https://github.com/prsmjs/entitle) | ![test](https://github.com/prsmjs/entitle/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/entitle) | Plan-based entitlements and feature gating, resolved at runtime, backed by postgres |
| [@prsm/from](https://github.com/prsmjs/from) | ![test](https://github.com/prsmjs/from/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/from) | Fluent, immutable query builder for arrays of objects |
| [@prsm/fsm](https://github.com/prsmjs/fsm) | ![test](https://github.com/prsmjs/fsm/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/fsm) | Non-deterministic finite state machine with persistence |
| [@prsm/hash](https://github.com/prsmjs/hash) | ![test](https://github.com/prsmjs/hash/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/hash) | Salted string hashing with self-describing hash format |
| [@prsm/ids](https://github.com/prsmjs/ids) | ![test](https://github.com/prsmjs/ids/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/ids) | Reversible integer-to-short-string obfuscation |
| [@prsm/imagegen](https://github.com/prsmjs/imagegen) | ![test](https://github.com/prsmjs/imagegen/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/imagegen) | Image generation across OpenAI, xAI, and Google with normalized options and raw provider passthrough |
| [@prsm/limit](https://github.com/prsmjs/limit) | ![test](https://github.com/prsmjs/limit/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/limit) | Redis-backed rate limiting - token bucket, sliding window, leaky bucket |
| [@prsm/lock](https://github.com/prsmjs/lock) | ![test](https://github.com/prsmjs/lock/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/lock) | Distributed locking primitives for Redis - mutex and semaphore |
| [@prsm/log](https://github.com/prsmjs/log) | ![test](https://github.com/prsmjs/log/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/log) | Structured logging with child contexts |
| [@prsm/meter](https://github.com/prsmjs/meter) | ![test](https://github.com/prsmjs/meter/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/meter) | Durable usage metering for billing and quotas, backed by postgres |
| [@prsm/ms](https://github.com/prsmjs/ms) | ![test](https://github.com/prsmjs/ms/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/ms) | Human-friendly time expression parser |
| [@prsm/queue](https://github.com/prsmjs/queue) | ![test](https://github.com/prsmjs/queue/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/queue) | Redis-backed distributed task queue with per-tenant grouped concurrency |
| [@prsm/realtime](https://github.com/prsmjs/realtime) | ![test](https://github.com/prsmjs/realtime/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/realtime) | Distributed WebSocket framework with Redis-backed rooms, records, presence, channels, collections, and persistence |
| [@prsm/trace](https://github.com/prsmjs/trace) | ![test](https://github.com/prsmjs/trace/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/trace) | Distributed trace propagation with W3C TraceContext, AsyncLocalStorage, and framework adapters |
| [@prsm/workflow](https://github.com/prsmjs/workflow) | ![test](https://github.com/prsmjs/workflow/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/workflow) | Durable workflow engine with explicit steps, persisted execution state, retries, and inspectable history |

### [gridwork](https://github.com/gridworkjs)

Composable spatial data structures for JavaScript. Every index implements the same query interface - learn one API, pick the data structure that fits your access pattern.

| Package | | | Description |
|---------|---|---|-------------|
| [@gridworkjs/core](https://github.com/gridworkjs/core) | ![test](https://github.com/gridworkjs/core/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/core) | Geometry primitives (point, rect, circle) and spatial index protocol |
| [@gridworkjs/quadtree](https://github.com/gridworkjs/quadtree) | ![test](https://github.com/gridworkjs/quadtree/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/quadtree) | Quadtree spatial index for sparse, uneven point and region data |
| [@gridworkjs/rtree](https://github.com/gridworkjs/rtree) | ![test](https://github.com/gridworkjs/rtree/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/rtree) | R-tree spatial index with bulk loading for rectangles and polygons |
| [@gridworkjs/hashgrid](https://github.com/gridworkjs/hashgrid) | ![test](https://github.com/gridworkjs/hashgrid/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/hashgrid) | Spatial hash grid for uniform distributions and fast neighbor lookups |
| [@gridworkjs/kd](https://github.com/gridworkjs/kd) | ![test](https://github.com/gridworkjs/kd/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/kd) | KD-tree for static point sets and nearest-neighbor queries |
| [@gridworkjs/query](https://github.com/gridworkjs/query) | ![test](https://github.com/gridworkjs/query/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/query) | Higher-level queries (radius, knn, ray, within) against any index |

### [sigwatch](https://github.com/nvms/sigwatch)

![test](https://github.com/nvms/sigwatch/actions/workflows/ci.yml/badge.svg)

Live game state inspector. TUI application for real-time process memory visualization, built on procmod.

### [schism](https://github.com/nvms/schism)

![ci](https://github.com/nvms/schism/actions/workflows/ci.yml/badge.svg)

Spectral fractal path tracer. Renders 3D fractal geometry using SDF raymarching and physically-based spectral path tracing via Vulkan compute shaders. Deterministic seed-based output.

### [ridgeview](https://github.com/nvms/ridgeview)

![ci](https://github.com/nvms/ridgeview/actions/workflows/ci.yml/badge.svg)

Interactive 3D terrain generation explorer. Implements gradient-trick and DLA mountain generation techniques with real-time parameter tweaking and orbit camera controls.

### [zphp](https://github.com/nvms/zphp)

![ci](https://github.com/nvms/zphp/actions/workflows/ci.yml/badge.svg)

Zig-based PHP runtime with built-in HTTP server, package manager, test runner, formatter, and binary compiler.

### [gitcat](https://github.com/nvms/gitcat)

Self-hosted git server written in fur. Push, clone, and browse repositories over HTTP with a built-in web interface for viewing commit history, diffs, and syntax-highlighted source.

### [ti](https://github.com/nvms/ti)

![test](https://github.com/nvms/ti/actions/workflows/test.yml/badge.svg)

Functional language with pipe-first syntax that compiles to C. Algebraic types, Hindley-Milner inference, and a `metal` qualifier for runtime-free in-process systems work (DLLs, hooks, plugins). One language, one type system, both sides of the wall.

### [pastel-vue](https://github.com/nvms/pastel-vue)

![ci](https://github.com/nvms/pastel-vue/actions/workflows/ci.yml/badge.svg)

Pastel-toned Vue 3 component library covering primitives, forms, overlays, navigation, and data display, with a dedicated tier for AI tooling: token views, cost estimators, diff viewers, retrieval and citation displays, and evaluation scorecards. The full showcase is published at [nvms.github.io/pastel-vue](https://nvms.github.io/pastel-vue/).

### [huly-mcp](https://github.com/nvms/huly-mcp)

![ci](https://github.com/nvms/huly-mcp/actions/workflows/ci.yml/badge.svg)

Local MCP server that lets Claude manage a self-hosted Huly instance from a conversation: reading and updating issues, tracking estimated and actual time, leaving comments, and working the planner.

### [procmod](https://github.com/procmod)

Composable runtime game instrumentation primitives for Rust. Process memory, pattern scanning, function hooking, struct mapping, and overlay rendering.

| Crate | | | Description |
|-------|---|---|-------------|
| [procmod-core](https://github.com/procmod/procmod-core) | ![test](https://github.com/procmod/procmod-core/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-core) | Cross-platform process memory read/write |
| [procmod-scan](https://github.com/procmod/procmod-scan) | ![test](https://github.com/procmod/procmod-scan/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-scan) | Fast pattern and signature scanning for byte slices |
| [procmod-layout](https://github.com/procmod/procmod-layout) | ![test](https://github.com/procmod/procmod-layout/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-layout) | Struct mapping with pointer chain traversal via derive macros |
| [procmod-hook](https://github.com/procmod/hook) | ![test](https://github.com/procmod/hook/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-hook) | Inline function hooking and detouring |
| [procmod-overlay](https://github.com/procmod/overlay) | ![test](https://github.com/procmod/overlay/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-overlay) | Game overlay rendering with transparent click-through windows |

## Archived

### [@eaccess/auth](https://github.com/nvms/eaccess)

Postgres-backed auth for Express. Sessions, remember-me, email verification, password reset, OAuth (GitHub/Google/Azure), role bitmasks, 2FA (TOTP + email/SMS OTP + backup codes), activity logging. Archived in favor of [@prsm/auth](https://github.com/prsmjs/auth).

### [@threaded/ai](https://github.com/nvms/threaded)

Composable, provider-agnostic LLM workflow library. Functional pipelines over immutable conversation contexts. Supports OpenAI, Anthropic, Gemini, xAI, Ollama. Tool execution with approval, streaming, structured outputs, threads, embeddings, image generation, MCP integration. Archived in favor of [@prsm/ai](https://github.com/prsmjs/ai).

### [jsondelta](https://github.com/jsondelta)

Reversible JSON diffing, patching, and merging. The WASM serialization boundary made it slower than pure JS alternatives.

| Package | | Description |
|---------|---|-------------|
| [@jsondelta/diff](https://github.com/jsondelta/diff) | ![npm](https://img.shields.io/npm/v/@jsondelta/diff) | Structural JSON diffing with reversible deltas |
| [@jsondelta/patch](https://github.com/jsondelta/patch) | ![npm](https://img.shields.io/npm/v/@jsondelta/patch) | Patch application and delta inversion |
| [@jsondelta/merge](https://github.com/jsondelta/merge) | ![npm](https://img.shields.io/npm/v/@jsondelta/merge) | Three-way merge with conflict detection |

### [pyr](https://github.com/nvms/pyr)

Systems programming language with scripting ergonomics, built in Zig. Bytecode VM with NaN-boxed values, mark-sweep GC, arena-scoped memory for hot paths, green threads, algebraic types with pattern matching, UFCS, structural traits. Stdlib covers IO, networking, HTTP, TLS, and JSON. Ships with a package manager, formatter, and LSP.
